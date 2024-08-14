<?php require_once('Connections/mysqli.php'); ?>
<?php
if (!function_exists("GetSQLValueString")) {
function GetSQLValueString($theValue, $theType, $theDefinedValue = "", $theNotDefinedValue = "") 
{
  if (PHP_VERSION < 6) {
    $theValue = get_magic_quotes_gpc() ? stripslashes($theValue) : $theValue;
  }

  $theValue = function_exists("mysql_real_escape_string") ? mysql_real_escape_string($theValue) : mysql_escape_string($theValue);

  switch ($theType) {
    case "text":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;    
    case "long":
    case "int":
      $theValue = ($theValue != "") ? intval($theValue) : "NULL";
      break;
    case "double":
      $theValue = ($theValue != "") ? doubleval($theValue) : "NULL";
      break;
    case "date":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;
    case "defined":
      $theValue = ($theValue != "") ? $theDefinedValue : $theNotDefinedValue;
      break;
  }
  return $theValue;
}
}

mysql_select_db($database_mysqli, $mysqli);
$query_login_member = "SELECT * FROM member";
$login_member = mysql_query($query_login_member, $mysqli) or die(mysql_error());
$row_login_member = mysql_fetch_assoc($login_member);
$totalRows_login_member = mysql_num_rows($login_member);
?>
<?php
// *** Validate request to login to this site.
if (!isset($_SESSION)) {
  session_start();
}

$loginFormAction = $_SERVER['PHP_SELF'];
if (isset($_GET['accesscheck'])) {
  $_SESSION['PrevUrl'] = $_GET['accesscheck'];
}

if (isset($_POST['user'])) {
  $loginUsername=$_POST['user'];
  $password=$_POST['upass'];
  $MM_fldUserAuthorization = "";
  $MM_redirectLoginSuccess = "index.php";
  $MM_redirectLoginFailed = "m_login.php";
  $MM_redirecttoReferrer = true;
  mysql_select_db($database_mysqli, $mysqli);
  
  $LoginRS__query=sprintf("SELECT `user`, upass FROM member WHERE `user`=%s AND upass=%s",
    GetSQLValueString($loginUsername, "-1"), GetSQLValueString($password, "text")); 
   
  $LoginRS = mysql_query($LoginRS__query, $mysqli) or die(mysql_error());
  $loginFoundUser = mysql_num_rows($LoginRS);
  if ($loginFoundUser) {
     $loginStrGroup = "";
    
	if (PHP_VERSION >= 5.1) {session_regenerate_id(true);} else {session_regenerate_id();}
    //declare two session variables and assign them
    $_SESSION['MM_Username'] = $loginUsername;
    $_SESSION['MM_UserGroup'] = $loginStrGroup;	      

    if (isset($_SESSION['PrevUrl']) && true) {
      $MM_redirectLoginSuccess = $_SESSION['PrevUrl'];	
    }
    header("Location: " . $MM_redirectLoginSuccess );
  }
  else {
    header("Location: ". $MM_redirectLoginFailed );
  }
}
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        .container {
            background: #ffffff;
            border-radius: 15px;
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
            max-width: 400px;
            width: 100%;
            padding: 40px;
            box-sizing: border-box;
            position: relative;
            text-align: center;
            animation: fadeIn 1s ease-in;
        }
        .container::before {
            content: '';
            position: absolute;
            top: -50px;
            left: 50%;
            transform: translateX(-50%);
            width: 120px;
            height: 120px;
            background: radial-gradient(circle, #0072ff 0%, #00c6ff 100%);
            border-radius: 50%;
            box-shadow: 0 0 30px rgba(0, 114, 255, 0.5);
            z-index: -1;
            animation: pulse 2s infinite;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.5; }
            100% { transform: scale(1); opacity: 1; }
        }
        h2 {
            margin: 0 0 30px;
            font-size: 32px;
            color: #333;
            font-weight: 700;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
        }
        .input-group {
            margin-bottom: 20px;
            position: relative;
        }
        .input-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #666;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .input-group input {
            width: 85%;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: border-color 0.3s, box-shadow 0.3s;
        }
        .input-group input:focus {
            border-color: #0072ff;
            outline: none;
            box-shadow: 0 0 8px rgba(0, 114, 255, 0.3);
        }
        .login-button {
            width: 100%;
            padding: 15px;
            background: #0072ff;
            border: none;
            border-radius: 8px;
            color: white;
            font-size: 18px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s, box-shadow 0.2s;
        }
        .login-button:hover {
            background-color: #0056b3;
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .signup-link {
            margin-top: 20px;
            font-size: 16px;
            color: #666;
        }
        .signup-link a {
            color: #0072ff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }
        .signup-link a:hover {
            color: #0056b3;
            text-decoration: underline;
        }
    body,td,th {
	font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
    </style>
</head>
<body>

    <form name="form1" method="post" action="">
    </form>
    <div class="container">
      <img src="image/logo.png" width="150" height="154">
      <h2>เข้าสู่ระบบนักเรียน นักศึกษา      </h2>
      <form action="<?php echo $loginFormAction; ?>" method="POST">
          <div class="input-group">
                <label for="user">ชื่อผู้ใช้งาน</label>
            <label for="user2"></label>
            <input type="text" name="user" id="user2">
        </div>
            <div class="input-group">
                <label for="upass">รหัสผ่าน</label>
                <input type="password" id="upass" name="upass" required>
        </div>
            <button type="submit" class="login-button">เข้าสู่ระบบ</button>
      </form>
        <div class="signup-link">
            คุณยังไม่มีบัญชีผู้ใช้งานใช่ไหม? <a href="register.php"> สมัครสมาชิก</a>
        </div>
</div>
</body>
</html>
<?php
mysql_free_result($login_member);
?>
