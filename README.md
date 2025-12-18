<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookHaven</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background:#f5f5f5;
        }

        /* NAVBAR */
        nav{
            width:100%;
            background:#fff;
            padding:15px 50px;
            display:flex;
            align-items:center;
            justify-content:space-between;
            box-shadow:0 2px 5px rgba(0,0,0,0.1);
            position:sticky;
            top:0;
            z-index:10;
        }

        .logo{
            font-size:24px;
            font-weight:bold;
            display:flex;
            align-items:center;
            gap:8px;
        }

        .nav-links{
            display:flex;
            gap:30px;
        }

        .nav-links a{
            text-decoration:none;
            color:#333;
            font-size:16px;
        }

        .nav-right{
            display:flex;
            align-items:center;
            gap:20px;
        }

        .login-btn{
            padding:8px 18px;
            background:#111;
            color:#fff;
            border-radius:6px;
            text-decoration:none;
        }

        /* HERO SECTION */
        .hero{
            width:100%;
            display:flex;
            padding:80px 50px;
            background:linear-gradient(to right,#0d78d4,#2c5fd4);
            color:#fff;
        }

        .hero-left{
            width:50%;
            padding-right:40px;
        }

        .hero-left h1{
            font-size:48px;
            margin-bottom:20px;
        }

        .hero-left p{
            font-size:18px;
            margin-bottom:25px;
            opacity:0.9;
        }

        .hero-btn{
            padding:12px 25px;
            background:#fff;
            border-radius:8px;
            color:#333;
            font-size:16px;
            text-decoration:none;
            font-weight:bold;
        }

        .hero-right{
            width:50%;
        }

        .hero-right img{
            width:100%;
            border-radius:12px;
        }

        /* FEATURES SECTION */
        .features {
            padding: 60px 50px;
            background: #fff;
            text-align: center;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
            margin-top: 40px;
        }

        .feature-card {
            padding: 30px 20px;
            border-radius: 12px;
            background: #f9f9f9;
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .feature-icon {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .feature-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #0d1b4b;
        }

        .feature-desc {
            color: #666;
            line-height: 1.5;
        }

        /* BOOK SECTION */
        .section{
            padding:40px 50px;
        }

        .section-title{
            font-size:22px;
            margin-bottom:25px;
        }

        .books{
            display:grid;
            grid-template-columns:repeat(2,1fr);
            gap:30px;
        }

        .book-card{
            background:#fff;
            border-radius:12px;
            padding:15px;
            box-shadow:0 3px 8px rgba(0,0,0,0.1);
        }

        .book-card img{
            width:100%;
            height:250px;
            object-fit:cover;
            border-radius:12px;
            margin-bottom:12px;
        }

        .book-title{
            font-size:20px;
            font-weight:bold;
        }

        .book-author{
            font-size:14px;
            color:#666;
        }

        .price{
            margin-top:8px;
            font-size:16px;
        }

        .add-btn{
            margin-top:12px;
            padding:10px;
            width:100%;
            background:#0d1b4b;
            color:#fff;
            border:none;
            border-radius:8px;
            cursor:pointer;
            font-size:16px;
        }

        /* READING JOURNEY SECTION */
        .reading-journey {
            padding: 80px 50px;
            background: linear-gradient(to right, #0d78d4, #2c5fd4);
            color: #fff;
            text-align: center;
            margin-top: 40px;
        }

        .journey-content {
            max-width: 600px;
            margin: 0 auto;
        }

        .journey-content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .journey-content p {
            font-size: 18px;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .journey-btn {
            padding: 12px 25px;
            background: #fff;
            border-radius: 8px;
            color: #333;
            font-size: 16px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
        }
    </style>

</head>
<body>

    <!-- NAVBAR -->
    <nav>
        <div class="logo">📘 BookHaven</div>

        <div class="nav-links">
            <a style="color:#2c5fd4;" href="#">Home</a>
            
            <a href="books.html">Books</a>
        </div>

        <div class="nav-right">
            🛒
            <a href="login.html" class="login-btn">Login</a>
            
        </div>
    </nav>

    <!-- HERO SECTION -->
    <div class="hero">
        <div class="hero-left">
            <h1>Discover Your<br>Next Great<br>Read</h1>
            <p>Explore thousands of books across all genres. Fast delivery, secure payment, and great prices.</p>
            <a href="#" class="hero-btn">Browse Books →</a>
        </div>

        <div class="hero-right">
            <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f" alt="">
        </div>
    </div>

    <!-- FEATURES SECTION -->
    <div class="features">
        <h2 class="section-title">Why Choose BookHaven?</h2>
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">🚚</div>
                <h3 class="feature-title">Fast Delivery</h3>
                <p class="feature-desc">Quick and reliable shipping to your doorstep</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💰</div>
                <h3 class="feature-title">Best Prices</h3>
                <p class="feature-desc">Competitive prices on all our books</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📚</div>
                <h3 class="feature-title">Wide Selection</h3>
                <p class="feature-desc">Thousands of books across all genres</p>
            </div>
        </div>
    </div>

    <!-- FEATURED BOOKS -->
    <div class="section">
        <h2 class="section-title">Featured Books</h2>

        <div class="books">

            <!-- BOOK 1 -->
            <div class="book-card">
                <img src="https://via.placeholder.com/400x250" alt="">
                <p class="book-title">The Midnight Library</p>
                <p class="book-author">Matt Haig</p>
                ⭐ 4.5
                <p class="price">$16.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 2 -->
            <div class="book-card">
                <img src="https://tse3.mm.bing.net/th/id/OIP.RgKVDGE_x4uyE1JjjKuWWwHaHa?pid=Api&P=0&h=220" alt="">
                <p class="book-title">Atomic Habits</p>
                <p class="book-author">James Clear</p>
                ⭐ 4.8
                <p class="price">$14.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

        </div>

        <br><br>

        <div class="books">

            <!-- BOOK 3 -->
            <div class="book-card">
                <img src="https://tse2.mm.bing.net/th/id/OIP.Ei-67fm6RGwk05DkdAmeHgHaEo?pid=Api&P=0&h=220" alt="">
                <p class="book-title">The Silent Patient</p>
                <p class="book-author">Alex Michaelides</p>
                ⭐ 4.3
                <p class="price">$15.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 4 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="">
                <p class="book-title">Sapiens</p>
                <p class="book-author">Yuval Noah Harari</p>
                ⭐ 4.7
                <p class="price">$12.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 5 -->
            <div class="book-card">
                <img src="https://tse1.mm.bing.net/th/id/OIP.9j0kj9e2UhR1jB6q-9MviAHaEt?pid=Api&P=0&h=220" alt="">
                <p class="book-title">Project Hail Mary</p>
                <p class="book-author">Andy Weir</p>
                ⭐ 4.7
                <p class="price">$18.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 6 -->
            <div class="book-card">
                <img src="https://tse3.mm.bing.net/th/id/OIP.s53-jcSF3qWi0WlNcU-9qgHaGK?pid=Api&P=0&h=220" alt="">
                <p class="book-title">The Psychology of Money</p>
                <p class="book-author">Morgan House</p>
                ⭐ 4.7
                <p class="price">$30</p>
                <button class="add-btn">Add to Cart</button>
            </div>

        </div>

    </div>

    <!-- READING JOURNEY SECTION -->
    <div class="reading-journey">
        <div class="journey-content">
            <h2>Start Your Reading Journey Today</h2>
            <p>Join thousands of readers who trust BookHaven for their reading needs</p>
            <a href="#" class="journey-btn">Explore Our Collection</a>
        </div>
    </div>

</body>
</html>
