<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brews & Beans</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="container">
            <h1>Brews & Beans</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="about">
        <div class="container">
            <h2>Welcome to Brews & Beans</h2>
            <p>Your cozy corner for the best coffee and craft beer in town. Enjoy our carefully curated selection in a warm and inviting atmosphere.</p>
        </div>
    </section>

    <section id="menu" class="menu">
        <div class="container">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3>Espresso</h3>
                    <p>A shot of rich, intense coffee.</p>
                </div>
                <div class="menu-item">
                    <h3>Cappuccino</h3>
                    <p>Espresso with steamed milk and foam.</p>
                </div>
                <div class="menu-item">
                    <h3>Craft Beer</h3>
                    <p>A selection of local craft beers.</p>
                </div>
                <div class="menu-item">
                    <h3>Pastries</h3>
                    <p>Freshly baked pastries to complement your drink.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="gallery">
        <div class="container">
            <h2>Gallery</h2>
            <div class="gallery-images">
                <img src="coffee.jpg" alt="Coffee">
                <img src="beer.jpg" alt="Beer">
                <img src="pastries.jpg" alt="Pastries">
                <img src="interior.jpg" alt="Cafe Interior">
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>123 Coffee Lane, Brewtown</p>
            <p>Email: info@brewsandbeans.com</p>
            <p>Phone: (123) 456-7890</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Brews & Beans. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
}

header h1 {
    margin: 0;
    font-weight: 700;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 1em;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: 400;
}

.container {
    width: 80%;
    margin: 0 auto;
    max-width: 1200px;
}

section {
    padding: 2em 0;
}

.about, .menu, .gallery, .contact {
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.menu-item {
    flex: 1 1 200px;
    margin: 1em;
    background-color: #fff;
    padding: 1em;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.menu-item h3 {
    margin-top: 0;
}

.gallery-images {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.gallery-images img {
    flex: 1 1 200px;
    margin: 1em;
    max-width: 45%;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

