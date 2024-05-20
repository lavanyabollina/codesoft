<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: #f5f5dc; /* Light Beige Background */
            box-sizing: border-box;
            color: #333; /* Set default text color */
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h2 {
            margin: 0;
        }

        header p {
            margin: 0.5rem 0 0;
        }

        .container {
            padding: 2rem 1rem;
            margin: 1rem auto;
            max-width: 800px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section {
            margin-bottom: 2rem;
        }

        section:last-child {
            margin-bottom: 0;
        }

        #about {
            text-align: center;
        }

        #about .content {
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: left;
        }

        #about img {
            border-radius: 50%;
            margin-right: 1rem;
            width: 150px;
            height: 150px;
        }

        .bio {
            flex: 1;
        }

        #skills {
            text-align: center;
        }

        #skills .skills-container {
            display: flex;
            justify-content: space-around;
            margin-top: 2rem;
        }

        #skills img {
            border-radius: 50%;
            height: 120px;
            width: auto;
        }

        .project {
            display: flex;
            flex-direction: column;
        }

        .project-images {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .project-images img {
            width: calc(50% - 0.5rem);
            height: auto;
            border-radius: 8px;
        }

        .project-images .large-image {
            width: calc(50% - 0.5rem);
            height: 200px; /* Adjust the height to make the images smaller */
        }

        .project-description {
            padding: 1rem;
            background-color: #f9f9f9;
            border-radius: 8px;
            margin-top: 1rem;
            color: #333; /* Set text color */
        }

        .project-description p {
            margin: 0;
        }

        #resume a {
            display: inline-block;
            margin-top: 1rem;
            padding: 0.5rem 1rem;
            background: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
        }

        #contact p {
            margin: 0.5rem 0;
            color: #333; /* Set text color */
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
        }

        footer p {
            margin: 0;
        }

        .achievement {
            margin: 2rem 0;
        }

        .achievement img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
         .container {
    background:#faf0e6;# /* Light Beige Background */
}

.container img {
    background:#fff5ee; /* Light Beige Background */
}


        .achievement-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .achievement-item {
            flex: 1 1 calc(50% - 1rem);
            margin: 0.5rem;
            text-align: center;
            color: #333; /* Set text color */
        }

        .achievement-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .achievement-item-full {
            flex: 1 1 100%;
            margin: 0.5rem;
            text-align: center;
            color: #333; /* Set text color */
        }

        .achievement-item-full img {
            width: 50%;
            height: auto;
        }

        a {
            color: #333; /* Set link color */
        }
    </style>
</head>
<body>
    <header>
        <h2>Bollina Lavanya</h2>
        <p>A Frontend Developer</p>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <div class="content">
                <img src="about.png" alt="Bollina Lavanya">
                <div class="bio">
                    <p>My name is Bollina Lavanya, and I am a Computer Science Engineering (CSE) student with a strong passion for frontend development. Throughout my academic journey, I have developed a solid foundation in HTML, CSS, JavaScript, and Python. I have worked on several projects that have allowed me to apply my skills and learn new technologies. My recent internship at Codesoft in web development provided me with valuable real-world experience. I am enthusiastic about creating user-friendly and visually appealing web applications, and I am always eager to learn and take on new challenges in the field of web development.</p>
                </div>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <img src="html.png" alt="HTML">
                <img src="css.png" alt="CSS">
                <img src="javascript.png" alt="JavaScript">
                <img src="python.png" alt="Python">
                <img src="sql.png" alt="SQL">
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Organ Donation Management System</h3>
                <div class="project-images">
                    <img src="frontend.png" alt="Frontend Interface">
                    <img src="admin.png" alt="Admin Interface">
                    <img class="large-image" src="patients.png" alt="Patients Interface">
                    <img class="large-image" src="donars.png" alt="Donors Interface">
                </div>
                <div class="project-description">
                    <p>I developed this project using HTML and CSS to create web pages. The system consists of three modules: Admin, Donor, and Patients. Any user can register through the patients or donor registration form, and this information can only be accessed by the admin. The admin interface allows authorized personnel to manage the organ donation system, including approving donor registrations, monitoring organ availability, and overseeing the organ allocation process. This interface ensures a smooth and efficient workflow for organ donation management.</p>
                    <p>The patients interface provides patients with information about available organs and the status of their requests. It also allows them to register their interest in receiving an organ. The donors interface allows potential donors to register and provide details about the organs they are willing to donate.</p>
                </div>
            </div>
            <!-- Add more projects as needed -->
        </section>

        <section id="achievements">
            <h2>Achievements</h2>
            <div class="achievement-container">
                <div class="achievement-item">
                    <h3>Python Programming Essentials - Cisco</h3>
                    <img src="pythoncer.png" alt="Python Programming Essentials">
                    <p>Completed the Python Programming Essentials course at Cisco, gaining a comprehensive understanding of Python programming and its applications in various fields.</p>
                </div>
                <div class="achievement-item">
                    <h3>Programming Essentials in C - Cisco</h3>
                    <img src="cprogramming.png" alt="Programming in C">
                    <p>Completed the C Programming Essentials course at Cisco, gaining a comprehensive understanding of C programming and its applications in various fields.</p>
                </div>
                <div class="achievement-item-full">
                    <h3>Programming in Java - NPTEL</h3>
                    <img src="nptel-cer.png" alt="Programming in Java">
                    <p>Successfully completed the Programming in Java course on NPTEL with a score of 65%, learning the fundamentals of Java programming and its application in developing robust software solutions.</p>
                </div>
            </div>
        </section>

        <section id="resume">
            <h2>Resume</h2>
            <center>
                <p>Click on the button below</p>
                <a href="finalresume.pdf" download>Download My Resume</a>
            </center>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <center>
                <p>Email: <a href="mailto:lavanyabollina12@gmail.com">lavanyabollina12@gmail.com</a></p>
                <p>Phone: 63046*****</p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/lavanya-bollina-b670592b2/" target="_blank">lavanya-bollina</a></p>
            </center>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Bollina Lavanya. All rights reserved.</p>
    </footer>
</body>
</html>
