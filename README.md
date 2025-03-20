<!DOCTYPE html>
<html>
<head>
    <title>Cooking with Love</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: url('https://i.imgur.com/2xtqKYn.png') no-repeat center center fixed;
            background-size: cover;
            color: #f8f8f8;
            display: flex;
        }
        .sidebar {
            width: 200px;
            background: rgba(30, 30, 30, 0.8);
            padding: 20px;
            position: fixed;
            left: 0;
            top: 0;
            height: 100%;
            box-shadow: 2px 0px 10px rgba(255, 165, 0, 0.5);
        }
        .sidebar a {
            display: block;
            color: #e67e22;
            text-decoration: none;
            margin: 10px 0;
            font-size: 18px;
        }
        .sidebar a:hover {
            color: #f39c12;
        }
        .content {
            margin-left: 220px;
            width: 100%;
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        h1 {
            color: #e67e22;
        }
        .section {
            background: rgba(30, 30, 30, 0.8);
            padding: 20px;
            margin: 20px auto;
            width: 50%;
            box-shadow: 0px 0px 15px rgba(255, 165, 0, 0.5);
            border-radius: 10px;
        }
        button {
            background-color: #c0392b;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
        }
        button:hover {
            background-color: #e74c3c;
        }
        .meme img {
            width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>Links</h2>
        <a href="https://www.youtube.com" target="_blank">YouTube</a>
        <a href="https://www.twitch.tv" target="_blank">Twitch</a>
    </div>
    <div class="content">
        <h1>Welcome to Cooking with Love</h1>
        <p>Discover simple and delicious recipes!</p>
        
        <div class="section">
            <h2>Recipes</h2>
            <div class="recipe">
                <h3>Easy Pancakes</h3>
                <p>Ingredients: Flour, Eggs, Milk, Sugar, Baking Powder</p>
                <button onclick="alert('Enjoy your pancakes!')">Try This Recipe</button>
            </div>
            <div class="recipe">
                <h3>Chocolate Chip Cookies</h3>
                <p>Ingredients: Flour, Butter, Sugar, Chocolate Chips, Eggs, Baking Soda</p>
                <button onclick="alert('Enjoy your cookies!')">Try This Recipe</button>
            </div>
        </div>
        
        <div class="section meme">
            <h2>Funny Cooking Memes</h2>
            <img src="https://i.imgur.com/J8XBytF.jpeg" alt="Funny Cooking Meme 1">
            <img src="https://i.imgur.com/2z8AYDk.jpeg" alt="Funny Cooking Meme 2">
        </div>
    </div>
</body>
</html>
