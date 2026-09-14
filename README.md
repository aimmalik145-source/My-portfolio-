# My-portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aimen Malik | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f7f8fc;
            color: #222;
            line-height: 1.6;
        }

        header {
            background: #111827;
            color: white;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h2 {
            font-size: 22px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            padding: 70px 8%;
        }

        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(135deg, #eef2ff, #ffffff);
        }

        .hero-content {
            max-width: 800px;
        }

        .hero h1 {
            font-size: 52px;
            color: #111827;
            margin-bottom: 15px;
        }

        .hero h1 span {
            color: #2563eb;
        }

        .hero p {
            font-size: 20px;
            color: #555;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            text-decoration: none;
            margin: 5px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #1d4ed8;
            transform: translateY(-2px);
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 40px;
            color: #111827;
        }

        .about {
            max-width: 850px;
            margin: auto;
            text-align: center;
            color: #555;
            font-size: 17px;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 15px;
            max-width: 1000px;
            margin: auto;
        }

        .skill {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.06);
            font-weight: bold;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            max-width: 1100px;
            margin: auto;
        }

        .project {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 18px rgba(0,0,0,0.07);
        }

        .project h3 {
            color: #2563eb;
            margin-bottom: 8px;
        }

        .project .meta {
            color: #777;
            font-size: 14px;
            margin-bottom: 12px;
        }

        .project ul {
            padding-left: 20px;
            margin-top: 12px;
        }

        .education-box,
        .certification-box {
            max-width: 850px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 5px 18px rgba(0,0,0,0.06);
            text-align: center;
        }

        .education-box h3,
        .certification-box h3 {
            color: #2563eb;
            margin-bottom: 8px;
        }

        .contact {
            background: #111827;
            color: white;
            text-align: center;
        }

        .contact .section-title {
            color: white;
        }

        .contact-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            background: #1f2937;
            padding: 12px 18px;
            border-radius: 8px;
        }

        .contact-info a:hover {
            background: #2563eb;
        }

        footer {
            background: #0b1120;
            color: #aaa;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }

        @media (max-width: 700px) {
            header {
                flex-direction: column;
                gap: 10px;
            }

            nav {
                text-align: center;
            }

            nav a {
                margin: 5px;
                display: inline-block;
            }

            .hero h1 {
                font-size: 38px;
            }

            .hero p {
                font-size: 17px;
            }

            section {
                padding: 55px 6%;
            }
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <h2>Aimen Malik</h2>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#education">Education</a>
            <a href="#certifications">Certifications</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>


    <!-- Hero -->
    <section class="hero">
        <div class="hero-content">

            <h1>Hi, I'm <span>Aimen Malik</span></h1>

            <p>
                BS Information Technology Student & Aspiring App Developer
            </p>

            <p>
                Flutter • Dart • Firebase • Web Development
            </p>

            <a href="#projects" class="btn">View My Projects</a>

            <a href="#contact" class="btn">Contact Me</a>

        </div>
    </section>


    <!-- About -->
    <section id="about">

        <h2 class="section-title">About Me</h2>

        <div class="about">

            <p>
                I am Aimen Malik, a BS Information Technology student
                interested in mobile application development and modern
                software technologies.
            </p>

            <p>
                I enjoy building practical applications using Flutter,
                Dart and Firebase. I am continuously improving my
                programming, problem-solving and development skills
                through academic and personal projects.
            </p>

        </div>

    </section>


    <!-- Skills -->
    <section id="skills">

        <h2 class="section-title">Skills</h2>

        <div class="skills">

            <div class="skill">Flutter</div>

            <div class="skill">Dart</div>

            <div class="skill">Firebase</div>

            <div class="skill">Cloud Firestore</div>

            <div class="skill">Firebase Authentication</div>

            <div class="skill">Git & GitHub</div>

            <div class="skill">HTML</div>

            <div class="skill">CSS</div>

            <div class="skill">JavaScript Basics</div>

        </div>

    </section>


    <!-- Projects -->
    <section id="projects">

        <h2 class="section-title">Projects</h2>

        <div class="projects">


            <!-- Project 1 -->
            <div class="project">

                <h3>Smart Study Planner</h3>

                <div class="meta">
                    2026 • FG Postgraduate College
                </div>

                <p>
                    A personalized study planning and productivity
                    mobile application designed to help students
                    organize study goals and track their progress.
                </p>

                <ul>
                    <li>Study goal management</li>
                    <li>Focus timer and study sessions</li>
                    <li>Progress tracking</li>
                    <li>Firebase Authentication</li>
                    <li>Cloud Firestore</li>
                    <li>AI-powered study assistance</li>
                </ul>

                <p style="margin-top:15px;">
                    <strong>Technology:</strong>
                    Flutter, Dart, Firebase
                </p>

            </div>


            <!-- Project 2 -->
            <div class="project">

                <h3>School Parent App</h3>

                <div class="meta">
                    2026 • Mobile App Bootcamp
                </div>

                <p>
                    A school communication mobile application that
                    connects parents, teachers and school administration.
                </p>

                <ul>
                    <li>Parent and school communication</li>
                    <li>Attendance information</li>
                    <li>Homework updates</li>
                    <li>School notices</li>
                    <li>Exam timetable and results</li>
                    <li>Leave request management</li>
                </ul>

                <p style="margin-top:15px;">
                    <strong>Technology:</strong>
                    Flutter, Dart, Firebase
                </p>

            </div>

        </div>

    </section>


    <!-- Education -->
    <section id="education">

        <h2 class="section-title">Education</h2>

        <div class="education-box">

            <h3>BS Information Technology</h3>

            <p>
                FG Postgraduate College
            </p>

            <p>
                2023 – 2027
            </p>

        </div>

    </section>


    <!-- Certifications -->
    <section id="certifications">

        <h2 class="section-title">Certifications</h2>

        <div class="certification-box">

            <h3>Certifications</h3>

            <p>
                Certifications will be added here.
            </p>

        </div>

    </section>


    <!-- Contact -->
    <section id="contact" class="contact">

        <h2 class="section-title">Contact Me</h2>

        <p>
            Feel free to connect with me through the following platforms.
        </p>

        <div class="contact-info">

            <a href="mailto:aimmalik143@gmail.com">
                📧 aimmalik143@gmail.com
            </a>

            <a href="tel:03356030836">
                📱 03356030836
            </a>

            <a href="https://www.linkedin.com/in/aim-malik-b2246538a"
               target="_blank">
                🔗 LinkedIn
            </a>

            <a href="https://github.com/Aimenmalik725-coder"
               target="_blank">
                💻 GitHub
            </a>

        </div>

    </section>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Aimen Malik. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
