<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ELITE PIP TRADERS FOREX SIGNALS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ELITE PIP TRADERS FOREX SIGNALS</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#signals">Signals</a></li>
                <li><a href="#subscription">Subscription</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to ELITE PIP TRADERS FOREX SIGNALS</h2>
        <p>Get accurate and timely Forex signals to maximize your trading profits.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We provide expert Forex signals to help traders make informed decisions. Our team consists of experienced traders with a proven track record.</p>
    </section>

    <section id="signals">
        <h2>Latest Forex Signals</h2>
        <div id="signal-list"></div>
    </section>

    <section id="subscription">
        <h2>Subscription Plans</h2>
        <div class="plan">
            <h3>Basic Plan</h3>
            <p>Receive 5 signals per week.</p>
            <button>Subscribe</button>
        </div>
        <div class="plan">
            <h3>Pro Plan</h3>
            <p>Receive 20 signals per week.</p>
            <button>Subscribe</button>
        </div>
        <div class="plan">
            <h3>Premium Plan</h3>
            <p>Unlimited signals.</p>
            <button>Subscribe</button>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 ELITE PIP TRADERS FOREX SIGNALS. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2rem;
    border-bottom: 1px solid #ddd;
}

section h2 {
    margin-top: 0;
}

#signals {
    background-color: #f9f9f9;
    padding: 2rem;
}

.plan {
    border: 1px solid #ddd;
    padding: 1rem;
    margin: 1rem 0;
}

.plan h3 {
    margin-top: 0;
}

.plan button {
    padding: 10px;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 10px;
}

form input, form textarea {
    margin-top: 5px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    margin-top: 10px;
    padding: 10px;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}
