<!DOCTYPE html>
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
        }
        header {
            background-color: #4CAF50;
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
        }
        .content {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
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
        <form class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    <div class="social-media">
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">LinkedIn</a>
    </div>
</footer>

</body>
</html>
