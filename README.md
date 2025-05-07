# Vuck
These website is for the per foods, pets, pet accessories
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pet Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Pet Shop</h1>
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Search for pets, food, accessories..." id="search">
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#food">Food</a></li>
            <li><a href="#pets">Pets</a></li>
            <li><a href="#accessories">Accessories</a></li>
        </ul>
    </nav>

    <main>
        <section id="food">
            <h2>Food</h2>
            <p>Explore our wide range of pet food.</p>
            <!-- Example items can be added here -->
        </section>

        <section id="pets">
            <h2>Pets</h2>
            <p>Find the perfect pet for you.</p>
            <!-- Example items can be added here -->
        </section>

        <section id="accessories">
            <h2>Accessories</h2>
            <p>Shop accessories for your pets.</p>
            <!-- Example items can be added here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Pet Shop. All rights reserved.</p>
    </footer>
</body>
</html>/* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #2E8BC0; /* Blue */
    color: #fff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

.search-bar input {
    padding: 10px;
    font-size: 1em;
    border-radius: 5px;
    border: none;
    width: 250px;
}

nav {
    background-color: #F8C8D2; /* Pink */
    text-align: center;
    padding: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #333;
    text-decoration: none;
    font-size: 1.1em;
}

main {
    padding: 20px;
    text-align: center;
}

section {
    margin-bottom: 30px;
}

footer {
    background-color: #2E8BC0;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
