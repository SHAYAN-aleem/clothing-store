<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FashionHub - Trendy Clothing Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>Fashion<span>Hub</span></h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html" class="active">Home</a></li>
                    <li><a href="products.html">Shop</a></li>
                    <li><a href="#">New Arrivals</a></li>
                    <li><a href="#">Sale</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
            <div class="icons">
                <a href="#" id="search-btn"><i class="fas fa-search"></i></a>
                <a href="#" id="user-btn"><i class="fas fa-user"></i></a>
                <a href="cart.html" id="cart-btn"><i class="fas fa-shopping-cart"></i><span class="cart-count">0</span></a>
                <a href="#" id="menu-btn"><i class="fas fa-bars"></i></a>
            </div>
            <div class="search-form">
                <input type="search" placeholder="Search products...">
                <label for="search-box" class="fas fa-search"></label>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h2>Summer Collection 2023</h2>
                <p>Discover our latest trends and styles</p>
                <a href="products.html" class="btn">Shop Now</a>
            </div>
        </div>
    </section>

    <!-- Categories -->
    <section class="categories">
        <div class="container">
            <h2 class="section-title">Shop by Category</h2>
            <div class="category-grid">
                <div class="category-card">
                    <img src="https://images.unsplash.com/photo-1551232864-3f0890e580d9?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Men's Clothing">
                    <div class="category-info">
                        <h3>Men's</h3>
                        <a href="products.html?category=men" class="btn">View All</a>
                    </div>
                </div>
                <div class="category-card">
                    <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Women's Clothing">
                    <div class="category-info">
                        <h3>Women's</h3>
                        <a href="products.html?category=women" class="btn">View All</a>
                    </div>
                </div>
                <div class="category-card">
                    <img src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Kids Clothing">
                    <div class="category-info">
                        <h3>Kids</h3>
                        <a href="products.html?category=kids" class="btn">View All</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Products -->
    <section class="featured-products">
        <div class="container">
            <h2 class="section-title">Featured Products</h2>
            <div class="product-grid" id="featured-products">
                <!-- Products will be loaded via JavaScript -->
            </div>
            <div class="view-all">
                <a href="products.html" class="btn">View All Products</a>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="newsletter">
        <div class="container">
            <div class="newsletter-content">
                <h3>Subscribe to Our Newsletter</h3>
                <p>Get 10% off your first order and updates on new arrivals</p>
                <form>
                    <input type="email" placeholder="Enter your email">
                    <button type="submit" class="btn">Subscribe</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>FashionHub</h3>
                    <p>Your one-stop shop for trendy and affordable clothing.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-pinterest"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="products.html">Shop</a></li>
                        <li><a href="#">New Arrivals</a></li>
                        <li><a href="#">Sale</a></li>
                        <li><a href="#">About Us</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Customer Service</h3>
                    <ul>
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">FAQs</a></li>
                        <li><a href="#">Shipping Policy</a></li>
                        <li><a href="#">Returns & Exchanges</a></li>
                        <li><a href="#">Size Guide</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Contact Info</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> 123 Fashion St, Trendy City</li>
                        <li><i class="fas fa-phone"></i> +1 (555) 123-4567</li>
                        <li><i class="fas fa-envelope"></i> info@fashionhub.com</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 FashionHub. All Rights Reserved.</p>
                <div class="payment-methods">
                    <i class="fab fa-cc-visa"></i>
                    <i class="fab fa-cc-mastercard"></i>
                    <i class="fab fa-cc-paypal"></i>
                    <i class="fab fa-cc-amex"></i>
                </div>
            </div>
        </div>
    </footer>

    <!-- Login Form -->
    <div class="login-form-container">
        <form>
            <h3>Login</h3>
            <input type="email" placeholder="Email" class="box">
            <input type="password" placeholder="Password" class="box">
            <div class="remember">
                <input type="checkbox" id="remember-me">
                <label for="remember-me">Remember me</label>
            </div>
            <button type="submit" class="btn">Login</button>
            <p>Don't have an account? <a href="#">Register here</a></p>
            <i class="fas fa-times close-login"></i>
        </form>
    </div>

    <script src="js/products.js"></script>
    <script src="js/main.js"></script>
</body>
</html>
