<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#affiliations">Affiliations</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a web developer with a passion for creating beautiful and functional websites. I love coding and learning new technologies.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
            <li>Git & GitHub</li>
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <ul>
            <li>Bachelor of Science in Computer Science - University XYZ (2018 - 2022)</li>
            <li>Web Development Bootcamp - Online Course (2022)</li>
        </ul>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1. This project is about...</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2. This project is about...</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Project 3</h3>
            <p>Description of project 3. This project is about...</p>
            <a href="#">View Project</a>
        </div>
    </section>

    <section id="interests">
        <h2>Interests</h2>
        <ul>
            <li>Web Development</li>
            <li>Open Source Contribution</li>
            <li>Artificial Intelligence</li>
            <li>Traveling</li>
            <li>Photography</li>
        </ul>
    </section>

    <section id="affiliations">
        <h2>Affiliations</h2>
        <ul>
            <li>Member of the Web Developers Association</li>
            <li>Contributor to Open Source Projects on GitHub</li>
            <li>Volunteer at Local Coding Bootcamps</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, feel free to reach out!</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
