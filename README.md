# NurulAini-Portfolio
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
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Nurul Aini, a motivated Computer Science student with a passion for technology, problem-solving, and innovation. My academic journey has equipped me with a strong foundation in programming, algorithms, and software development, alongside hands-on experience in web development, data analysis, or machine learning.

I am proficient in Python, C++, Java, Power BI and thrive in collaborative environments where I can apply my technical and analytical skills to solve real-world challenges. Beyond academics, I actively seek opportunities to grow, contribute to impactful projects, and stay ahead of evolving technologies.</p>
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
