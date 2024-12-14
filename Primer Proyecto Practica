<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Licores</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }
        header {
            background-color: #4a2c2a;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background-image: url('hero-image.jpg'); /* Replace with a relevant image */
            background-size: cover;
            background-position: center;
            color: white;
        }
        .container {
            padding: 20px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: #fff;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
            color: #4a2c2a;
        }
        .product button {
            background-color: #4a2c2a;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #6b3d3b;
        }
        .educational {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .form-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .form-container input, .form-container textarea, .form-container button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a Licorería Exclusiva</h1>
        <p>Los mejores licores, a un clic de distancia</p>
    </header>
    <nav>
        <a href="#productos">Productos</a>
        <a href="#promociones">Promociones</a>
        <a href="#educativo">Educación</a>
        <a href="#ubicacion">Ubicación</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section class="hero">
        <h2>Ofertas Exclusivas en Vinos y Whiskys</h2>
        <p>Entrega rápida y fácil acceso. ¡Haz tu pedido hoy mismo!</p>
    </section>
    <section id="productos" class="container">
        <h2>Productos Destacados</h2>
        <div class="product-grid">
            <div class="product">
                <img src="vino.jpg" alt="Vino Tinto">
                <h3>Vino Tinto Premium</h3>
                <p>$25.00</p>
                <button>Agregar al Carrito</button>
            </div>
            <div class="product">
                <img src="whisky.jpg" alt="Whisky Escocés">
                <h3>Whisky Escocés</h3>
                <p>$40.00</p>
                <button>Agregar al Carrito</button>
            </div>
            <div class="product">
                <img src="cerveza.jpg" alt="Cerveza Artesanal">
                <h3>Cerveza Artesanal</h3>
                <p>$8.00</p>
                <button>Agregar al Carrito</button>
            </div>
        </div>
    </section>
    <section id="promociones" class="container">
        <h2>Promociones Especiales</h2>
        <p>¡Compra 2 botellas de vino y obtén un 10% de descuento!</p>
    </section>
    <section id="educativo" class="container">
        <h2>Aprende con Nosotros</h2>
        <div class="educational">
            <h3>¿Cómo elegir el vino perfecto?</h3>
            <p>Elige vinos según su maridaje: tintos para carnes, blancos para pescados y espumosos para celebraciones.</p>
        </div>
        <div class="educational">
            <h3>¿Qué es el whisky de malta?</h3>
            <p>Es un whisky elaborado únicamente con cebada malteada y destilado en un alambique de cobre. Ideal para conocedores.</p>
        </div>
    </section>
    <section id="subir-productos" class="container">
        <h2>Agregar Nuevos Productos</h2>
        <div class="form-container">
            <form>
                <label for="product-name">Nombre del Producto:</label>
                <input type="text" id="product-name" name="product-name" placeholder="Ingrese el nombre del producto" required>

                <label for="product-price">Precio:</label>
                <input type="text" id="product-price" name="product-price" placeholder="Ingrese el precio" required>

                <label for="product-image">Imagen del Producto:</label>
                <input type="file" id="product-image" name="product-image" accept="image/*" required>

                <label for="product-description">Descripción:</label>
                <textarea id="product-description" name="product-description" placeholder="Ingrese una descripción breve" rows="4" required></textarea>

                <button type="submit">Subir Producto</button>
            </form>
        </div>
    </section>
    <section id="ubicacion" class="container">
        <h2>Encuéntranos</h2>
        <p>Estamos ubicados en [Tu Dirección].</p>
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.1234567890!2d-122.0842495!3d37.4220654!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xabcdef123456789!2zQWxnb24gUG9zaXRpdm8!5e0!3m2!1ses-419!2sus!4v1609459200000!5m2!1ses-419!2sus"
            width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>
    <section id="contacto" class="container">
        <h2>Contáctanos</h2>
        <p>Teléfono: +123 456 7890</p>
        <p>Email: contacto@licoreriaejemplo.com</p>
        <button onclick="window.location.href='https://wa.me/1234567890?text=Hola,%20estoy%20interesado%20en%20sus%20productos!'">
            Contáctanos por WhatsApp
        </button>
    </section>
    <footer>
        <p>&copy; 2024 Licorería Exclusiva. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
