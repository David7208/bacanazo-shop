<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bacanazo Shop</title>
    <style>
        /* Estilo global */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }
        header {
            background-color: #ff6363;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #ff4747;
            padding: 10px;
            font-weight: bold;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 16px;
        }
        .container {
            padding: 20px;
        }
        h2 {
            color: #ff4747;
            text-align: center;
            margin-bottom: 20px;
        }
        .categories, .promotions, .best-sellers {
            margin-bottom: 40px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .item {
            background-color: white;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s;
        }
        .item:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #ff4747;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bacanazo Shop</h1>
        <p>¡Tu tienda online favorita, ahora con más estilo y mejores precios!</p>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Categorías</a>
        <a href="#">Promociones</a>
        <a href="#">Lo Más Vendido</a>
        <a href="#">Contacto</a>
    </nav>

    <div class="container">
        <section class="categories">
            <h2>Categorías</h2>
            <div class="grid">
                <div class="item">Ropa</div>
                <div class="item">Tecnología</div>
                <div class="item">Hogar</div>
                <div class="item">Accesorios</div>
            </div>
        </section>

        <section class="promotions">
            <h2>Promociones</h2>
            <div class="grid">
                <div class="item">Descuento 50%</div>
                <div class="item">Compre 2 y Lleve 3</div>
                <div class="item">Ofertas Relámpago</div>
                <div class="item">Cupones Especiales</div>
            </div>
        </section>

        <section class="best-sellers">
            <h2>Lo Más Vendido</h2>
            <div class="grid">
                <div class="item">Producto 1</div>
                <div class="item">Producto 2</div>
                <div class="item">Producto 3</div>
                <div class="item">Producto 4</div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Bacanazo Shop. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
