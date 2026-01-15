<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Shop</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; background-color: #f4f7f6; }
        header { background: #3f51b5; color: white; padding: 1rem 5%; display: flex; justify-content: space-between; align-items: center; }
        .hero { background: #c5cae9; height: 200px; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
        .hero button { background: #3f51b5; color: white; border: none; padding: 10px 20px; border-radius: 20px; cursor: pointer; }
        
        .container { padding: 40px 5%; }
        h2 { color: #333; }
        
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .product-card { background: white; padding: 15px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-align: center; }
        .product-card img { width: 100%; border-radius: 8px; height: 200px; object-fit: cover; }
        .product-card h3 { margin: 10px 0 5px; font-size: 1.1rem; }
        .product-card p { color: #777; font-size: 0.9rem; }
        .price { font-weight: bold; color: #333; margin: 10px 0; }
        .add-btn { color: #3f51b5; border: none; background: none; font-weight: bold; cursor: pointer; }
  body { background-color: lightblue; }
    </style>
</head>
<body>

<header>
    <h1>MODERN SHOP</h1>
    <nav>Home Products Cart (0)</nav>
</header>

<div class="hero">
    <button>Shop Now</button>
</div>

<div class="container">
    <h2>Featured Products</h2>
    <div class="product-grid">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=500" alt="Headphones">
            <h3>Wireless Headphones</h3>
            <p>Noise cancelling, 20h battery</p>
            <div class="price">Sh.2000.00</div>
            <button class="add-btn">+ Add</button>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=500" alt="Watch">
            <h3>Minimalist Watch</h3>
            <p>Stainless steel, water resistant</p>
            <div class="price">Sh.2500.00</div>
            <button class="add-btn">+ Add</button>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=500" alt="Backpack">
            <h3>Smart Backpack</h3>
            <p>Anti-theft, USB charging port</p>
            <div class="price">Sh.1000.00</div>
            <button class="add-btn">+ Add</button>
        </div>
    </div>
</div>

</body>
</html>
