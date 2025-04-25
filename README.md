# clothing
fashion with cushion
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>UrbanWear - Clothing for Everyone</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #111;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.8rem;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1618354691373-d6c9cfe72863') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero button {
      background: #ff5252;
      border: none;
      padding: 15px 30px;
      font-size: 1rem;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 40px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .product {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .product h4 {
      margin: 15px;
      font-size: 1.2rem;
    }

    .product p {
      margin: 0 15px 20px;
      color: #888;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>UrbanWear</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div>
      <h2>Style That Speaks for You</h2>
      <button>Shop Now</button>
    </div>
  </section>

  <section class="section">
    <h3>Featured Products</h3>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1618354691373-d6c9cfe72863" alt="T-Shirt">
        <h4>Classic Tee</h4>
        <p>$29.99</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="Hoodie">
        <h4>Urban Hoodie</h4>
        <p>$49.99</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1542062703-3c7f0f9c47d8" alt="Jacket">
        <h4>Denim Jacket</h4>
        <p>$89.99</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 UrbanWear. All rights reserved.
  </footer>

</body>
</html>
