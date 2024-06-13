
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
            background-image: url('https://picsum.photos/seed/pauljarvis/1600/900');
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
    <h1>Welcome to My Personal Page</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#resources">Resources</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <div class="content">
        <h2>Introduction</h2>
        <p>Welcome to my personal page where I share insights and resources on health, finance, money, mindset, and emotions. Dive in to explore more and improve your life in these essential areas.</p>
    </div>
</section>

<section id="about">
    <div class="content">
        <h2>About Me</h2>
        <p>Hi, I'm [Your Name], passionate about helping people achieve a balanced and fulfilling life. With a background in [your background], I provide valuable insights and practical tips on managing your health, finances, mindset, and emotions.</p>
    </div>
</section>

<section id="blog">
    <div class="content">
        <h2>Blog</h2>
        <p>Explore my latest posts on health, finance, money, mindset, and emotions.</p>
        <!-- Blog posts will go here -->
    </div>
</section>

<section id="resources">
    <div class="content">
        <h2>Resources</h2>
        <p>Check out these recommended books, articles, tools, and resources to help you on your journey.</p>
        <!-- Resource links will go here -->
    </div>
</section>

<section id="contact">
    <div class="content">
        <h2>Contact Me</h2>
        <form action="https://formspree.io/f/xvoeeqzv" method="POST" class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
             <label for="whatsApp">WhatsApp</label>
            <input type="whatsApp" id="whatsApp" name="whatsApp" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Muhammad Fairus Bin Hashim. All rights reserved.</p>
    <div class="social-media">
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">LinkedIn</a>
    </div>
</footer>

</body>
</html>
