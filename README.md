<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matan Schliserman</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0073e6;
            color: white;
            padding: 1em;
            text-align: center;
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
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
            background: white;
            margin: 20px auto;
            width: 80%;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            display: flex;
            align-items: center;
        }
        .about-content {
            flex: 1;
        }
        .profile-photo {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-left: 20px;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #0073e6;
            color: white;
        }

        @media (max-width: 768px) {
            section {
                flex-direction: column;
                text-align: center;
            }
            .profile-photo {
                margin-left: 0;
                margin-top: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Matan Schliserman</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#publications">Publications</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <div class="about-content">
            <h2>About Me</h2>
            <p>PhD student in computer science focusing on optimization and generalization in machine learning.</p>
            <h2>Contact</h2>
            <p>Email: your-email@example.com</p>
        </div>
        <img src="placeholder.jpg" alt="Profile Photo" class="profile-photo">
    </section>
    
   <section id="preprints">
    <h2>Preprints</h2>
    <ul>
        <li>Preprint 1 - <a href="#">Link</a></li>
        <li>Preprint 2 - <a href="#">Link</a></li>
    </ul>
</section>

<section id="publications">
    <h2>Publications</h2>
    <ul>
        <li>Publication 1 - <a href="#">Link</a></li>
        <li>Publication 2 - <a href="#">Link</a></li>
    </ul>
</section>
    
    <footer>
        <p>&copy; 2025 Matan Schliserman</p>
    </footer>
</body>
</html>
