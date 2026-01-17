<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karah Sarkar Colony - Housing Society</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Roboto', sans-serif; background: linear-gradient(135deg, #e3f2fd, #f3e5f5); color: #333; }
        .hero { background: linear-gradient(135deg, rgba(0,123,255,0.8), rgba(0,255,123,0.8)), url('hero1.jpg'); /* Replace with your image */ background-size: cover; height: 60vh; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.7); animation: fadeIn 2s; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        .navbar { background: linear-gradient(90deg, #2c3e50, #3498db); box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .card { border: none; box-shadow: 0 8px 16px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .card:hover { transform: translateY(-5px); }
        .btn-custom { background: linear-gradient(45deg, #3498db, #2ecc71); border: none; color: white; }
        .btn-custom:hover { background: linear-gradient(45deg, #2980b9, #27ae60); }
        footer { background: #2c3e50; color: white; padding: 20px 0; }
        .social-icons a { color: white; margin: 0 10px; font-size: 1.5rem; transition: color 0.3s; }
        .social-icons a:hover { color: #3498db; }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#"><i class="fas fa-home"></i> Karah Sarkar Colony</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#residents">Residents</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section with Carousel -->
    <section id="home" class="hero">
        <div class="container text-center">
            <h1 class="display-4">Welcome to Karah Sarkar Colony</h1>
            <p class="lead">A serene haven for families, fostering community and harmony.</p>
            <a href="#about" class="btn btn-custom btn-lg">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h2 class="mb-4"><i class="fas fa-info-circle"></i> About Our Society</h2>
                    <p>Established in [Year], Karah Sarkar Colony boasts [number] homes with top-notch amenities like lush parks, 24/7 security, clean water supply, and recreational areas. We're committed to sustainable living and community events.</p>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-check text-success"></i> Secure gated community</li>
                        <li><i class="fas fa-check text-success"></i> Eco-friendly initiatives</li>
                        <li><i class="fas fa-check text-success"></i> Regular maintenance</li>
                    </ul>
                </div>
                <div class="col-md-6">
                    <img src="colony.jpg" alt="Colony View" class="img-fluid rounded shadow" style="animation: fadeIn 3s;"> <!-- Replace with your image -->
                </div>
            </div>
        </div>
    </section>

    <!-- Residents Section -->
    <section id="residents" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5"><i class="fas fa-users"></i> Residents & Community</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card text-center">
                        <div class="card-body">
                            <i class="fas fa-calendar-alt fa-3x text-primary mb-3"></i>
                            <h5 class="card-title">Upcoming Events</h5>
                            <p class="card-text">Annual Meeting: [Date]. Diwali Celebration: [Date]. Join us!</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card text-center">
                        <div class="card-body">
                            <i class="fas fa-book fa-3x text-success mb-3"></i>
                            <h5 class="card-title">Resident Directory</h5>
                            <p class="card-text">Access our directory for easy connections. <a href="#">Download PDF</a></p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card text-center">
                        <div class="card-body">
                            <i class="fas fa-gavel fa-3x text-warning mb-3"></i>
                            <h5 class="card-title">Community Rules</h5>
                            <p class="card-text">Guidelines for a peaceful living. <a href="#">View Rules</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5"><i class="fas fa-envelope"></i> Get in Touch</h2>
            <div class="row">
                <div class="col-md-6">
                    <h5>Contact Info</h5>
                    <p><i class="fas fa-map-marker-alt"></i> [Full Address, e.g., Karah Sarkar Colony, City, State, PIN]</p>
                    <p><i class="fas fa-phone"></i> [Phone Number]</p>
                    <p><i class="fas fa-envelope"></i> [Email Address]</p>
                </div>
                <div class="col-md-6">
                    <form action="#" method="post"> <!-- Integrate with a service like Formspree for real submissions -->
                        <div class="mb-3">
                            <input type="text" class="form-control" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" name="message" rows="4" placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-custom">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container text-center">
            <p>&copy; 2023 Karah Sarkar Colony. All rights reserved.</p>
            <div class="social-icons">
                <a href="#" title="Facebook"><i class="fab fa-facebook"></i></a>
                <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
                <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
