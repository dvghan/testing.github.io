<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dnyanesh | Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background: linear-gradient(135deg, #f0f4f8, #d9e2ec);
            color: #333;
        }
        header {
            background-color: #0077b6;
            color: white;
            padding: 2rem;
            text-align: center;
        }
        header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 1rem;
        }
        section {
            max-width: 800px;
            margin: auto;
            padding: 2rem;
        }
        h1 {
            margin-top: 0;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        .skill-card {
            background: white;
            border-radius: 10px;
            padding: 1rem;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            flex: 1 1 calc(33% - 1rem);
            min-width: 200px;
            text-align: center;
        }
        .skill-card img {
            width: 50px;
            height: 50px;
            margin-bottom: 0.5rem;
        }
        footer {
            background-color: #023e8a;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        @media (max-width: 600px) {
            .skills {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

<header>
    <img src="your_image_here.jpg" alt="Dnyanesh" style="width:120px; height:120px; border-radius: 50%;">
    <h1>Dnyanesh</h1>
    <p>Python Developer | Exploring Web Development & Microservices</p>
</header>

<section>
    <h2>About Me</h2>
    <p>
        Hi, I’m Dnyanesh — a Python developer currently expanding my skills into web development.
        I have a solid understanding of HTML and CSS, and I’m now diving deeper into creating 
        modern, interactive web apps. Lately, I’ve been exploring microservices architecture using 
        Python FastAPI to build scalable, efficient solutions.
    </p>

    <h2>Skills</h2>
    <div class="skills">
        <div class="skill-card">
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Python Icon">
            <h3>Python Development</h3>
            <p>Experienced in building backend solutions, automation, and APIs.</p>
        </div>
        <div class="skill-card">
            <img src="https://cdn-icons-png.flaticon.com/512/888/888859.png" alt="HTML CSS Icon">
            <h3>HTML & CSS</h3>
            <p>Creating responsive, clean, and visually appealing web pages.</p>
        </div>
        <div class="skill-card">
            <img src="https://cdn-icons-png.flaticon.com/512/919/919854.png" alt="FastAPI Icon">
            <h3>FastAPI & Microservices</h3>
            <p>Designing scalable APIs and microservices with FastAPI.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2025 Dnyanesh. All rights reserved.</p>
</footer>

</body>
</html>
