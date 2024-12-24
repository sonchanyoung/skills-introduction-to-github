<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Custom Product Platform</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        header {
            background-color: #87CEEB;
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        header nav {
            display: flex;
            gap: 15px;
        }

        header nav a {
            color: white;
            text-decoration: none;
            font-size: 16px;
        }

        .main-banner {
            background-color: #d5f4fd;
            text-align: center;
            padding: 50px 20px;
        }

        .main-banner h1 {
            margin: 0;
            font-size: 36px;
            color: #333;
        }

        .categories {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background-color: white;
        }

        .category-item {
            text-align: center;
        }

        .featured-creators, .new-requests {
            padding: 20px;
        }

        .section-title {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            background-color: white;
            margin-bottom: 20px;
        }

        footer {
            background-color: #f1f1f1;
            text-align: center;
            padding: 10px 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Custom Platform</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Categories</a>
            <a href="#">Login</a>
        </nav>
    </header>

    <section class="main-banner">
        <h1>Welcome to Your Custom Product Platform</h1>
        <p>Create or discover unique, personalized products today!</p>
    </section>

    <section class="categories">
        <div class="category-item">
            <h3>Figures</h3>
        </div>
        <div class="category-item">
            <h3>Custom Goods</h3>
        </div>
        <div class="category-item">
            <h3>More...</h3>
        </div>
    </section>

    <section class="featured-creators">
        <div class="section-title">Featured Creators</div>
        <div class="card">Creator 1</div>
        <div class="card">Creator 2</div>
    </section>

    <section class="new-requests">
        <div class="section-title">New Requests</div>
        <div class="card">Request 1</div>
        <div class="card">Request 2</div>
    </section>

    <footer>
        &copy; 2024 Custom Product Platform | All Rights Reserved
    </footer>
</body>
</html>
