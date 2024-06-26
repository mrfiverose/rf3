<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            background-image: url('https://picsum.photos/id/296/1600/900');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed; /* Background image fixed */
        }
        header {
            background-color: rgba(76, 175, 80, 0.8); /* Semi-transparent green */
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 2em;
            background-color: rgba(255, 255, 255, 0.9); /* Semi-transparent white */
            margin: 50px 0;
        }
        .content {
            max-width: 800px;
            margin: auto;
            background: rgba(255, 255, 255, 0.95); /* Semi-transparent white */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .video-wrapper {
            display: flex;
            justify-content: center;
        }
        .map-wrapper {
            display: flex;
            justify-content: center; /* Center the map horizontally */
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            left: 0;
            right: 0;
            z-index: 1; /* Ensure footer is above background image */
        }
        .social-media {
            margin-top: 1em;
        }
        .social-media a {
            margin: 0 10px;
            text-decoration: none;
            color: #4CAF50;
        }
        .contact-form label {
            display: block;
            margin-top: 10px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to RF3World (Singapore)</h1>
    <nav>
        <ul>
            <li><a href="#home">Introduction</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#blog">Our Services</a></li>
            <li><a href="#resources">Find us</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <div class="content">
        <h2>Introduction</h2>
        <p>Many perceive conquering a mountain as daunting, yet the real feat lies in embracing our weaknesses and courageously taking the necessary actions. </p>
    </div>
</section>

<section id="about">
    <div class="content">
        <h2>About Us</h2>
        <p>Many times, we feel helpless due to health issues, financial commitments, unforeseen circumstances, and the unpredictability of life. Royalty Vitality was formed to provide opportunities for self-improvement and empowerment when life happens. Our mission is to support individuals in navigating these challenges and to help them achieve a sense of stability and vitality.</p>
        <div class="video-wrapper">
            <iframe width="800" height="450" src="https://www.youtube.com/embed/Hy6j9o8FYb0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</section>

<section id="services">
    <div class="content">
        <h2>Services</h2>
        <p>Health Support Programs: Tailored plans to enhance physical and mental well-being.</p>
        <p>Financial Guidance: Expert advice to manage and improve your financial health.</p>
        <p>Life Coaching: Personalized coaching to help you navigate life's challenges.</p>
        <p>Community Support: A network of like-minded individuals offering mutual support and encouragement.</p>
        <!-- Blog posts will go here -->
    </div>
</section>

<section id="resources">
    <div class="content">
        <h2>Find Us</h2>
        <div class="map-wrapper">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.5665570290416!2d103.80240337412135!3d1.4352697612970964!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da13004b2d554b%3A0x78829c3624d9246d!2sPrimz%20BizHub!5e0!3m2!1sen!2ssg!4v1718863480362!5m2!1sen!2ssg" 
                width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
        <p>Our HP: +65 8774 1661.</p>
        <!-- Resource links will go here -->
    </div>
</section>

<section id="contact">
    <div class="content">
        <h2>Whether you have questions, need more information, or are ready to join, reach out to us. We'd love to hear from you!</h2>
        <form action="https://formspree.io/f/xvoeeqzv" method="POST" class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="whatsApp">WhatsApp ( Please include your country code, eg: +65 1234 5678 )</label>
            <input type="text" id="whatsApp" name="whatsApp" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Royalty Vitality. All rights reserved.</p>
    <div class="social-media">
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">LinkedIn</a>
    </div>
</footer>
</body>
</html>
