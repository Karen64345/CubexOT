<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CubexOT Demo</title>
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <header class="header">
        <nav>
            <div class="logo">
                <h1>CubexOT</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <h2>Welcome to CubexOT</h2>
        <p>Your one-stop platform for endless entertainment.</p>
        <button class="cta-btn" onclick="showModal()">Learn More</button>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Discover movies, series, and much more!</p>
    </section>

    <section id="services" class="services">
        <h2>Services</h2>
        <div class="card">
            <i class="fas fa-film"></i>
            <h3>Movies</h3>
        </div>
        <div class="card">
            <i class="fas fa-tv"></i>
            <h3>TV Shows</h3>
        </div>
        <div class="card">
            <i class="fas fa-music"></i>
            <h3>Music</h3>
        </div>
    </section>

    <footer id="contact" class="footer">
        <p>&copy; 2025 CubexOT. All rights reserved.</p>
    </footer>

    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal()">&times;</span>
            <h2>Welcome!</h2>
            <p>Explore a world of entertainment!</p>
        </div>
    </div>

    <script src="assets/js/script.js"></script>
</body>
</html>
