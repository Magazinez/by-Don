<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magazine Subscription Service</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin: 1rem 0;
        }
        nav a {
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #81C784;
        }
        .hero {
            text-align: center;
            padding: 3rem 2rem;
            background: linear-gradient(to right, #4CAF50, #81C784);
            color: white;
            border-radius: 0 0 20px 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .hero p {
            font-size: 1.4rem;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        .subscriptions {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem;
            padding: 2rem;
        }
        .subscription {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .subscription:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .subscription h3 {
            color: #4CAF50;
            margin-bottom: 1rem;
        }
        .subscription p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 1.5rem;
        }
        .btn {
            display: inline-block;
            background-color: #4CAF50;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #388E3C;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Magazine Subscription Service</h1>
        <p>Your favorite magazines delivered to your doorstep!</p>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#subscriptions">Subscriptions</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h1>Welcome to Our Service</h1>
        <p>Curated magazines for older adults. Subscribe today and stay informed and entertained!</p>
    </section>

    <section class="subscriptions" id="subscriptions">
        <div class="subscription">
            <h3>Monthly Plan</h3>
            <p>Get access to a curated selection of magazines every month.</p>
            <p><strong>$10/month</strong></p>
            <a href="#" class="btn">Subscribe Now</a>
        </div>
        <div class="subscription">
            <h3>Quarterly Plan</h3>
            <p>Save more with our 3-month subscription package.</p>
            <p><strong>$25/quarter</strong></p>
            <a href="#" class="btn">Subscribe Now</a>
        </div>
        <div class="subscription">
            <h3>Annual Plan</h3>
            <p>Enjoy a full year of magazines at a discounted price.</p>
            <p><strong>$90/year</strong></p>
            <a href="#" class="btn">Subscribe Now</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Magazine Subscription Service. All rights reserved.</p>
    </footer>
</body>
</html>
