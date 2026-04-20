<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Subscriptions</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #121212;
            color: white;
            display: flex;
            justify-content: center;
            padding: 40px;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            width: 100%;
            max-width: 1000px;
        }
        .card {
            background: #1e1e1e;
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            border: 1px solid #333;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-10px);
            border-color: #e50914;
        }
        .card h2 { margin-bottom: 10px; font-size: 1.5rem; }
        .card p { color: #bbb; font-size: 0.9rem; margin-bottom: 20px; }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #e50914;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .gaana { background-color: #f02727; }
        .insta { background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888); }
    </style>
</head>
<body>

<div class="container">
    <div class="card">
        <h2>Instagram</h2>
        <p>Get Premium Followers & Growth</p>
        <a href="https://instagram.com/YOUR_USERNAME" class="btn insta">View Profile</a>
    </div>

    <div class="card">
        <h2>Netflix</h2>
        <p>Premium Ultra HD Subscriptions</p>
        <a href="https://www.netflix.com" class="btn">Access Netflix</a>
    </div>

    <div class="card">
        <h2>Gaana</h2>
        <p>Classic 2017 Hits & Premium Radio</p>
        <a href="https://gaana.com" class="btn gaana">Listen Now</a>
    </div>
</div>

</body>
</html>
