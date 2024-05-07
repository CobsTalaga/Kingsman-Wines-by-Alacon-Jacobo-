<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kingsman Wines</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8; 
    color: #333; 
}

.container {
    width: 90%;
    margin: 0 auto;
    max-width: 1200px;
}

header {
    background-color: #000;
    padding: 20px 0;
    color: #ffd700; 
}

.logo img {
    height: 50px;
}

.nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.nav ul li {
    display: inline;
    margin-right: 20px;
}

.nav ul li a {
    text-decoration: none;
    color: #ffd700;
    font-weight: bold;
}

.nav ul li a:hover {
    color: #fff;
}

.main-content {
    padding: 20px 0;
}

.wine-category {
    margin-bottom: 40px;
}

.wine-category h2 {
    color: #333;
    font-size: 28px; 
    margin-bottom: 20px;
}

.wine-item img {
    width: 100%;
    max-width: 300px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.wine-description {
    color: #666;
    font-size: 16px;
}

.contact-section {
    background-color: #ffd700;
    color: #333;
    padding: 50px 0;
}

.contact-form {
    max-width: 500px;
    margin: 0 auto;
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.contact-form h2 {
    color: #333;
    text-align: center;
    margin-bottom: 20px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-form button {
    width: 100%;
    padding: 10px;
    background-color: #000; 
    color: #ffd700;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s ease;
}

.contact-form button:hover {
    background-color: #333;
}

footer {
    background-color: #000;
    color: #ffd700;
    padding: 20px 0;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.social-links a {
    color: #ffd700;
    margin-right: 10px;
}

.social-links a:hover {
    color: #fff;
}

</style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <img src="logo.png" alt="Kingsman Logo">
            </div>
            <nav class="nav">
                <ul>
                    <li><a href="#red-wine">Red Wine</a></li>
                    <li><a href="#sparkling-wine">Sparkling Wine</a></li>
                    <li><a href="#rose-wine">Rosé Wine</a></li>
                    <li><a href="#moscato">Moscato</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="main-content">
        <div class="container">
            <div class="wine-products">
                <div class="wine-category">
                    <h2>Kingsman Reserve Rouge</h2>
                    <div class="wine-item">
                        <img src="kingsman-reserve-rouge.jpg" alt="Kingsman Reserve Rouge">
                        <p class="wine-description">699.00</p>
                    </div>
                </div>
                <div class="wine-category">
                    <h2>Kingsman Brilliance</h2>
                    <div class="wine-item">
                        <img src="kingsman-brilliance.jpg" alt="Kingsman Brilliance">
                        <p class="wine-description">399.00</p>
                    </div>
                </div>
                <div class="wine-category">
                    <h2>Kingsman Blush Royale</h2>
                    <div class="wine-item">
                        <img src="kingsman-blush-royale.jpg" alt="Kingsman Blush Royale">
                        <p class="wine-description">599.00</p>
                    </div>
                </div>
                <div class="wine-category">
                    <h2>Kingsman Moscato Majesty</h2>
                    <div class="wine-item">
                        <img src="kingsman-moscato-majesty.jpg" alt="Kingsman Moscato Majesty">
                        <p class="wine-description">650.00</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="contact-section">
        <div class="container">
            <div class="contact-form">
                <h2>Contact Us</h2>
                <form action="submit.php" method="post">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="message" placeholder="Your Message" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
                </div>
                </div>
                </section>
            </body>
            </html>
