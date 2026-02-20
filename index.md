<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jagriti Yadav | CV Blog</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #667eea, #764ba2);
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: auto;
            background: #ffffff;
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header h1 {
            font-size: 32px;
            color: #333;
            margin-bottom: 5px;
        }

        .header p {
            color: #666;
            font-size: 15px;
        }

        .image-section {
            text-align: center;
            margin-bottom: 30px;
        }

        .image-section img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #667eea;
            transition: transform 0.3s ease;
        }

        .image-section img:hover {
            transform: scale(1.05);
        }

        section {
            margin-bottom: 30px;
        }

        section h2 {
            color: #667eea;
            margin-bottom: 10px;
            border-bottom: 2px solid #eee;
            padding-bottom: 5px;
        }

        section p {
            color: #444;
            line-height: 1.6;
        }

        ul {
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 8px;
        }

        .skills span {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 7px 14px;
            border-radius: 20px;
            margin: 5px 5px 0 0;
            font-size: 14px;
            transition: background 0.3s ease;
        }

        .skills span:hover {
            background: #764ba2;
        }

        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: #777;
        }

        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }

            .header h1 {
                font-size: 24px;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <div class="header">
        <h1>Jagriti Yadav</h1>
        <p>Web Developer | Computer Science Student | Nepal</p>
        <p>Email: jagriti86124@gmail.com</p>
    </div>

    <!-- Image Section with Dummy Photo -->
    <div class="image-section">
        <img src="https://via.placeholder.com/300" alt="Profile Photo">
        <p style="margin-top:10px; color:#777;">Profile Photo</p>
    </div>

    <section>
        <h2>About Me</h2>
        <p>
            I am a passionate third-year Computer Science student specializing in Web Development.
            I enjoy building responsive and user-friendly websites. My goal is to grow professionally,
            improve my communication skills, and become a successful entrepreneur in the future.
        </p>
    </section>

    <section>
        <h2>Skills</h2>
        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>Responsive Design</span>
            <span>Git & GitHub</span>
            <span>Basic React</span>
        </div>
    </section>

    <section>
        <h2>Education</h2>
        <p>Bachelor of Computer Science (3rd Year)</p>
    </section>

    <section>
        <h2>Projects</h2>
        <ul>
            <li>Personal Portfolio Website</li>
            <li>Food Blogging Website</li>
            <li>Restaurant Style Recipe Blog</li>
        </ul>
    </section>

    <section>
        <h2>Career Objective</h2>
        <p>
            To build a strong career in Web Development and create innovative digital solutions
            that make a positive impact.
        </p>
    </section>

    <div class="footer">
        © 2026 Jagriti Yadav | Hosted on GitHub Pages
    </div>

</div>

</body>
</html>
