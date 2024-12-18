<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Bienvenido a Nike
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Potencia tu estilo con Nike</h1>
        <p>Explora la última colección y encuentra lo mejor para ti.</p>
    </header>
    <nav>
        <ul>
            <li><a href="#productos">Productos</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    <section id="productos">
        <h2>Productos destacados</h2>
        <div class="productos">
            <div class="producto">
                <img src="zapatillas.jpg" alt="Zapatillas Nike">
                <h3>Zapatillas deportivas</h3>
                <p>Comodidad y estilo para tu día a día.</p>
            </div>
            <div class="producto">
                <img src="camiseta.jpg" alt="Camiseta Nike">
                <h3>Camiseta deportiva</h3>
                <p>Ligera y transpirable, ideal para entrenar.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>© 2024 Nike. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
 nike-productos
/* Estilo básico del sitio */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Encabezado */
header {
    background: #000;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
}

/* Navegación */
nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background: #333;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
    display: block;
}

/* Productos */
#productos {
    padding: 20px;
    text-align: center;
}

.productos {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.producto {
    background: #fff;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: 200px;
}

.producto img {
    width: 100%;
    border-radius: 5px;
}

.producto h3 {
    margin-top: 10px;
    font-size: 1.2rem;
}

/* Pie de página */
footer {
    text-align: center;
    background: #000;
    color: #fff;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
