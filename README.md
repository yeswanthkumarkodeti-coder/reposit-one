<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Big HTML Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0; padding: 0;
            background-color: #f5f5f5;
        }
        header, footer {
            background-color: #333;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background: #fff;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        form {
            background: #fff;
            padding: 20px;
            border: 1px solid #ccc;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 8px;
            margin-bottom: 16px;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Big HTML Web Page</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <section id="about">
            <h2>About Us</h2>
            <p>This is a full-featured HTML page demonstrating common elements used in web design.</p>
            <img src="https://via.placeholder.com/600x200" alt="Placeholder image">
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Web Development</li>
                <li>SEO Optimization</li>
                <li>UI/UX Design</li>
            </ul>
            <h3>Pricing Table</h3>
            <table>
                <tr>
                    <th>Service</th>
                    <th>Price</th>
                </tr>
                <tr>
                    <td>Basic Website</td>
                    <td>$500</td>
                </tr>
                <tr>
                    <td>Advanced SEO</td>
                    <td>$300</td>
                </tr>
            </table>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form action="/submit" method="post">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name">

                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email">

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5"></textarea>

                <input type="submit" value="Send Message">
            </form>
        </section>

    </main>

    <footer>
        <p>&copy; 2025 My Company. All rights reserved.</p>
        <p>Follow us on 
            <a href="#" style="color: #ccc;">Twitter</a> | 
            <a href="#" style="color: #ccc;">Facebook</a>
        </p>
    </footer>

    <script>
        // Example JavaScript
        document.querySelector("form").addEventListener("submit", function(e) {
            alert("Thank you for your message!");
            e.preventDefault(); // Prevent actual form submission
        });
    </script>
</body>
</html>
