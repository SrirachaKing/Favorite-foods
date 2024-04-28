<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Foods</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 10px 20px;
            width: 100%;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            overflow: hidden;
            width: 300px;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card .content {
            padding: 15px;
        }
        .card h3 {
            margin-top: 0;
        }
        .card p {
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Favorite Foods</h1>
    </header>
    <div class="container">
        <div class="card">
            <img src="https://example.com/sushi.jpg" alt="Sushi">
            <div class="content">
                <h3>Sushi</h3>
                <p>Sushi is a Japanese dish of prepared vinegared rice, usually with some sugar and salt, accompanying a variety of ingredients, such as seafood, often raw, and vegetables.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://example.com/pizza.jpg" alt="Pizza">
            <div class="content">
                <h3>Pizza</h3>
                <p>Pizza is a savory dish of Italian origin consisting of a usually round, flattened base of leavened wheat-based dough topped with tomatoes, cheese, and often various other ingredients.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://example.com/icecream.jpg" alt="Ice Cream">
            <div class="content">
                <h3>Ice Cream</h3>
                <p>Ice cream is a sweetened frozen food typically eaten as a snack or dessert. It may be made from dairy milk or cream and is flavored with a sweetener, either sugar or an alternative, and any spice, such as cocoa or vanilla.</p>
            </div>
        </div>
    </div>
</body>
</html>
