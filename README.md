# InstYle-Fashion
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InstYle Fashion - Premium Clothing</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">InstYle Fashion</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Welcome to InstYle Fashion</h1>
        <p>Discover premium clothing with style and comfort.</p>
        <a href="#products" class="cta-button">Shop Now</a>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2>Our Collection</h2>
        <div class="product-grid">
            <!-- Product Item -->
            <div class="product-card" data-editable>
                <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c" alt="Men's Jacket">
                <h3>Men's Premium Jacket</h3>
                <p class="description">Stylish and warm jacket for all seasons.</p>
                <p class="price">₹2,999</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product-card" data-editable>
                <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f" alt="Women's Dress">
                <h3>Women's Elegant Dress</h3>
                <p class="description">Perfect for parties and casual outings.</p>
                <p class="price">₹1,799</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product-card" data-editable>
                <img src="https://images.unsplash.com/photo-1525171254930-643fc83d3c66" alt="Men's Shirt">
                <h3>Men's Casual Shirt</h3>
                <p class="description">Comfortable cotton shirt for everyday wear.</p>
                <p class="price">₹1,299</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product-card" data-editable>
                <img src="https://images.unsplash.com/photo-1551488831-00ddcb6c6bd3" alt="Women's Top">
                <h3>Women's Chic Top</h3>
                <p class="description">Trendy top for a modern look.</p>
                <p class="price">₹999</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About InstYle Fashion</h2>
        <p>We are a premium clothing brand dedicated to bringing style, comfort, and affordability to your wardrobe. Our collections are designed with the modern Indian consumer in mind.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: support@instylefashion.com</p>
        <p>Phone: +91 98765 43210</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 InstYle Fashion. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

/* Header */
header {
    background: #333;
    color: #fff;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

nav a:hover {
    color: #f4a261;
}

/* Hero Section */
.hero {
    background: url('https://images.unsplash.com/photo-1445205170230-053211c18157') no-repeat center/cover;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
    padding: 0 2rem;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    background: #f4a261;
    color: #fff;
    padding: 0.8rem 2rem;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.1rem;
}

.cta-button:hover {
    background: #e76f51;
}

/* Products Section */
.products {
    padding: 4rem 2rem;
    background: #f9f9f9;
}

.products h2 {
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.product-card {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 1rem;
}

.product-card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

.product-card h3 {
    margin: 1rem 0 0.5rem;
    font-size: 1.2rem;
}

.product-card .description {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.product-card .price {
    color: #e76f51;
    font-size: 1.1rem;
    font-weight: bold;
    margin-bottom: 1rem;
}

.add-to-cart {
    background: #2a9d8f;
    color: #fff;
    border: none;
    padding: 0.6rem 1.2rem;
    border-radius: 5px;
    cursor: pointer;
}

.add-to-cart:hover {
    background: #264653;
}

/* About Section */
.about {
    padding: 4rem 2rem;
    text-align: center;
    background: #fff;
}

.about h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.about p {
    max-width: 800px;
    margin: 0 auto;
    font-size: 1.1rem;
}

/* Contact Section */
.contact {
    padding: 4rem 2rem;
    background: #f9f9f9;
    text-align: center;
}

.contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.contact p {
    font-size: 1.1rem;
    margin-bottom: 0.5rem;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    .hero h1 {
        font-size: 2rem;
    }

    .hero p {
        font-size: 1rem;
    }

    nav ul {
        flex-direction: column;
        gap: 1rem;
    }
}
