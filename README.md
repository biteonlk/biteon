<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BiteOn</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header Styles */
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin: 0 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }

        /* Hero Section */
        .hero-section {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .hero-section h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .hero-section p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        .cta-button {
            background-color: green;
            padding: 12px 30px;
            font-size: 18px;
            text-decoration: none;
            color: white;
            border-radius: 5px;
            font-weight: bold;
        }

        /* Services Section */
        .services-section {
            display: flex;
            justify-content: space-around;
            padding: 40px 20px;
            text-align: center;
        }

        .service {
            width: 30%;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .service h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .service p {
            font-size: 1.1em;
            color: #555;
        }

        /* Products Section */
        .products-section {
            background-color: #f9f9f9;
            padding: 60px 20px;
        }

        .products-section h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.5em;
        }

        .product-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .product {
            width: 30%;
            background-color: white;
            text-align: center;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .product img {
            width: 35%;
            height: auto;
            margin-bottom: 10px;
            border-radius: 3px;
        }

        .product h3 {
            font-size: 1.4em;
            margin-bottom: 10px;
        }

        .product p {
            font-size: 1.2em;
            color: #333;
        }

        .buy-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 15px;
        }

        /* Contact Section */
        .contact-section {
            background-color: #fff;
            padding: 60px 20px;
            text-align: center;
        }

        .contact-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        .contact-form button {
            background-color: #28a745;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <h1>Welcome to BiteOn Technologies Pvt Ltd.</h1>
        <p>Your trusted partner for all your computer repair and hardware needs!</p>
        <a href="#products" class="cta-button">Shop Now</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="services-section">
        <div class="service">
            <h3>Computer Repair</h3>
            <p>Get your computer fixed by certified experts. Fast, reliable, and affordable repairs!</p>
        </div>
        <div class="service">
            <h3>Custom PC Builds</h3>
            <p>Build your own custom PC with the latest parts. Tailored to meet your needs and budget.</p>
        </div>
        <div class="service">
            <h3>Upgrades & Maintenance</h3>
            <p>Keep your system up-to-date with the latest upgrades and maintain optimal performance.</p>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products-section">
        <h2>Shop Our Latest Products</h2>
        <div class="product-container">
            <div class="product">
                <img src="INTEL.jpg" alt="Intel Processors">
                <h3>Intel Processors</h3>
                <p>$300</p>
<br/>
                <a href="#" class="buy-button">Add to Cart</a>
            </div>
            <div class="product">
                <img src="img.jpg" alt="Graphics Card">
                <h3>Graphics Card</h3>
                <p>$700</p>
<br/>
                <a href="#" class="buy-button">Add to Cart</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form class="contact-form" action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 BiteOn Technologies Pvt Ltd. All rights reserved.</p>
    </footer>

</body>
</html>
