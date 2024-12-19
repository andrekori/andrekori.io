<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learn Ice Skating</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #0088cc;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 1rem 0;
        }
        nav a {
            text-decoration: none;
            color: #0088cc;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 1rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .video {
            margin: 2rem 0;
        }
        .video iframe {
            width: 100%;
            height: 400px;
            border: none;
        }
        footer {
            background-color: #0088cc;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Learn Ice Skating</h1>
        <p>Your guide to mastering the ice!</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#blogs">Blogs</a>
        <a href="#videos">Videos</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container" id="home">
        <h2>Welcome!</h2>
        <p>Whether you're a complete beginner or looking to refine your skills, this is the place for you. Explore our blogs and videos to start your journey on the ice.</p>
    </div>

    <div class="container" id="blogs">
        <h2>Latest Blogs</h2>
        <ul>
            <li><strong>5 Tips for Beginners:</strong> Learn the basics to get started.</li>
            <li><strong>Choosing the Right Skates:</strong> What to look for in a good pair of skates.</li>
            <li><strong>Common Mistakes:</strong> Avoid these pitfalls as you learn.</li>
        </ul>
    </div>

    <div class="container video" id="videos">
        <h2>Instructional Videos</h2>
        <iframe src="https://www.youtube.com/embed/example" title="Ice Skating Basics"></iframe>
    </div>

    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>

            <button type="submit">Send</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Learn Ice Skating. All rights reserved.</p>
    </footer>
</body>
</html>
