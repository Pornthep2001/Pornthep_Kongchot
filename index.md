<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - Pornthep Kongchot</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            display: flex;
            margin: 0;
            height: 100vh;
            background-color: #f5f5f5;
        }
        /* Sidebar */
        .sidebar {
            position: fixed;
            left: 0;
            top: 0;
            width: 250px;
            height: 100%;
            background-color: #333;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding-top: 20px;
            transition: width 0.3s;
        }
        .sidebar.collapsed {
            width: 80px;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            width: 100%;
            padding: 0;
        }
        nav ul li {
            width: 100%;
            text-align: center;
        }
        nav ul li a {
            display: block;
            padding: 15px;
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: background 0.3s;
        }
        nav ul li a:hover {
            background-color: #f39c12;
        }
        .toggle-btn {
            display: none;
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #333;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
        .content {
            margin-left: 250px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            transition: margin-left 0.3s;
        }
        .content.collapsed {
            margin-left: 80px;
        }
        .hero {
            background-color: white;
            border-radius: 10px;
            max-width: 800px;
            padding: 50px 20px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .hero img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 18px;
            color: #333;
            margin-bottom: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #2980b9;
        }
        @media (max-width: 768px) {
            .sidebar {
                width: 200px;
            }
            .content {
                margin-left: 200px;
            }
            .toggle-btn {
                display: block;
            }
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <div class="logo">Resume</div>
        <nav>
            <ul>
                <li><a href="index.html">หน้าแรก</a></li>
                <li><a href="#">ประวัติส่วนตัว</a></li>
                <li><a href="#">ประสบการณ์การทำงาน</a></li>
                <li><a href="#">การศึกษา</a></li>
                <li><a href="#">ติดต่อ</a></li>
            </ul>
        </nav>
    </div>
    <div class="content">
        <button class="toggle-btn" onclick="toggleSidebar()">☰</button>
        <section class="hero">
            <img src="Profile.png" alt="Profile Picture">
            <p>ยินดีต้อนรับสู่ประวัติส่วนตัวของ Pornthep Kongchot ผู้เชี่ยวชาญด้านไอที</p>
            <a href="index.html" class="btn">เรียนรู้เพิ่มเติมเกี่ยวกับฉัน</a>
        </section>
    </div>
    <script>
        function toggleSidebar() {
            const sidebar = document.querySelector('.sidebar');
            const content = document.querySelector('.content');
            sidebar.classList.toggle('collapsed');
            content.classList.toggle('collapsed');
        }
    </script>
</body>
</html>
