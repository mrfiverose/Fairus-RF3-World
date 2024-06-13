
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royalty Vitality - Personal Webpage</title>
    <style>
        /* Global reset and basic styling */
        body {
            font-family: 'Roboto', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        /* Header styling */
        header {
            background: linear-gradient(to right, #55D6AA, #5DD6B6);
            color: white;
            padding: 1em 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: relative;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            margin-top: 15px;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            transition: color 0.3s ease;
            padding-bottom: 5px;
            border-bottom: 2px solid transparent;
        }
        nav ul li a:hover {
            color: #5DD6B6;
            border-color: #5DD6B6;
        }

        /* Main content sections */
        section {
            padding: 4em 0;
            background: #f9f9f9;
            position: relative;
        }
        .content {
            max-width: 800px;
            margin: auto;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            background: white;
            position: relative;
            z-index: 1;
        }
        .content h2 {
            font-size: 2.8em;
            margin-bottom: 20px;
            color: #55D6AA;
        }
        .content p {
            font-size: 1.1em;
            line-height: 1.8;
        }

        /* Contact form */
        .contact-form label {
            display: block;
            margin-top: 15px;
            font-size: 1.1em;
            color: #555;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin-top: 8px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 1em;
        }
        .contact-form button {
            background-color: #55D6AA;
            color: white;
            padding: 14px 28px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 15px;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }
        .contact-form button:hover {
            background-color: #5DD6B6;
        }

        /* Footer styling */
        footer {
            background: linear-gradient(to right, #333, #444);
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 5px rgba(0,0,0,0.1);
        }
        .social-media {
            margin-top: 1em;
        }
        .social-media a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }
        .social-media a:hover {
            color: #5DD6B6;
        }

        /* Background image overlay */
        .background-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            background-image: url('https://source.unsplash.com/1600x900/?motivation');
            background-size: cover;
            background-position: center;
            filter: grayscale(80%) brightness(70%);
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .content {
                padding: 20px;
            }
            .contact-form input, .contact-form textarea {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="background-overlay"></div>
    <h1>Welcome to Royalty Vitality</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#resources">Resources</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <div class="content">
        <h2>Introduction</h2>
        <p>Welcome to our personal page where we share insights and resources on health, finance, money, mindset, and emotions. Dive in to explore more and improve your life in these essential areas.</p>
    </div>
</section>

<section id="about">
    <div class="content">
        <h2>About Us</h2>
        <p>Hi, We Royalty Vitality, are made of many individuals passionate about helping people achieve a balanced and fulfilling life. With a background, we provide valuable insights and practical tips on managing your health, finances, mindset, and emotions.</p>
    </div>
</section>

<section id="blog">
    <div class="content">
        <h2>Blog</h2>
        <p>Explore our latest posts on health, finance, money, mindset, and emotions.</p>
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
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/xvoeeqzv" method="POST" class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="whatsapp">WhatsApp</label>
            <input type="text" id="whatsapp" name="whatsapp" required>
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
