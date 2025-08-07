!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glamour Glitz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fffafc;
            color: #333;
        }
        header {
            background: linear-gradient(to right, #d8b4e2, #f5e1ff);
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 18px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #fff;
            padding: 10px 0;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            color: #a76cc3;
        }
        nav a:hover {
            color: #e3b8ff;
        }
        .hero {
            text-align: center;
            padding: 30px;
        }
        .hero img {
            width: 120px;
            border-radius: 50%;
        }
        .hero h1 {
            font-size: 28px;
            color: #a76cc3;
        }
        .hero p {
            font-size: 16px;
            color: #555;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product {
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            margin: 15px;
            padding: 20px;
            width: 250px;
            transition: 0.3s;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            border-radius: 12px;
        }
        .price {
            font-weight: bold;
            color: #a76cc3;
            margin: 10px 0;
        }
        .btn {
            display: inline-block;
            background: #a76cc3;
            color: white;
            padding: 8px 15px;
            border-radius: 8px;
            text-decoration: none;
        }
        .btn:hover {
            background: #8d55aa;
        }
        footer {
            background: #a76cc3;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .rating {
            color: gold;
            font-size: 14px;
        }
        .qr-footer img {
            width: 120px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>✨ Halper Kit – Just ₹499 ✨ Limited Time Offer</header>

<nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <img src="logo.jpg" alt="Glamour Glitz Logo">
    <h1>Glamour Glitz</h1>
    <p>We Balance Beauty With Nature</p>
</section>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>At Glamour Glitz, we believe skincare should be pure, effective, and affordable. 
    Our Halper Kit is 100% nature-based, chemical-free, and perfect for all skin types and ages.</p>
</section>

<section id="products" class="section">
    <h2>Our Products</h2>
    <div class="products">
        <div class="product">
            <img src="foam_cleanser.jpg" alt="Foam Cleanser">
            <h3>Foam Cleanser (150ml)</h3>
            <div class="rating">★★★★★</div>
            <p>Gently removes dirt without stripping skin.</p>
            <p class="price">₹ 149</p>
            <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Foam%20Cleanser" class="btn">Buy Now</a>
        </div>
        <div class="product">
            <img src="toner.jpg" alt="Natural Toner">
            <h3>Natural Toner (100ml)</h3>
            <div class="rating">★★★★★</div>
            <p>Tightens pores and hydrates skin.</p>
            <p class="price">₹ 149</p>
            <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Natural%20Toner" class="btn">Buy Now</a>
        </div>
        <div class="product">
            <img src="serum.jpg" alt="Face Serum">
            <h3>Face Serum (30ml)</h3>
            <div class="rating">★★★★★</div>
            <p>Vitamin-rich for glow and repair.</p>
            <p class="price">₹ 249</p>
            <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Face%20Serum" class="btn">Buy Now</a>
        </div>
        <div class="product">
            <img src="moisturizer.jpg" alt="Moisturizer">
            <h3>Moisturizer (125ml)</h3>
            <div class="rating">★★★★★</div>
            <p>Non-greasy, long-lasting hydration.</p>
            <p class="price">₹ 199</p>
            <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Moisturizer" class="btn">Buy Now</a>
        </div>
        <div class="product">
            <img src="lipbalm.jpg" alt="Lip Balm">
            <h3>Lip Balm (10ml)</h3>
            <div class="rating">★★★★★</div>
            <p>Keeps lips soft and nourished.</p>
            <p class="price">₹ 99</p>
            <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Lip%20Balm" class="btn">Buy Now</a>
        </div>
    </div>
</section>

<section class="section">
    <h2>Halper Kit Combo</h2>
    <p>All 5 products in one – only ₹ 499</p>
    <a href="https://wa.me/916351137898?text=I%20want%20to%20order%20Halper%20Kit%20Combo" class="btn">Buy Now</a>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:aryan1225sharma@gmail.com">aryan1225sharma@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/glamourglitsco">@glamourglitsco</a></p>
    <p>WhatsApp: <a href="https://wa.me/916351137898">+91 6351137898</a></p>
</section>

<footer>
    <p>&copy; 2025 Glamour Glitz. All Rights Reserved.</p>
    <div class="qr-footer">
        <img src="qr_code.png" alt="QR Code">
    </div>
</footer>

</body>
</html>
