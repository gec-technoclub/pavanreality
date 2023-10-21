# temp.github.io
<!DOCTYPE html>
<html>
<head>
    <title>Sample Website</title>
    <style>
        /* CSS styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #444;
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
            margin-right: 20px;
        }
        #content {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sample Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div id="content">
        <h2>Welcome to Our Website</h2>
        <p>This is a sample website created using HTML, CSS, and JavaScript.</p>
        <button id="changeText">Change Content</button>
    </div>
    <footer>
        &copy; 2023 Sample Website
    </footer>
    <script>
        // JavaScript function to change content when the button is clicked
        document.getElementById("changeText").addEventListener("click", function() {
            var content = document.getElementById("content");
            content.innerHTML = "<h2>New Content</h2><p>This content was changed using JavaScript.</p>";
        });
    </script>
</body>
</html>
