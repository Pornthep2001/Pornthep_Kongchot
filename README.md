<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ประวัติส่วนตัวของ Pornthep Kongchot</title>
    <link rel="stylesheet" href="styles.css">
    <style>
 /* เพิ่มสไตล์ให้กับชื่อ */
.name-heading {
    font-size: 36px;
    font-weight: bold;
    color: rgb(83, 84, 85);
    text-transform: uppercase;
    letter-spacing: 2px;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
    transition: color 0.3s, transform 0.3s;
}
/* เอฟเฟกต์เมื่อเมาส์ hover ไปที่ชื่อ */
.name-heading:hover {
    color: rgb(68, 35, 216);
    transform: scale(1.1);
}
/* สไตล์แถบเมนู (Navbar) ที่ทำให้มันล็อคอยู่ที่ด้านบน */
header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #333; /* สีพื้นหลังแถบเมนู */
    color: white;
    z-index: 1000; /* ให้แถบเมนูอยู่เหนือเนื้อหาทั้งหมด */
    padding: 10px 20px;
}
/* ทำให้เมนูแสดงเป็นแนวนอน */
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}
nav ul li {
    margin: 0 15px;
}
nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}
nav ul li a:hover {
    color: #f39c12; /* เปลี่ยนสีเมื่อ hover */
}
/* เพิ่มระยะห่างจากเนื้อหาเมื่อแถบเมนูล็อคอยู่ที่ด้านบน */
body {
    margin-top: 80px; /* ขยับเนื้อหาให้พ้นจากแถบเมนู */
}
    </style>
</head>
<body>
    <!-- Header (Fixed Navbar) -->
    <header>
        <div class="logo">Resume</div>
        <nav>
            <ul>
                <li><a href="#">หน้าแรก</a></li>
                <li><a href="#">ประวัติส่วนตัว</a></li>
                <li><a href="#">ประสบการณ์การทำงาน</a></li>
                <li><a href="#">การศึกษา</a></li>
                <li><a href="#">ติดต่อ</a></li>
            </ul>
        </nav>
    </header>
    <!-- Main Content -->
    <section class="hero">
        <p>ยินดีต้อนรับสู่ประวัติส่วนตัวของ Pornthep Kongchot ผู้เชี่ยวชาญด้านไอที</p>
        <a href="#about" class="btn">เรียนรู้เพิ่มเติมเกี่ยวกับฉัน</a>
    </section>

</body>
</html>
