<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhaskar Prabha Foundation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f3e8;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #d9c5a8;
            padding: 20px;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            border-bottom: 5px solid #b8a089;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
            color: #4a3f35;
        }

        header img {
            width: 60px;
            height: auto;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #e5d5be;
            padding: 15px 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav a {
            margin: 0 20px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
            font-size: 18px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #7a5c48;
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .container h2 {
            color: #4a3f35;
            margin-bottom: 20px;
            border-bottom: 3px solid #d9c5a8;
            padding-bottom: 10px;
        }

        .contact-form {
            margin-top: 20px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }

        .contact-form button {
            padding: 12px 25px;
            background-color: #7a5c48;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s;
        }

        .contact-form button:hover {
            background-color: #4a3f35;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #d9c5a8;
            margin-top: 20px;
            color: #4a3f35;
            font-size: 16px;
        }

        iframe {
            width: 100%;
            height: 300px;
            border: none;
            border-radius: 8px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo">
        <h1>Bhaskar Prabha Foundation</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#programs">Programs</a>
        <a href="file:///C:/Users/astro/OneDrive/Desktop/professors/stats/contactus.html" target="_blank">Contact</a>
        <a href="#map">Location</a>
    </nav>

    <div class="container" id="home">
        <h2>Welcome to Bhaskar Prabha Foundation</h2>
        <p>Bhaskar Prabha Foundation started in 2022. Founded by Tejas Kulkarni Guruji, our mission is to explore ancient and modern mathematics.</p>
    </div>

    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: mail@Bhaskar Prabha Foundation.org</p>
        <p>Phone: 8275281687</p>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>

    <div class="container" id="map">
        <h2>Find Us</h2>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.3755757269796!2d73.8390548757232!3d18.52817011077281!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bc2c23c5293b163%3A0x5e688810d34617db!2s2%2C%20Anand%20Vihar%20Colony%20Rd%2C%20Mahadev%20Nagar%2C%20Vadgaon%20Budruk%2C%20Pune%2C%20Maharashtra%20411009!5e0!3m2!1sen!2sin!4v1611234567890" loading="lazy"></iframe>
    </div>

    <footer>
        <p>&copy; 2025 Bhaskar Prabha Foundation</p>
    </footer>
</body>
</html>
