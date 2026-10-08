<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Jacky Masagnay | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f7fb;
            color: #222;
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            background: #0b3d91;
            padding: 18px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            color: white;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #55d6ff;
        }

        /* Hero */
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: white;
        }

        .hero h1 {
            font-size: 48px;
            color: #0b3d91;
            margin-bottom: 10px;
        }

        .hero h3 {
            font-size: 24px;
            color: #555;
            margin-bottom: 20px;
        }

        .hero p {
            max-width: 650px;
            margin: auto;
            color: #666;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: #0b3d91;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }

        .button:hover {
            background: #075dcc;
        }

        /* Sections */
        section {
            padding: 70px 10%;
        }

        section h2 {
            text-align: center;
            color: #0b3d91;
            margin-bottom: 35px;
            font-size: 32px;
        }

        /* About */
        .about {
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        /* Skills */
        .skills {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skill {
            background: white;
            padding: 15px 25px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }

        /* Projects */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }

        .project h3 {
            color: #0b3d91;
            margin-bottom: 10px;
        }

        .project p {
            color: #666;
        }

        /* Contact */
        .contact {
            text-align: center;
            background: white;
        }

        .contact p {
            margin: 10px 0;
        }

        .contact a {
            color: #0b3d91;
            text-decoration: none;
            font-weight: bold;
        }

        /* Footer */
        footer {
            background: #0b3d91;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Mobile */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }

            .hero h1 {
                font-size: 36px;
            }

            .hero h3 {
                font-size: 20px;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <h2>Jacky Masagnay</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Home -->
    <section class="hero" id="home">

        <h1>Jacky Masagnay</h1>

        <h3>Computer Engineering Student</h3>

        <p>
            Welcome to my portfolio. I am interested in software development,
            embedded systems, microcontrollers, automation, and technology.
        </p>

        <a href="#projects" class="button">
            View My Projects
        </a>

    </section>


    <!-- About -->
    <section id="about">

        <h2>About Me</h2>

        <div class="about">

            <p>
                I am Jacky Masagnay, a Computer Engineering student interested
                in developing software and hardware-based systems. I enjoy
                creating applications, working with microcontrollers, and
                developing technology solutions for real-world problems.
            </p>

        </div>

    </section>


    <!-- Skills -->
    <section id="skills">

        <h2>My Skills</h2>

        <div class="skills">

            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Arduino</div>
            <div class="skill">ESP32</div>
            <div class="skill">Embedded Systems</div>
            <div class="skill">IoT</div>
            <div class="skill">GitHub</div>

        </div>

    </section>


    <!-- Projects -->
    <section id="projects">

        <h2>My Projects</h2>

        <div class="projects">

            <div class="project">
                <h3>Cardiovascular Monitoring System</h3>

                <p>
                    A microcontroller-based system designed to monitor
                    heart-related information using sensors.
                </p>
            </div>


            <div class="project">
                <h3>Ready PH Offline Application</h3>

                <p>
                    An offline application concept designed to provide
                    useful information even without an internet connection.
                </p>
            </div>


            <div class="project">
                <h3>Automated Cable Measurement and Cutting</h3>

                <p>
                    An automated machine concept that measures and cuts
                    electrical cables according to the required length.
                </p>
            </div>


            <div class="project">
                <h3>ReceiScan OCR</h3>

                <p>
                    A receipt management system that uses OCR technology
                    to extract information from receipts.
                </p>
            </div>


            <div class="project">
                <h3>AI Microcontroller Projects</h3>

                <p>
                    Projects combining microcontrollers, sensors,
                    automation, and intelligent system concepts.
                </p>
            </div>

        </div>

    </section>


    <!-- Contact -->
    <section id="contact" class="contact">

        <h2>Contact Me</h2>

        <p>
            Email:
            <a href="mailto:jackymasagnay445@gmail.com">
                jackymasagnay445@gmail.com
            </a>
        </p>

        <p>
            GitHub:
            <a href="https://github.com/jackymasagnay445-debug"
               target="_blank">
                github.com/jackymasagnay445-debug
            </a>
        </p>

        <p>
            Philippines
        </p>

    </section>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Jacky Masagnay. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
