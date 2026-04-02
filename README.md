# cafe.website
a simple cafe website built using HTML and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafe Delight</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f8f5f2;
        }
        header {
            background-color: #6b3e26;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background: #3e2723;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') no-repeat center;
            background-size: cover;
            height: 300px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2em;
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .menu-item {
            background: white;
            margin: 10px;
            padding: 15px;
            border-radius: 10px;
            width: 200px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background: #3e2723;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Cafe Delight</h1>
    <p>Fresh Coffee & Delicious Food</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    Welcome to Our Cafe ☕
</div>

<section id="menu" class="section">
    <h2>Our Menu</h2>
    <div class="menu">
        <div class="menu-item">
            <h3>Espresso</h3>
            <p>$2.50</p>
        </div>
        <div class="menu-item">
            <h3>Latte</h3>
            <p>$3.50</p>
        </div>
        <div class="menu-item">
            <h3>Burger</h3>
            <p>$5.00</p>
        </div>
        <div class="menu-item">
            <h3>Pasta</h3>
            <p>$6.50</p>
        </div>
    </div>
</section>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>We serve fresh coffee and tasty meals in a cozy environment.</p>
</section>

<section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: info@cafedelight.com</p>
    <p>Phone: +123 456 789</p>
</section>

<footer>
    <p>© 2026 Cafe Delight</p>
</footer>

</body>
</html>
