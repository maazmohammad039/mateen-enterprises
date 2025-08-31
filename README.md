<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" /><meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mateen Enterprises</title>
  <style>
    body { margin:0; font-family: Arial, sans-serif;
           background: url('https://img.freepik.com/free-photo/clothing-store-interior_1232-1682.jpg') no-repeat center center fixed;
           background-size: cover; }
    header, nav, section, footer { background: rgba(255,255,255,0.9); margin: 0 20px; border-radius: 10px; padding: 20px; }
    header { text-align: center; }
    nav { display: flex; justify-content: center; gap:15px; }
    nav a { text-decoration:none; color:#333; font-weight:bold; }
    .products { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
    .product { width:200px; background:white; padding:15px; border-radius:8px; text-align:center; box-shadow:0 4px 8px rgba(0,0,0,0.1); }
    .product img { width:100%; height:150px; object-fit:cover; border-radius:5px; }
    .order-button { display:inline-block; margin-top:8px; padding:8px 15px; background:#25D366; color:white; border-radius:5px; text-decoration:none; font-weight:bold; }
    footer { text-align:center; margin: 20px; padding: 20px; background: rgba(0,0,0,0.7); color: white; border-radius:8px; }
    form input { width:100%; padding:8px; margin:5px 0; }
    form button { padding:10px 20px; background:#333; color:white; border:none; border-radius:5px; }
  </style>
</head>
<body>

  <header>
    <h1>Mateen Enterprises</h1>
    <p>Your trusted clothing shop in Sawai Madhopur, Rajasthan</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#services">Services</a>
    <a href="#order">Order</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>We are a local clothing shop in Sawai Madhopur, offering stylish jeans, shirts, trousers, cargo pants, t-shirts, and lowers—all under ₹5000.</p>
  </section>

  <section id="products">
    <h2>Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1583001983248-5f8e9541f9bb" alt="Jeans Pant">
        <h3>Jeans Pant</h3>
        <p>Stylish & comfy denim.</p>
        <p><b>₹2000</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20Jeans%20Pant." target="_blank" class="order-button">📦 Order Now</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1602810318383-d94a53c19a59" alt="Cargo Pant">
        <h3>Cargo Pants</h3>
        <p>Trendy cargo style.</p>
        <p><b>₹1800</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20Cargo%20Pant." target="_blank" class="order-button">📦 Order Now</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1622470954799-5b08c4a9c7a6" alt="Trousers">
        <h3>Trousers</h3>
        <p>Office-ready formal wear.</p>
        <p><b>₹2200</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20Trousers." target="_blank" class="order-button">📦 Order Now</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1617134635060-6a62ed6a5e47" alt="Casual Shirt">
        <h3>Shirt</h3>
        <p>Premium cotton shirt.</p>
        <p><b>₹1500</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20Shirt." target="_blank" class="order-button">📦 Order Now</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1618354691581-c36b6b29f3d1" alt="T-Shirt">
        <h3>T-shirt</h3>
        <p>Casual & comfy.</p>
        <p><b>₹800</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20T-shirt." target="_blank" class="order-button">📦 Order Now</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1593032465179-8a02b68e5c0f" alt="Lower">
        <h3>Sports Lower</h3>
        <p>Gym & casual.</p>
        <p><b>₹1200</b></p>
        <a href="https://wa.me/918504801771?text=Hello%20Mateen%20Enterprises%2C%20I%20want%20to%20order%20Sports%20Lower." target="_blank" class="order-button">📦 Order Now</a>
      </div>
    </div>
  </section>

  <!-- Order Form Section -->
  <section id="order">
    <h2>Order Now</h2>
    <form action="https://formspree.io/f/maypkwlg" method="POST" style="max-width:400px;margin:auto;">
      <label>Name:</label><br>
      <input type="text" name="name" required><br>

      <label>Phone:</label><br>
      <input type="text" name="phone" required><br>

      <label>Product:</label><br>
      <input type="text" name="product" required><br>

      <button type="submit">Submit Order</button>
    </form>
  </section>

  <section id="services">
    <h2>Services</h2>
    <ul>
      <li>Retail & Wholesale</li>
      <li>Reasonable Prices, Quality Clothing</li>
      <li>Custom Orders Available</li>
      <li>Delivery across Rajasthan</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><b>Phone:</b> +91-8504801771</p>
    <p><b>Address:</b> Mateen Enterprises, City Center Mall, Indra Colony, Sawai Madhopur, Rajasthan</p>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3531.951234540832!2d76.353!3d26.017!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x396db495b54a2b01%3A0xaceb0d6dab0f5a1f!2sCity%20Center%20Mall%2C%20Indra%20Colony%2C%20Sawai%20Madhopur%2C%20Rajasthan%20322001%2C%20India!5e0!3m2!1sen!2sin!4v1696040000000!5m2!1sen!2sin"
      width="100%" height="250" style="border:0; border-radius:10px; margin-top:10px;" allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <footer>
    <p>© 2025 Mateen Enterprises | Sawai Madhopur, Rajasthan</p>
  </footer>

</body>
</html>
