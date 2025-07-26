# Sugum-fugum
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FUGUM & SUGUM - THC-Infused Gums & Lollies</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fefaf6;
      margin: 0;
      padding: 0;
      color: #222;
    }
    header {
      background: #ff5e5e;
      color: white;
      padding: 2em;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
      margin-top: 0.5em;
    }
    nav {
      background: #fff;
      padding: 1em;
      text-align: center;
      border-bottom: 1px solid #eee;
    }
    nav a {
      margin: 0 1em;
      text-decoration: none;
      color: #222;
      font-weight: bold;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 3em 1em;
    }
    .hero img {
      max-width: 300px;
      margin-bottom: 1em;
    }
    .hero h2 {
      font-size: 2em;
      margin: 0.5em 0;
    }
    .hero p {
      max-width: 600px;
      text-align: center;
      font-size: 1.1em;
      margin-bottom: 1em;
    }
    .buy-btn {
      padding: 0.75em 2em;
      background-color: #222;
      color: #fff;
      border: none;
      font-size: 1em;
      border-radius: 6px;
      cursor: pointer;
    }
    .flavors {
      background: #fff;
      padding: 3em 1em;
      text-align: center;
    }
    .flavors h3 {
      font-size: 1.8em;
    }
    .product-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2em;
      margin-top: 2em;
    }
    .product {
      background: #f2f2f2;
      padding: 1em;
      border-radius: 8px;
      width: 160px;
    }
    .product img {
      max-width: 100%;
      border-radius: 6px;
    }
    .product h4 {
      margin: 0.5em 0 0.2em;
    }
    .locations {
      background: #fef0e3;
      padding: 3em 1em;
      text-align: center;
    }
    .locations h3 {
      font-size: 1.8em;
      margin-bottom: 0.5em;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 2em 1em;
    }
  </style>
</head>
<body>

  <header>
    <h1>FUGUM & SUGUM™</h1>
    <p>THC-Infused Gum & Lollipops for the Modern Explorer</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#flavors">Flavors</a>
    <a href="#locations">Locations</a>
    <a href="#buy">Buy</a>
  </nav>

  <section class="hero" id="products">
    <img src="https://example.com/lion-lollipop.png" alt="Lion Lollipop">
    <h2>Chew Bold. Suck Smart.</h2>
    <p>From Seattle to Medellín, FUGUM & SUGUM are reshaping cannabis one gummy bite at a time. Microdosed. Delicious. Discreet. Legal.</p>
    <button class="buy-btn" onclick="window.location.href='#buy'">Buy Now</button>
  </section>

  <section class="flavors" id="flavors">
    <h3>Your Mood. Your Animal. Your High.</h3>
    <div class="product-grid">
      <div class="product">
        <img src="https://example.com/elephant.png" alt="Elephant Lollipop">
        <h4>Elephant</h4>
        <p>Watermelon<br>$2</p>
      </div>
      <div class="product">
        <img src="https://example.com/lion.png" alt="Lion Lollipop">ok
        <h4>Lion</h4>
        <p>Mango<br>$2</p>
      </div>
      <div class="product">
        <img src="https://example.com/penguin.png" alt="Penguin Lollipop">
        <h4>Penguin</h4>
        <p>Seattle Coffee<br>$3</p>
      </div>
      <div class="product">
        <img src="https://example.com/fugum-pack.png" alt="FUGUM Gum">
        <h4>FUGUM</h4>
        <p>THC Gum<br>Watermelon</p>
      </div>
      <div class="product">
        <img src="https://example.com/sugum-pack.png" alt="SUGUM Gum">
        <h4>SUGUM</h4>
        <p>Medellín Mango<br>$2</p>
      </div>
    </div>
  </section>

  <section class="locations" id="locations">
    <h3>Three Cities. One Mission.</h3>
    <p><strong>Seattle:</strong> High-tech terpene extraction & fast-acting formulas.</p>
    <p><strong>Tampa:</strong> Tropically inspired medical-grade cannabis candy.</p>
    <p><strong>Medellín:</strong> Organic THC roots + fruit-forward flavors.</p>
  </section>

  <footer id="buy">
    <p>© 2025 The Gum Family™. All rights reserved.<br>
    Based in Seattle • Tampa • Medellín<br>
    THC products available to adults 21+ where legal. Medically licensed where required.</p>
  </footer>

</body>
</html>
