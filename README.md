## Hi there 👋
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FarmConnect Ghana</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">FarmConnect Ghana</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#farmers">Farmers</a></li>
                <li><a href="#buyers">Buyers</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#login">Login</a></li>
            </ul>
        </nav>
    </header>
    <section id="hero">
        <h1>Connecting Farmers with Buyers Across Ghana</h1>
        <p>Join our platform to buy and sell fresh produce directly from local farmers.</p>
        <button>Join as a Farmer</button>
        <button>Find Fresh Produce</button>
    </section>
    <section id="search">
        <input type="text" placeholder="Search for products or farmers...">
    </section>
    <section id="featured-products">
        <h2>Featured Products</h2>
        <!-- Product listings will go here -->
    </section>
    <section id="how-it-works">
        <h2>How It Works</h2>
        <p>Learn how our platform connects farmers with buyers.</p>
    </section>
    <section id="testimonials">
        <h2>Testimonials</h2>
        <!-- Testimonials will go here -->
    </section>
    <footer>
        <p>Contact us: info@farmconnectghana.com</p>
        <p>Follow us on social media:</p>
        <!-- Social media links will go here -->
    </footer>
</body>
</html>

<!--
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    display: flex;
    justify-content: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

#hero {
    background-image: url('hero-image.jpg');
    background-size: cover;
    text-align: center;
    padding: 100px 0;
    color: white;
}

#hero h1 {
    font-size: 2.5em;
}

#hero p {
    font-size: 1.2em;
}

#search {
    text-align: center;
    padding: 20px;
}

#search input {
    width: 80%;
    padding: 10px;
    font-size: 1em;
}

#featured-products, #how-it-works, #testimonials {
    padding: 50px 20px;
    text-align: center;
}

#featured-products h2, #how-it-works h2, #testimonials h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer p {
    margin: 5px 0;
}
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = htmlspecialchars($_POST['name']);
    $email = htmlspecialchars($_POST['email']);
    $message = htmlspecialchars($_POST['message']);

    $to = "info@farmconnectghana.com";
    $subject = "New Contact Form Submission";
    $body = "Name: $name\nEmail: $email\n\nMessage:\n$message";

    if (mail($to, $subject, $body)) {
        echo "Thank you for your message!";
    } else {
        echo "Sorry, something went wrong. Please try again.";
    }
}
?>

**Farmershulb/Farmershulb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
