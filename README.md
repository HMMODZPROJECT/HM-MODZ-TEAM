<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Toko File Digital - HM MODZ</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 2rem;
    }

    .product-card {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }

    .product-card img {
      width: 100%;
      max-height: 150px;
      object-fit: contain;
      margin-bottom: 1rem;
    }

    .product-card h3 {
      margin: 0.5rem 0;
    }

    .price {
      color: #27ae60;
      font-weight: bold;
    }

    .buy-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #3498db;
      color: #fff;
      border: none;
      border-radius: 5px;
      text-decoration: none;
    }

    .buy-button:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>

  <header>
    <h1>HM MODZ Store</h1>
    <p>Jualan File Digital - Script, Mod, Template</p>
  </header>

  <div class="container">
    <div class="product-card">
      <img src="https://via.placeholder.com/150" alt="Produk 1">
      <h3>Script Auto Headshot</h3>
      <p class="price>Rp 25.000</p>
      <a href="https://wa.me/6285137060301" class="buy-button">Beli via WhatsApp</a>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/150" alt="Produk 2">
      <h3>ESP + Wallhack</h3>
      <p class="price">Rp 30.000</p>
      <a href="https://wa.me/628XXXXXXX" class="buy-button">Beli Sekarang</a>
    </div>

    <!-- Tambahkan produk lainnya di sini -->
  </div>

</body>
</html>
