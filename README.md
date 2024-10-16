<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartNest - Smart Home Automation</title>
    <style>
       
        
/* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }
        a {
            text-decoration: none;
            color: white;
        }

   /* Header styles */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 15px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            margin: 10px 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }

   /* Hero section */
        .hero {
            background: url('https://images.unsplash.com/photo-1554188248-986adbb73bfe') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }
        .hero h2 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .hero button {
            padding: 10px 20px;
            background-color: #e74c3c;
            border: none;
            color: white;
            font-size: 1rem;
            cursor: pointer;
            margin-top: 20px;
        }

   /* Section styles */
        section {
            padding: 60px 20px;
        }
        .about, .products, .contact {
            text-align: center;
        }
        .about h2, .products h2, .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .about p, .products p {
            font-size: 1.2rem;
            margin: 10px auto;
            max-width: 800px;
        }
             .products-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product-item {
            background-color: white;
            padding: 20px;
            width: 30%;
            margin: 20px 0;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .product-item:hover {
            transform: scale(1.05);
        }
        .product-item img {
            width: 100%;
            border-radius: 10px;
        }
        .product-item h3 {
            font-size: 1.5rem;
            margin: 15px 0;
        }
        .product-item p {
            color: #777;
            font-size: 1rem;
        }
    /* Contact form */
        .contact form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact button {
            padding: 15px 20px;
            background-color: #2c3e50;
            border: none;
            color: white;
            cursor: pointer;
            width: 100%;
        }
     /* Footer styles */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

   /* Media Queries */
        @media (max-width: 768px) {
            .product-item {
                width: 90%;
            }
            .hero h2 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body><!-- Header -->
    <header>
        <h1>SmartNest</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <!-- Hero Section -->
    <div class="hero" id="home">
        <div>
            <h2>Welcome to SmartNest</h2>
            <p>Your trusted smart home solution provider</p>
            <button>Learn More</button>
        </div>
    </div>
<!-- About Section -->
    <section class="about" id="about">
        <h2>About SmartNest</h2>
        <p>At SmartNest, we revolutionize the way you live by integrating advanced smart home automation systems. With our easy-to-use technology, you can control every aspect of your home, from lights and security to appliances and energy consumption.</p>
    </section>
    <!-- Products Section -->
    <section class="products" id="products">
        <h2>Our Products</h2>
        <div class="products-grid">
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smart Security Camera">
                <h3>Smart Security Camera</h3>
                <p>Keep your home safe with our high-quality smart security cameras.</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smart Thermostat">
                <h3>Smart Thermostat</h3>
                <p>Efficiently control your home’s temperature with the latest smart thermostat technology.</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smart Lighting System">
                <h3>Smart Lighting System</h3>
                <p>Transform your home ambiance with energy-efficient smart lighting systems.</p>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/myemail" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="_replyto" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <!-- Footer -->
    <footer>
        <p>&copy; 2024 SmartNest. All rights reserved.</p>
    </footer>

</body>
</html>
