<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Fashion Brand</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Your Fashion Brand</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#collection">Collection</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero">
            <h2>Welcome to Your Fashion Brand</h2>
            <p>Discover the latest trends in fashion.</p>
            <a href="#collection" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="about" class="content-section">
        <h2>About Us</h2>
        <p>At Your Fashion Brand, we believe in empowering people through fashion. Our collections are designed to make you feel confident, stylish, and comfortable.</p>
    </section>

    <section id="collection" class="content-section">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <h3>Summer Dress</h3>
                <p>$45.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <h3>Evening Gown</h3>
                <p>$120.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="product3.jpg" alt="Product 3">
                <h3>Classic Blazer</h3>
                <p>$75.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <section id="contact" class="content-section">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Your Fashion Brand. All rights reserved.</p>
    </footer>
</body>
</html>
