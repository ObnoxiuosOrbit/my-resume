<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77a 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        section {
            padding: 20px;
        }
        .section-title {
            border-bottom: 2px solid #77a;
            margin-bottom: 10px;
            padding-bottom: 10px;
        }
        .resume-section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Your Name</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <section id="about" class="resume-section">
            <h2 class="section-title">About Me</h2>
            <p>Outgoing and sociable, I am one of the most hardworking individuals in the room. With extensive experience in game presentation statistics for the Detroit Tigers and other roles in IT, administration, and customer service, I bring a diverse skill set to the table.</p>
        </section>

        <section id="experience" class="resume-section">
            <h2 class="section-title">Experience</h2>
            <h3>Game Scorer</h3>
            <h4>Major League Baseball, Lakeland, FL</h4>
            <p>Accurately recorded and documented all aspects of each game, including player performance statistics and game events. Ensured every play was correctly logged, maintaining real-time accuracy in the scorebook.</p>
            
            <h3>Intern & Scout</h3>
            <h4>Perfect Game USA</h4>
            <p>Responsible for scouting and evaluating player performance, providing detailed reports, and supporting event operations.</p>
            
            <h3>Game Presentation Statistics Operator</h3>
            <h4>Detroit Tigers</h4>
            <p>Managed statistical data for game presentations, ensuring accuracy and timely updates during live events.</p>
        </section>

        <section id="education" class="resume-section">
            <h2 class="section-title">Education</h2>
            <h3>Bachelor's in Economics</h3>
            <h4>SUNY College - Oneonta</h4>
            <p>Graduated May 2022</p>
        </section>

        <section id="skills" class="resume-section">
            <h2 class="section-title">Skills</h2>
            <ul>
                <li>SQL</li>
                <li>Forecasting</li>
                <li>Budgeting</li>
                <li>Stata</li>
                <li>Excel</li>
                <li>Access</li>
                <li>Operations Research</li>
            </ul>
        </section>

        <section id="contact" class="resume-section">
            <h2 class="section-title">Contact</h2>
            <p>Email: your.email@example.com</p>
            <p>Phone: (123) 456-7890</p>
        </section>
    </div>
</body>
</html>
