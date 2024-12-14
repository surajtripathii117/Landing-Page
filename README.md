# Landing-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 3em;
            margin: 0;
        }

        .hero p {
            font-size: 1.2em;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .section:nth-child(even) {
            background-color: #f9f9f9;
        }

        .columns {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .column {
            flex: 1;
            max-width: 30%;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Landing Page</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <div>
            <h1>Design. Develop. Deliver.</h1>
            <p>Your one-stop solution for all web development needs.</p>
        </div>
    </div>
    <div class="section" id="about">
        <h2>About Us</h2>
        <p>We are a team of dedicated developers, passionate about creating stunning and functional websites.</p>
    </div>
    <div class="section" id="services">
        <h2>Our Services</h2>
        <div class="columns">
            <div class="column">
                <h3>Web Design</h3>
                <p>Creating visually appealing and user-friendly designs.</p>
            </div>
            <div class="column">
                <h3>Development</h3>
                <p>Building robust and scalable web applications.</p>
            </div>
            <div class="column">
                <h3>SEO</h3>
                <p>Optimizing your website to rank higher on search engines.</p>
            </div>
        </div>
    </div>
    <div class="section" id="contact">
        <h2>Contact Us</h2>
        <p>Email: surajtripathi7254@gmail.com</p>
        <p>Phone: 8303003824</p>
    </div>
    <footer>
        <p>&copy; 2024 Landing Page. All rights reserved.</p>
    </footer>
</body>
</html>
