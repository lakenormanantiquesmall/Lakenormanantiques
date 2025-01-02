# Lakenormanantiques
Official website for Lake Norman Antiques Mall, showcasing timeless treasures, luxury collectibles, and vintage charm. Located in Mooresville, NC, our collection includes exquisite antiques, rare decor, and unique heirlooms. Built for antique enthusiasts and collectors to explore and connect
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lake Norman Antiques Mall</title>
    <style>
        /* General styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f8f8f8;
        }
        header {
            background-color: #8e44ad;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 36px;
            margin: 0;
        }
        header p {
            font-size: 18px;
            margin: 10px 0;
        }
        header .cta-buttons a {
            text-decoration: none;
            color: white;
            background-color: #f4d03f;
            padding: 10px 20px;
            margin: 5px;
            border-radius: 5px;
            font-weight: bold;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        section h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 0 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .gallery p {
            margin: 10px 0;
            font-weight: bold;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea, .contact-form button {
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        footer a {
            color: #f4d03f;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Discover Timeless Treasures at Lake Norman Antiques Mall</h1>
        <p>Your destination for exquisite antiques, luxury collectibles, and vintage charm.</p>
        <p>Visit us at 467 E Plaza Dr, Mooresville, NC.</p>
        <div class="cta-buttons">
            <a href="#gallery">Shop Now</a>
            <a href="#contact">Contact Us</a>
        </div>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Located in the heart of Mooresville, NC, Lake Norman Antiques Mall is a haven for antique lovers, collectors, and interior design enthusiasts. Our curated collection includes rare antiques, elegant décor, and unique treasures that bring history and luxury together under one roof.</p>
        <p>We are passionate about preserving the charm of history while offering our clients exceptional service. Let us help you find that perfect piece to enrich your home or collection.</p>
    </section>

    <section id="gallery">
        <h2>Highlighted Treasures</h2>
        <div class="gallery">
            <!-- Add your product images -->
            <div>
                <img src="baccarat-candle-holders.jpg" alt="Baccarat Candle Holders">
                <p>Baccarat Candle Holders (French Crystal, Circa 1880, $64,000.00)</p>
            </div>
            <div>
                <img src="rosdorf-console-table.jpg" alt="Rosdorf Console Table">
                <p>Rosdorf Console Table (Antique Gold, $1,321.00)</p>
            </div>
            <div>
                <img src="bathroom-vanity.jpg" alt="Bathroom Vanity">
                <p>Randa Bathroom Vanity (Luxury Design, $16,425.00)</p>
            </div>
            <div>
                <img src="moissanite-watch.jpg" alt="Moissanite Watch">
                <p>Moissanite Watch Collection (Pink/Silver, $2,200.00)</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Our Location</h2>
        <p>Address: 467 E Plaza Dr, Mooresville, NC 28115, United States</p>
        <p>Email: <a href="mailto:lakeormanantiquemall@gmail.com">lakeormanantiquemall@gmail.com</a></p>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Lake Norman Antiques Mall | <a href="#about">About Us</a> | <a href="#gallery">Shop</a> | <a href="#contact">Contact</a></p>
        <p>Follow us on social media for the latest updates!</p>
    </footer>
</body>
</html>