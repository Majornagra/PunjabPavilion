<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Punjab Pavilion</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #0073e6;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004a99;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #003366;
        }
        section {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }
        .team-member {
            margin: 20px 0;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        footer {
            background-color: #0073e6;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Punjab Pavilion</h1>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#team">Our Team</a>
        <a href="#events">Events</a>
        <a href="#gallery">Photo Gallery</a>
        <a href="#live">Live Link</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>Punjab Pavilion is a not-for-profit organization in Canada that organizes the annual three-day "Punjabi Mela - Festival of Punjab" in collaboration with CARABRAM Brampton. Punjab Pavilion showcases Punjabi culture through dance performances, songs, food, and fashion.</p>
    </section>
    <section id="team">
        <h2>Our Team</h2>
        <div class="team-member">
            <h3>Member 1</h3>
            <p>Brief bio of team member 1.</p>
        </div>
        <div class="team-member">
            <h3>Member 2</h3>
            <p>Brief bio of team member 2.</p>
        </div>
        <!-- Add more team members as needed -->
    </section>
    <section id="events">
        <h2>Events</h2>
        <p>Details about the "Punjabi Mela - Festival of Punjab" and other events organized by Punjab Pavilion.</p>
    </section>
    <section id="gallery">
        <h2>Photo Gallery</h2>
        <div class="gallery">
            <img src="photo1.jpg" alt="Event Photo 1">
            <img src="photo2.jpg" alt="Event Photo 2">
            <!-- Add more photos as needed -->
        </div>
    </section>
    <section id="live">
        <h2>Live Link</h2>
        <p>Watch our events live <a href="live-stream-url">here</a>.</p>
    </section>
    <footer>
        <p>© 2024 Punjab Pavilion. All rights reserved.</p>
    </footer>
</body>
</html>
