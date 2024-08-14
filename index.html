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
$query_member_rec = "SELECT * FROM member";
$member_rec = mysql_query($query_member_rec, $mysqli) or die(mysql_error());
$row_member_rec = mysql_fetch_assoc($member_rec);
$totalRows_member_rec = mysql_num_rows($member_rec);
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ระบบสารสนเทศ วท.นร</title>
    <!-- Link to Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@400;500;700&family=Kanit:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Sarabun', sans-serif;
            background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 150vh;
            margin: 0;
            color: #333;
        }
        .container {
            background: #ffffff;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
            padding: 30px;
            width: 50%;
            max-width: 1000px;
            overflow: hidden;
            position: relative;
            text-align: center;
        }
        h1 {
            font-family: 'Kanit', sans-serif;
            font-size: 36px;
            margin-bottom: 30px;
            color: #004d40;
            font-weight: 700;
            text-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: color 0.3s, transform 0.3s;
        }
        h1:hover {
            color: #00796b;
            transform: scale(1.05);
        }
        .image-group {
            display: flex;
            justify-content: center;
            gap: 20px;
            overflow-x: auto;
            padding: 20px 0;
        }
        .image-group::-webkit-scrollbar {
            height: 12px;
        }
        .image-group::-webkit-scrollbar-thumb {
            background: #0072ff;
            border-radius: 6px;
        }
        .image-group::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        .image-group img {
            width: 220px;
            height: 160px;
            object-fit: cover;
            border-radius: 12px;
            border: 4px solid #ddd;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.4s, border-color 0.4s, box-shadow 0.4s;
        }
        .image-group img:nth-child(1) {
            border-color:;
        }
        .image-group img:nth-child(2) {
            border-color: #ff5722;
        }
        .image-group img:hover {
            transform: scale(1.1);
            border-color: #0056b3;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }
        .group-info {
            margin-top: 30px;
            font-size: 18px;
            color: #666;
            line-height: 1.8;
            text-align: left;
            position: relative;
        }
        .group-info div {
            margin: 15px 0;
            font-family: 'Kanit', sans-serif;
            font-weight: 700;
            color: #004d40;
            position: relative;
            padding-bottom: 10px;
            transition: color 0.3s, transform 0.3s;
        }
        .group-info div:hover {
            color: #00796b;
            transform: translateX(5px);
        }
        .group-info div::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 60px;
            height: 3px;
            background: #0072ff;
            border-radius: 3px;
            transform: scaleX(0);
            transform-origin: bottom right;
            transition: transform 0.4s;
        }
        .group-info div:hover::after {
            transform: scaleX(1);
            transform-origin: bottom left;
        }
        .group-info p {
            margin: 5px 0;
            padding: 0 10px;
        }
    .image-group1 {            display: flex;
            justify-content: center;
            gap: 20px;
            overflow-x: auto;
            padding: 20px 0;
}
    </style>
</head>
<body>
    <div class="container">	
        <h1><img src="image/logo.png" width="130" height="134"></h1>
        <h1>ระบบสารสนเทศ วท.นร</h1>
        <div class="image-group"><a href="m_login.php"><span class="image-group1"><a href="m_login.php"><img src="image/12.jpg" alt="กลุ่มนักเรียน นักศึกษา"></a><a href="a_login.php"><img src="image/1111.jpg" alt="กลุ่มผู้ดูแลระบบ"></a>
        </div>
        <div class="group-info">
            <div>กลุ่มนักเรียน นักศึกษา</div>
            <p>รายละเอียดเกี่ยวกับกลุ่มนักเรียนและนักศึกษา เช่น เป้าหมาย, บทบาทในระบบสารสนเทศ, และอื่นๆ</p>
            
            <div>กลุ่มผู้ดูแลระบบ</div>
            <p>รายละเอียดเกี่ยวกับกลุ่มผู้ดูแลระบบ เช่น หน้าที่, ความรับผิดชอบ, และอื่นๆ</p>
        </div>
    </div>
</body>
</html>
<?php
mysql_free_result($member_rec);
?>
