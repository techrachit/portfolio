<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #e9e7e7;
            color: #fff
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .skills-list, .projects-list {
            list-style: none;
            padding: 0;
        }
        .skills-list li, .projects-list li {
            margin-bottom: 10px;
        }
        .project-image {
            max-width: 100%;
            height: auto;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Hi Myself Rachit</h1>
    <p>Welcome to my website</p>
</header>

<section id="about">
    <h2>B.Tech Student </h2>
    <img src="C:\Users\rachi\Downloads\image.jpg" alt="Your Image" style="max-width: 150px; border-radius: 50%;">
    <p>Hello! I am Rachit Jain, a Student pursuing my gradution. I am fond of sports like cricket and also play indoor games such as chess.
        I enjoy working on creative projects that make an impact and inspires others. </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul class="skills-list">
        <li>Know Basic of C/C++ languses</li>
        <li>Can write basic programs in Java language</li>
        <li>Can speaak in more than 1 languages as follows English,Hindi,Marathi,Gujrati and Hadoti</li>
        <li>Have good communication skills</li>
        <li>Quick learner and Confident person</li>
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>
    <ul class="projects-list">
        <li>
            <h3>Magnum wheels robot</h3>
            <p>The robot running remotely by using code with the help of arduino uno, megnam wheels, motors etc.<br>
            It can be accessed with help of different software and devices such as phone.</p>
            <img src="C:\Users\rachi\Downloads\IMG1.jpeg" alt="Project 1 Image" class="project-image">
        </li>
    </ul>
</section>

<section id="resume">
    <h2>Resume</h2>
    <p><a href="" download>Download My Resume</a></p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:rachitjain768@gmail.com">rachitjain78@gmail.com</a></p>
</section>

<footer>
    <p>&copy; 2024 Rachit. All rights reserved.</p>
</footer>

</body>
</html>
