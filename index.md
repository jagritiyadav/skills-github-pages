<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jagruti Yadav | Web Developer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea, #764ba2);
            padding: 20px;
        }

        .cv-container {
            max-width: 900px;
            margin: auto;
            background: #ffffff;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #667eea;
            margin-bottom: 15px;
        }

        .header h1 {
            font-size: 32px;
            color: #333;
        }

        .header p {
            color: #666;
            margin-top: 5px;
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

        ul {
            list-style: square;
            padding-left: 20px;
        }

        .skills span {
            display: inline-block;
            background: #667eea;
            color: #fff;
            padding: 8px 12px;
            border-radius: 20px;
            margin: 5px 5px 0 0;
            font-size: 14px;
        }

        .footer {
            text-align: center;
            margin-top: 20px;
            color: #777;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            .cv-container {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

<div class="cv-container">

    <div class="header">
        <img src="profile.jpg" alt="Jagruti Yadav">
        <h1>Jagruti Yadav</h1>
        <p>Web Developer | Computer Science Student | Future Entrepreneur</p>
        <p>Email: yourmail@gmail.com | Nepal</p>
    </div>

    <section>
        <h2>About Me</h2>
        <p>
            I am a passionate third-year Computer Science student specializing in Web Development.
            I enjoy building responsive and user-friendly websites. My goal is to become a confident
            web developer and successful businesswoman in the future.
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
            To build a strong career in Web Development, improve my communication skills,
            and create innovative digital solutions that make an impact.
        </p>
    </section>

    <div class="footer">
        © 2026 Jagruti Yadav | Hosted on GitHub Pages
    </div>

</div>

</body>
</html>
