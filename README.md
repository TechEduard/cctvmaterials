<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CCTV MATERIALS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>CCTV MATERIALS</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="banner">
            <h2>Your One-Stop CCTV Solution</h2>
            <p>Protect your home and business with our reliable CCTV systems.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-list">
            <div class="product">
                <img src="camera1.jpg" alt="CCTV Camera 1">
                <h3>HD CCTV Camera</h3>
                <p>Price: $100</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="camera2.jpg" alt="CCTV Camera 2">
                <h3>Wireless CCTV Camera</h3>
                <p>Price: $150</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="camera3.jpg" alt="CCTV Camera 3">
                <h3>Night Vision Camera</h3>
                <p>Price: $200</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 CCTV Store. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section#home {
    background-color: #f4f4f4;
    padding: 50px 20px;
    text-align: center;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0;
}

.btn {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    display: inline-block;
}

section#products {
    padding: 50px 20px;
    background-color: #fff;
}

.product-list {
    display: flex;
    justify-content: space-around;
}

.product {
    text-align: center;
    border: 1px solid #ddd;
    padding: 20px;
    width: 30%;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

.product img {
    width: 100%;
    height: auto;
}

section#contact {
    padding: 50px 20px;
    background-color: #f9f9f9;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 600px;
    margin: 0 auto;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
    margin-top: 20px;
}

footer {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

/* Responsive Styles */
@media (max-width: 768px) {
    .product-list {
        flex-direction: column;
    }

    .product {
        width: 100%;
        margin-bottom: 20px;
    }
}
