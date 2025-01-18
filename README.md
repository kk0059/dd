<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #0078d7;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            margin: 0 1em;
            text-decoration: none;
            color: #0078d7;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin-top: 1em;
        }
        form input, form textarea, form button {
            margin-top: 0.5em;
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            background-color: #0078d7;
            color: white;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background-color: #005bb5;
        }
        footer {
            text-align: center;
            margin: 2em 0;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Business</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>We provide top-notch services to help your business succeed in the global market.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form action="https://example.com/submit-form" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Your Business Name. All rights reserved.</p>
    </footer>
</body>
</html>
