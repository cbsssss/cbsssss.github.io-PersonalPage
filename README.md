<html>
<head>
    <style>
        body {
            background: linear-gradient(135deg, #e6f7ff, #cce0ff); /* Blue light blue gradient */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            color: #333;
            transition: background 0.3s ease;
        }

        .img-container {
            margin-top: 20px;
            text-align: center;
            animation: fadeIn 1s ease-out;
        }

        img {
            border: 5px solid #007BFF;
            border-radius: 50%;
            width: 200px;
            height: 200px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        img:hover {
            transform: scale(1.05);
        }

        .additional-images {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .additional-images img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            margin: 10px;
            border: 2px solid #007BFF;
            transition: transform 0.3s ease;
        }

        .additional-images img:hover {
            transform: scale(1.1);
        }

        h1 {
            color: #0056b3;
            margin-top: 20px;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 10px;
            border-radius: 5px;
            animation: slideInDown 0.8s ease-out;
        }

        nav {
            margin-top: 10px;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 10px;
            border-radius: 5px;
            animation: slideInDown 1s ease-out;
        }

        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #007BFF;
            font-weight: 600;
            padding: 8px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease, color 0.3s ease, transform 0.2s ease;
        }

        nav a:hover {
            background-color: #007BFF;
            color: white;
            transform: translateY(-2px);
        }

        section {
            background-color: rgba(240, 248, 255, 0.9);
            border-radius: 10px;
            padding: 25px;
            margin: 20px auto;
            width: 85%;
            max-width: 900px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeIn 1s ease-out;
        }

        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }

        h2, h3, h4, h5, h6 {
            color: #0056b3;
            border-bottom: 2px solid #b3d9ff;
            padding-bottom: 8px;
            margin-bottom: 15px;
        }

        ul {
            list-style-type: disc;
            padding-left: 25px;
            color: #555;
        }

        li {
            margin-bottom: 10px;
        }

        p {
            line-height: 1.7;
            color: #444;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideInDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
    <title>PERSONAL PAGE</title>
    <meta charset="UTF-8">
    <meta name="author" content="CABE">
    <meta name="keyword" content="HTML,CSS,JavaScript">
</head>
<body>
    <div class="img-container">
        <img src="img_cabe.jpg" alt="Me">
    </div>

    <h1>Benjie Cabe</h1>

    <nav>
        <a href="#Personal Data">Personal Data</a>
        <a href="#Achievements">Achievements</a>
        <a href="#Skills">Skills</a>
        <a href="#Educational Attainment">Educational Attainment</a>
        <a href="#Training/Workshop Attended">Training/Workshop Attended</a>
    </nav>

    <section id="Personal Data">
        <h2>Personal Data</h2>
        <p>Personal Data:</p>
        <ul>
            <li>Last Name: Cabe</li>
            <li>First Name: Benjie Mark</li>
            <li>Middle Name: Orpeza</li>
            <li>Birth Date: November 27, 2003</li>
            <li>Live In: Lower Balandasan, Mt.View, Mariveles, Bataan</li>
            <li>Contact Number: 09090813247</li>
        </ul>
    </section>

    <section id="Achievements">
        <h3>Achievements</h3>
        <p>Achievements:</p>
        <ul>
            <li>Honor Student in Elementary</li>
            <li>Honor Student in Junior High School</li>
            <li>Honor Student in Senior High School</li>
        </ul>
    </section>

    <section id="Skills">
        <h4>Skills</h4>
        <p>Skills:</p>
        <ul>
            <li>Computer Literacy</li>
            <li>Multitasking</li>
            <li>Problem Solving</li>
            <li>Leadership</li>
            <li>Professionalism</li>
        </ul>
    </section>

    <section id="Educational Attainment">
        <h5>Educational Attainment</h5>
        <p>Educational Attainment:</p>
        <ul>
            <li>Mt. View Elementary School</li>
            <li>Mariveles National High School- Cabcaben</li>
            <li>MSHS-Sitio Mabuhay Cabcaben</li>
            <li>Polytechnic University of the Philippines-Bataan</li>
        </ul>
    </section>

    <section id="Training/Workshop Attended">
        <h6>Training/Workshop Attended</h6>
        <p>Training/Workshop Attended:</p>
        <ul>
            <li>Former Census Enumerator</li>
            <li>On call in Camaya coast</li>
        </ul>
    </section>

    
</body>
</html>
