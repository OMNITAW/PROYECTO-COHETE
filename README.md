# PROYECTO-COHETE
UN TRABAJO DE PROYECTO CHOHETE
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto Cohete</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Proyecto Cohete</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#informacion">Información</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section id="inicio">
        <h2>Bienvenidos al Proyecto Cohete</h2>
        <p>Un emocionante proyecto académico sobre cohetes de agua y más.</p>
    </section>
    <section id="informacion">
        <h2>Información</h2>
        <p>Descripción del proyecto y objetivos principales.</p>
    </section>
    <section id="galeria">
        <h2>Galería</h2>
        <div class="imagenes">
            <img src="imagen1.jpg" alt="Imagen 1">
            <img src="imagen2.jpg" alt="Imagen 2">
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <form action="#">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre">
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email">
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Proyecto Cohete. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px auto;
    max-width: 800px;
    text-align: center;
}

.imagenes img {
    width: 45%;
    margin: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
