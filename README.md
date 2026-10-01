# Maryam098765.github.io
This is my personal portfolio website 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Maryam's Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #fff7f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            background: #f4b6c2;
            color: white;
        }

        header h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
            margin-bottom: 25px;
        }

        header a {
            text-decoration: none;
            background: white;
            color: #d66b7b;
            padding: 12px 25px;
            border-radius: 25px;
        }

        section {
            max-width: 850px;
            margin: 30px auto;
            padding: 30px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 3px 12px rgba(0,0,0,0.08);
        }

        h2 {
            color: #d66b7b;
            margin-bottom: 15px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .skills span {
            background: #f4b6c2;
            color: white;
            padding: 10px 18px;
            border-radius: 20px;
        }

        .project {
            padding: 20px;
            background: #fff0f2;
            border-radius: 10px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #f4b6c2;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Hi, I'm Maryam</h1>
        <p>Student | Web Designer | Beginner Developer</p>
        <a href="#about">Explore My Portfolio</a>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a student interested in web designing and technology.
            I am learning HTML and CSS and building my skills step by step.
        </p>
    </section>

    <section>
        <h2>My Skills</h2>

        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>Web Design</span>
            <span>Graphic Design</span>
        </div>
    </section>

    <section>
        <h2>My Education</h2>
        <p>Intermediate D.Com</p>
    </section>

    <section>
        <h2>My Projects</h2>

        <div class="project">
            <h3>My First Portfolio</h3>
            <p>
                A personal portfolio website created using HTML and CSS.
            </p>
        </div>
    </section>

    <section>
        <h2>Contact Me</h2>
        <p>Email: your-email@example.com</p>
    </section>

    <footer>
        <p>© 2026 Maryam. All Rights Reserved.</p>
    </footer>

</body>
</html>