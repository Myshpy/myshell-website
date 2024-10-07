# myshell-website

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myshell - Panadería Artesanal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="images/myshell_transparent.png" alt="Myshell Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#about">Nosotros</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-text">
            <h2>¡Las Mejores Donas Artesanales!</h2>
            <p>Deliciosas y frescas, horneadas con amor todos los días.</p>
            <a href="#menu" class="cta-button">Ver Menú</a>
        </div>
        <div class="hero-image">
            <img src="hero-image.jpg" alt="Donas artesanales">
        </div>
    </section>

    <section id="about">
        <h2>Sobre Nosotros</h2>
        <p>En Myshell, nuestra pasión es crear donas artesanales, mini alfajores y otras delicias que alegren tu día.</p>
    </section>

    <section id="menu">
        <h2>Menú</h2>
        <div class="menu-items">
            <div class="item">
                <img src="mini-donas.jpg" alt="Mini Donas">
                <h3>Mini Donas</h3>
                <p>Paquete de 10 unidades - ... Bs.</p>
            </div>
            <div class="item">
                <img src="donas-normales.jpg" alt="Donas Normales">
                <h3>Donas Normales</h3>
                <p>Docena -... Bs.</p>
            </div>
            <div class="item">
                <img src="minialfajores.jpg" alt="Minialfajores">
                <h3>Minialfajores</h3>
                <p>Unidad - ...Bs.</p>
            </div>
            <div class="item">
                <img src="alfajores-normales.jpg" alt="Alfajores Normales">
                <h3>Alfajores Normales</h3>
                <p>Docena - ...Bs.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contáctanos</h2>
        <p>Email: myshellespinoza2@gmal.com</p>
        <p>Teléfono: +591 65540721-62506787</p>
    </section>

    <footer>
        <p>&copy; 2024 Myshell. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #fdf2e9;
    color: #333;
}

header {
    background-color: #f78f1e;
    padding: 15px 0;
    text-align: center;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 30px;
}

header .logo img {
    height: 85px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

#hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
    background-color: #fff5e0;
}

#hero .hero-text {
    max-width: 50%;
}

#hero .cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #f78f1e;
    color: white;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 20px;
}

#hero .hero-image img {
    width: 500px;
    border-radius: 10px;
}

#about, #menu, #contact {
    padding: 50px 0;
    text-align: center;
}

#menu .menu-items {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

#menu .menu-items .item {
    background-color: white;
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    max-width: 250px;
    text-align: center;
}

#menu .menu-items .item img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 15px;
}

#contact {
    background-color: #fff5e0;
    padding: 30px 0;
}

footer {
    background-color: #f78f1e;
    color: white;
    padding: 10px;
    text-align: center;
}

