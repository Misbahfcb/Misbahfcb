<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nesmal Personal Trainer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Nesmal Personal Trainer</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="intro">
            <h2>Welcome to Nesmal Personal Training</h2>
            <p>Transform your life with personalized fitness plans and professional guidance.</p>
        </section>
        <section class="services-overview">
            <h2>Our Services</h2>
            <p>Explore our range of services designed to help you achieve your fitness goals.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Nesmal Personal Trainer. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Nesmal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Nesmal</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="bio">
            <h2>Meet Nesmal</h2>
            <p>Nesmal is a certified personal trainer with over 10 years of experience in helping clients achieve their fitness goals...</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Nesmal Personal Trainer. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="contact-form">
            <h2>Get in Touch</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Nesmal Personal Trainer. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 2rem;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}

.intro, .services-overview, .bio, .services-list, .contact-form {
    margin-bottom: 2rem;
}

.contact-form form {
    display: flex;
    flex-direction: column;
}

.contact-form label {
    margin-bottom: 0.5rem;
}

.contact-form input, .contact-form textarea {
    margin-bottom: 1rem;
    padding: 0.5rem;
    font-size: 1rem;
}

.contact-form button {
    padding: 0.5rem;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}
