<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zbros - Online Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #28a745;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #28a745;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h1, h2 {
            color: #28a745;
        }
        .product-category {
            margin-bottom: 30px;
        }
        .product-category h2 {
            margin-bottom: 10px;
        }
        .product-category p {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Zbros Online Store</h1>
    </header>
    <nav>
        <a href="#clothes">Clothes</a>
        <a href="#kitchen">Kitchen</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="clothes">
        <h2>Clothes</h2>
        <div class="product-category">
            <h3>Men's Clothing</h3>
            <p>Explore our range of stylish and comfortable men's clothing.</p>
        </div>
        <div class="product-category">
            <h3>Women's Clothing</h3>
            <p>Discover the latest trends in women's fashion.</p>
        </div>
    </div>
    <div class="container" id="kitchen">
        <h2>Kitchen</h2>
        <div class="product-category">
            <h3>Cookware</h3>
            <p>Find high-quality cookware to make your kitchen complete.</p>
        </div>
        <div class="product-category">
            <h3>Utensils</h3>
            <p>Browse our selection of essential kitchen utensils.</p>
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, please email us at <a href="mailto:support@zbros.com">support@zbros.com</a>.</p>
    </div>
    <footer>
        <p>&copy; 2024 Zbros. All rights reserved.</p>
    </footer>
</body>
</html>
