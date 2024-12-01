<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our School</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#join">Join Us</a></li>
        </ul>
    </nav>
    <main>
        <section id="courses">
            <h2>Courses Offered</h2>
            <ul>
                <li>Mathematics</li>
                <li>Science</li>
                <li>History</li>
                <li>Art and Design</li>
                <li>Computer Science</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Details</h2>
            <p>Email: info@school.com</p>
            <p>Phone: +123 456 7890</p>
            <p>Address: 123 Education St, Learning City</p>
        </section>
        <section id="join">
            <h2>Join Our School</h2>
            <form id="joinForm">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
                <button type="submit">Submit</button>
            </form>
            <p id="response"></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Our School. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav {
    background: #444;
    color: #fff;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

form label {
    display: block;
    margin: 10px 0 5px;
}

form input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background: #333;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 4px;
}

button:hover {
    background: #555;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
