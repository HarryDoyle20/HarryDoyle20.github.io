<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Dealership</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to BMC Car Dealership</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#inventory">Inventory</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Find Your Dream Car Today!</h2>
        <p>Explore our wide range of vehicles at unbeatable prices.</p>
    </section>

    <section id="inventory">
        <h2>Our Inventory</h2>
        <div class="car-list">
            <div class="car">
                <img src="assets/car1.jpg" alt="Car 1">
                <h3>2023 Sedan</h3>
                <p>$25,000</p>
            </div>
            <div class="car">
                <img src="assets/car2.jpg" alt="Car 2">
                <h3>2023 SUV</h3>
                <p>$35,000</p>
            </div>
            <div class="car">
                <img src="assets/car3.jpg" alt="Car 3">
                <h3>2023 Truck</h3>
                <p>$40,000</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>XYZ Car Dealership has been serving the community for over 20 years, providing quality vehicles at affordable prices.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 XYZ Car Dealership. All Rights Reserved.</p>
    </footer>
</body>
</html>

