#tejas.github.io
<html>
<head>
    <meta charset="UTF-8" />
    <title>Tejas Sheth - Video Editor & Graphic Designer</title>
    <style>
        /* Internal CSS */

        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            background: #121212;
            color: #eee;
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(255,75,43,0.6);
        }

        header h1 {
            margin: 0;
            font-weight: 600;
            font-size: 3em;
            letter-spacing: 2px;
            text-shadow: 0 2px 6px rgba(0,0,0,0.4);
        }

        header p {
            font-weight: 300;
            font-size: 1.2em;
            margin-top: 10px;
            font-style: italic;
        }

        main {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 50px;
        }

        h2 {
            border-left: 6px solid #ff416c;
            padding-left: 15px;
            font-weight: 600;
            font-size: 2em;
            margin-bottom: 20px;
            color: #ff4b2b;
        }

        .about p {
            font-size: 1.15em;
            color: #ccc;
        }

        .skills-list, .projects-list {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skill, .project {
            background: #1e1e1e;
            border-radius: 10px;
            padding: 15px 20px;
            flex: 1 1 200px;
            box-shadow: 0 0 10px rgba(255,75,43,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .skill:hover, .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 20px #ff416c;
        }

        .skill {
            font-weight: 600;
            color: #ffffff;
            text-align: center;
            font-size: 1.1em;
        }

        .project img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 12px;
            object-fit: cover;
            height: 140px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }

        .project-title {
            font-weight: 600;
            font-size: 1.2em;
            margin-bottom: 5px;
            color: #ff416c;
        }

        .project-desc {
            font-size: 0.95em;
            color: #ddd;
        }

        footer {
            background: #222;
            padding: 20px;
            text-align: center;
            font-size: 0.9em;
            color: #888;
            border-top: 1px solid #444;
        }

        a.email-link {
            color: #ff416c;
            text-decoration: none;
            font-weight: 600;
        }

        a.email-link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header style="font-family: 'Poppins', sans-serif;">
    <h1>Tejas Sheth</h1>
    <p>Video Editor & Graphic Designer</p>
</header>

<main>
    <section class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Tejas Sheth, a creative video editor and graphic designer passionate about bringing stories to life through stunning visuals and seamless edits. I love turning ideas into eye-catching content that speaks volumes.</p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <div class="skills-list">
            <div class="skill" style="background: #ff4b2b;">Adobe Premiere Pro</div>
            <div class="skill" style="background: #ff416c;">Adobe After Effects</div>
            <div class="skill" style="background: #ff6e7f;">Final Cut Pro</div>
            <div class="skill" style="background: #ff416c;">Photoshop</div>
            <div class="skill" style="background: #ff4b2b;">Illustrator</div>
            <div class="skill" style="background: #ff6e7f;">DaVinci Resolve</div>
        </div>
    </section>

    <section class="projects">
        <h2>Projects</h2>
        <div class="projects-list">
            <div class="project">
                <img src="https://via.placeholder.com/300x140.png?text=Project+1" alt="Project 1 Screenshot" />
                <div class="project-title">Promo Video for Startup</div>
                <div class="project-desc">Created a dynamic promotional video using Adobe Premiere and After Effects to highlight brand strengths and services.</div>
            </div>

            <div class="project">
                <img src="https://via.placeholder.com/300x140.png?text=Project+2" alt="Project 2 Screenshot" />
                <div class="project-title">Event Poster Design</div>
                <div class="project-desc">Designed an eye-catching poster for a local music festival using Photoshop and Illustrator.</div>
            </div>

            <div class="project">
                <img src="https://via.placeholder.com/300x140.png?text=Project+3" alt="Project 3 Screenshot" />
                <div class="project-title">Social Media Video Ads</div>
                <div class="project-desc">Produced a series of short, engaging ads tailored for Instagram and Facebook platforms.</div>
            </div>
        </div>
    </section>

    <section class="contact" style="text-align: center;">
        <h2>Contact Me</h2>
        <p style="font-size: 1.1em; color: #ccc;">
            Feel free to reach out for collaboration or project inquiries!
        </p>
        <p>
            <a href="mailto:your-email@example.com" class="email-link" style="font-size: 1.2em;">your-email@example.com</a>
        </p>
    </section>
</main>

<footer>
    &copy; 2025 Tejas Sheth — All Rights Reserved.
</footer>

</body>
</html>
