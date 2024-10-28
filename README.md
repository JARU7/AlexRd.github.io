# AlexRd.github.io
Clothing brand 
# FORGE Clothing Brand

## Tagline
**Made with a Purpose**

Welcome to the **FORGE Clothing Brand**! We offer stylish and durable clothing designed for modern lifestyles.

## Website Structure

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORGE Clothing Brand</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>FORGE Clothing Brand</h1>
        <p class="tagline">Made with a Purpose</p>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to FORGE! We offer stylish and durable clothing designed for modern lifestyles.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="images/product1.jpg" alt="Product 1">
            <h3>Product Name 1</h3>
            <p>Description of product 1.</p>
            <p>Price: $XX.XX</p>
        </div>
        <!-- Add more products as needed -->
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 FORGE Clothing Brand. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

