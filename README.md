<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            margin: 10px;
            width: 200px;
            text-align: center;
        }
        .product-item img {
            max-width: 100%;
            border-bottom: 1px solid #ddd;
            margin-bottom: 10px;
        }
        .contact {
            margin-top: 20px;
            text-align: center;
        }
        .contact a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Tienda de Ropa</h1>
    </div>
    <div class="container">
        <h2>Nuestros Productos</h2>
        <div class="product">
            <div class="product-item">
                <img src="camiseta.jpg" alt="Camiseta">
                <h3>Camiseta</h3>
                <p>$20.00</p>
            </div>
            <div class="product-item">
                <img src="pantalon.jpg" alt="Pantalón">
                <h3>Pantalón</h3>
                <p>$30.00</p>
            </div>
            <div class="product-item">
                <img src="vestido.jpg" alt="Vestido">
                <h3>Vestido</h3>
                <p>$40.00</p>
            </div>
        </div>
        <div class="contact">
            <p>Para más información, contáctanos a nuestro WhatsApp:</p>
            <a href="https://wa.me/573113760409" target="_blank">311 376 0409</a>
        </div>
    </div>
</body>
</html>
