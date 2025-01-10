<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Amanda Carrillo Design - Graphic Design and Photography Portfolio">
    <title>Amanda Carrillo Design</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">
            <h1>ACRLO.GRPHCS</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#design-portfolio">Design</a></li>
                <li><a href="#photography-portfolio">Photography</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="theme-toggle">
            <button id="theme-btn">Toggle Theme</button>
        </div>
    </header>

    <section id="home">
        <div class="hero">
            <h2>Amanda Carrillo Design</h2>
            <p>Your vision brought to life through graphic design and photography.</p>
            <a href="#design-portfolio" class="cta">View Portfolio</a>
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Placeholder text for bio and background information. This section can include Amanda's experience, education, and a brief introduction.</p>
        <a href="#resume" class="cta">View Resume</a>
    </section>

    <section id="design-portfolio">
        <h2>Design Portfolio</h2>
        <div class="grid">
            <!-- Placeholder project cards -->
            <div class="project">
                <img src="placeholder.jpg" alt="Project 1">
                <h3>Project Title</h3>
                <p>Short description of the project.</p>
            </div>
            <div class="project">
                <img src="placeholder.jpg" alt="Project 2">
                <h3>Project Title</h3>
                <p>Short description of the project.</p>
            </div>
            <div class="project">
                <img src="placeholder.jpg" alt="Project 3">
                <h3>Project Title</h3>
                <p>Short description of the project.</p>
            </div>
        </div>
    </section>

    <section id="photography-portfolio">
        <h2>Photography Portfolio</h2>
        <div class="gallery">
            <!-- Placeholder photography cards -->
            <div class="photo">
                <img src="placeholder.jpg" alt="Photo 1">
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Photo 2">
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Photo 3">
            </div>
        </div>
    </section>

    <section id="services">
        <h2>Services</h2>
        <ul>
            <li>Graphic Design</li>
            <li>Photography</li>
            <li>Mural Work</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send</button>
        </form>
        <div class="socials">
            <a href="https://instagram.com" target="_blank">Instagram</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Amanda Carrillo Design. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
