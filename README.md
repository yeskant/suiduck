# suiduck<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUI DUCK</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #00ff99;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: rgba(0, 0, 0, 0.7);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #00ffff;
            text-shadow: 0 0 5px #00ffff, 0 0 20px #00ffff;
        }

        nav a {
            text-decoration: none;
            color: #00ff99;
            font-size: 1.2em;
            margin: 0 15px;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #ff0066;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            color: #fff;
        }

        .hero h2 {
            font-size: 3em;
            text-shadow: 0 0 10px #ff00ff, 0 0 30px #ff00ff;
        }

        .hero p {
            font-size: 1.5em;
            margin-top: 20px;
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 50px;
        }

        .card {
            background: rgba(0, 0, 0, 0.8);
            border: 1px solid #00ff99;
            border-radius: 10px;
            box-shadow: 0 0 20px #00ff99;
            padding: 20px;
            width: 300px;
            color: #fff;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .card:hover {
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-top: 1px solid #00ff99;
        }

        footer p {
            margin: 0;
            color: #00ff99;
        }
    </style>
</head>
<body>
    <header>
        <h1>SUI DUCK</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to the Future</h2>
        <p>Explore the neon-lit world of technology and innovation.</p>
    </section>

    <section class="cards">
        <div class="card">
            <img src="duck_holograms.png" alt="Hologram Duck">
            <h3>Holograms</h3>
            <p>Experience immersive visuals with our cutting-edge holographic technology.</p>
        </div>
        <div class="card">
            <img src="duck_ai.png" alt="AI Duck">
            <h3>AI Companions</h3>
            <p>Get to know our AI-driven companions, designed to assist and entertain.</p>
        </div>
        <div class="card">
            <img src="duck_neon.png" alt="Neon Duck">
            <h3>Neon Cities</h3>
            <p>Discover urban landscapes transformed by vibrant neon lights.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 SUI DUCK. All Rights Reserved.</p>
    </footer>
</body>
</html>
