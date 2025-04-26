delux
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LUXE Clothing Boutique</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #f9f7f4;
      color: #333;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background-color: #fff;
      position: sticky;
      top: 0;
      z-index: 1000;
      animation: fadeIn 1s ease-in;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #7d9775;
    }
    .hero {
      display: flex;
      align-items: center;
      padding: 50px;
      animation: fadeIn 1s ease-in;
    }
    .hero img {
      max-width: 50%;
      border-radius: 20px;
      animation: fadeSlide 1s ease-out;
    }
    .hero-text {
      margin-left: 50px;
      max-width: 40%;
    }
    .hero-text h1 {
      font-family: 'Georgia', serif;
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero-text p {
      font-size: 18px;
      margin-bottom: 20px;
    }
    .sizes button {
      padding: 10px 15px;
      margin-right: 10px;
      border: 1px solid #ccc;
      background: #fff;
      cursor: pointer;
      transition: background-color 0.3s, border-color 0.3s;
    }
    .sizes button:hover, .sizes button.active {
      background-color: #7d9775;
      border-color: #7d9775;
      color: #fff;
    }
    .add-to-cart {
      margin-top: 20px;
      padding: 15px 30px;
      background-color: #7d9775;
      border: none;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: transform 0.3s;
      border-radius: 5px;
    }
    .add-to-cart:hover {
      transform: scale(1.05);
    }
    .collections {
      padding: 50px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      animation: fadeSlide 1.5s ease-out;
    }
    .collections img {
      width: 100%;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .collections img:hover {
      transform: scale(1.05);
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes fadeSlide {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <div><strong>LUXE</strong></div>
  <nav>
    <a href="#shop">Shop</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <img src="https://via.placeholder.com/500x600" alt="Sustainable Trench Coat">
  <div class="hero-text">
    <h1>Sustainable Trench Coat</h1>
    <p>$350</p>
    <p>A timeless trench coat crafted from eco-friendly materials. Combining streetwear with luxury, it offers a stylish and sustainable choice for the modern wardrobe.</p>
    <div class="sizes">
      <button>S</button>
      <button>M</button>
      <button>L</button>
    </div>
    <button class="add-to-cart">ADD TO CART</button>
  </div>
</section>

<section id="shop" class="collections">
  <img src="https://via.placeholder.com/300x400" alt="Streetwear Hoodie">
  <img src="https://via.placeholder.com/300x400" alt="Luxury Coat">
  <img src="https://via.placeholder.com/300x400" alt="Organic Cotton Dress">
  <img src="https://via.placeholder.com/300x400" alt="Linen Trousers">
</section>

</body>
</html>
