# brandon-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="menu breakfast">
        <h2>Breakfast Menu</h2>
        <ul>
            <li>Pancakes</li>
            <li>Omelette</li>
            <li>Smoothies</li>
        </ul>
    </div>
    
    <div class="menu lunch">
        <h2>Lunch Menu</h2>
        <ul>
            <li>Salad</li>
            <li>Sandwich</li>
            <li>Soup</li>
        </ul>
    </div>
    
    <div class="menu dinner">
        <h2>Dinner Menu</h2>
        <ul>body {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.menu {
    width: 400px;
    height: 550px;
    padding: 20px;
    margin: 15px;
    border: 2px solid #333;
    color: white;
    font-family: Arial, sans-serif;
    list-style-type: none;
}

.breakfast {
    background-image: url('breakfast.jpg'); /* Add your breakfast image */
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.lunch {
    background-image: url('lunch.jpg'); /* Add your lunch image */
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.dinner {
    background-image: url('dinner.jpg'); /* Add your dinner image */
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}
            <li>Steak</li>
            <li>Pasta</li>
            <li>Dessert</li>
        </ul>
    </div>
</body>
</html>
