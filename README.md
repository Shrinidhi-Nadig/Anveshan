<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anveshan Club | NIE College</title>
    <link rel="stylesheet" href="anveshan.css">
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
body {
    color: #333;
    background-color: #f9f9f9;
    line-height: 1.6;
}
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}
header .logo h1 {
    font-size: 2rem;
}
header .logo p {
    font-size: 1rem;
    color: #ccc;
}
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 0.5rem;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
.hero {
    background: url('hero.jpg') no-repeat center center/cover;
    color: #000000;
    padding: 4rem 1.5rem;
    text-align: center;
}
.hero-content {
    max-width: 600px;
    margin: 0 auto;
}
.hero-content h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}
.hero-content p {
    font-size: 1.25rem;
    margin-bottom: 2rem;
}
.btn {
    background: #333;
    color: #fff;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}
.about, .events, .contact {
    padding: 3rem 1.5rem;
    text-align: center;
}
.about h2, .events h2, .contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}
.about p, .contact p {
    max-width: 700px;
    margin: 0 auto;
}
.events .event-list {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
}
.events .event {
    background: #f0f0f0;
    padding: 1rem;
    border-radius: 5px;
}
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    font-size: 0.875rem;
}
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Anveshan Club</h1>
            <p>NIE College of Engineering, Mysore</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#Projects">Projects</a></li>
                <li><a href="#Research">Research</a></li>
                <li><a href="#Events">Events</a></li>
                <li><a href="#Resourse">Resourse</a></li>
                <li><a href="#Blog">Blog</a></li>
                <li><a href="#Members">Members</a></li>
                <li><a href="#contact">Contact Us</a></li>
                <li><a href="#Newsletter">Newsletter</a></li>
            </ul>
        </nav>
    </header>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Explore. Innovate. Inspire.</h2>
            <p>Join us on a journey to discover and push the boundaries of engineering excellence.</p>
            <a href="#about" class="btn">Learn More</a>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Anveshan Club</h2>
        <p>Anveshan Club is a platform for students to showcase their engineering skills through projects, workshops, and competitions. We aim to inspire innovation and foster a collaborative environment for budding engineers at NIE.</p>
    </section>
    <!-- Events Section -->
    <section id="events" class="events">
        <h2>Upcoming Events</h2>
        <div class="event-list">
            <div class="event">
                <h3>Workshop on Robotics</h3>
                <p>Date: 20th Nov 2024</p>
                <p>Learn the basics of robotics with hands-on experience in building and programming your own robot.</p>
            </div>
            <div class="event">
                <h3>Hackathon 2024</h3>
                <p>Date: 5th Dec 2024</p>
                <p>A 24-hour hackathon to showcase your coding skills and creativity. Exciting prizes await!</p>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: anveshan@nie.edu</p>
        <p>Phone: +91 9876543210</p>
        <p>Follow us on social media for the latest updates.</p>
    </section>
    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Anveshan Club, NIE College of Engineering, Mysore</p>
    </footer>
</body>
</html>
