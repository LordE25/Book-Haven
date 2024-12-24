<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven - Free Books for Everyone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #6200ea;
            color: white;
            padding: 30px 15%;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
        }

        .container {
            max-width: 1400px;
            margin: 30px auto;
            padding: 20px;
        }

        .section {
            margin-bottom: 50px;
        }

        .section h2 {
            font-size: 2em;
            border-bottom: 3px solid #6200ea;
            padding-bottom: 10px;
        }

        .books {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
        }

        .book {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
            width: calc(25% - 30px);
            padding: 20px;
            text-align: center;
        }

        .book img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }

        .book h3 {
            font-size: 1.5em;
            margin: 15px 0;
        }

        .book a {
            display: inline-block;
            padding: 12px 18px;
            margin-top: 15px;
            background-color: #6200ea;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1em;
        }

        .book a:hover {
            background-color: #4500b3;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }

        footer a {
            color: #6200ea;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Book Haven</h1>
        <p>Your gateway to free, beloved books</p>
        <nav>
            <a href="#featured">Featured</a>
            <a href="#categories">Categories</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="featured" class="section">
            <h2>Featured Books</h2>
            <div class="books">
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>Pride and Prejudice</h3>
                    <p>by Jane Austen</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>Moby Dick</h3>
                    <p>by Herman Melville</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>The Adventures of Sherlock Holmes</h3>
                    <p>by Arthur Conan Doyle</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="images/harry_potter_sorcerers_stone.jpg" alt=" Harry Potter and the Sorcerer's Stone Cover">
                    <h3>Harry Potter and the Sorcerer's Stone</h3>
                    <p>by J.K. Rowling</p>
                    <a href="books/harry_potter_sorcerers_stone.pdf" download>Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>To Kill a Mockingbird</h3>
                    <p>by Harper Lee</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>1984</h3>
                    <p>by George Orwell</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>The Great Gatsby</h3>
                    <p>by F. Scott Fitzgerald</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>War and Peace</h3>
                    <p>by Leo Tolstoy</p>
                    <a href="#">Download</a>
                </div>
            </div>
        </section>

        <section id="categories" class="section">
            <h2>Categories</h2>
            <p>Explore books by genre: <a href="#">Fiction</a>, <a href="#">Non-Fiction</a>, <a href="#">Sci-Fi</a>, <a href="#">Romance</a>, and more.</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Have questions or suggestions? <a href="mailto:contact@bookhaven.com">Email us</a>.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Book Haven. All rights reserved. <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
