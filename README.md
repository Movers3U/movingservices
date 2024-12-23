# movingservices  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3U Movers - Moving Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #0056b3;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            text-align: center;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2rem;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .service {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            text-align: center;
        }
        .service h3 {
            color: #007BFF;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .contact {
            background: #f4f4f4;
            padding: 20px;
            margin: 20px 0;
        }
        .contact form {
            display: grid;
            gap: 15px;
        }
        .contact input, .contact textarea, .contact button {
            padding: 10px;
            font-size: 1rem;
        }
        .contact button {
            background: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
        }
        .contact button:hover {
            background: #0056b3;
        }
        .fixed-buttons {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .fixed-buttons a {
            display: flex;
            align-items: center;
            justify-content: center;
            background: #007BFF;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 50px;
            font-size: 1.2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: background 0.3s;
        }
        .fixed-buttons a:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to 3U Movers</h1>
        <p>Your Trusted Moving Partner</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact Us</a>
        <a href="#faq">FAQ</a>
    </nav>
    <div class="hero">
        Professional Moving Services at Affordable Prices
    </div>
    <div class="container">
        <section id="services">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>Residential Moving</h3>
                    <p>We handle your home relocation with care and efficiency.</p>
                </div>
                <div class="service">
                    <h3>Commercial Moving</h3>
                    <p>Office and business moving services tailored to your needs.</p>
                </div>
                <div class="service">
                    <h3>Packing Services</h3>
                    <p>Expert packing to keep your belongings safe during transit.</p>
                </div>
                <div class="service">
                    <h3>Storage Solutions</h3>
                    <p>Secure and flexible storage options for your convenience.</p>
                </div>
            </div>
        </section>
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
        <section id="faq">
            <h2>Frequently Asked Questions</h2>
            <p><strong>Q: How much do your moving services cost?</strong></p>
            <p>A: Our pricing depends on the distance and the size of your move. Contact us for a free quote!</p>
            <p><strong>Q: Do you offer insurance for items?</strong></p>
            <p>A: Yes, we provide optional insurance coverage for your valuable items.</p>
        </section>
    </div>
    <div class="fixed-buttons">
        <a href="tel:+123456789" title="Call Us">📞 Call Us</a>
        <a href="https://wa.me/123456789" target="_blank" title="WhatsApp Us">💬 WhatsApp</a>
    </div>
    <footer>
        <p>&copy; 2024 3U Movers. All Rights Reserved.</p>
    </footer>
</body>
</html>
