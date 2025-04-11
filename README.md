<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resturant Reciepe</title>
</head>
<body>
    <header>
        <nav>
            <a href="#Home">Home</a>
            <a href="#Add">Add Recipe</a>
            <a href="#Home">Recipe List</a>

        </nav>
    </header>
    <!-- Welcome part -->
    <h1>Welcome To My Recipe Book </h1>
    <p>Here you can taste delicious traditional Afghan meals . We are always here to bring new tastes</p>
     <!-- closed -->
     <!-- menu recipe -->
    <h2>Recipe of The Day:Chiken Shorma</h2>
    <p>This fast food is best choice for our customers</p>
    <img src="https://img.freepik.com/free-photo/side-view-shawarma-with-fried-potatoes-board-cookware_176474-3215.jpg?ga=GA1.1.2071099436.1739361925&semt=ais_country_boost&w=740" alt="image-type"width="300px">
    <p><a href="index.html">View full recipe</a></p>
    <h2>Featured Categories</h2>
<ul>
    <li><a href="Desserts">Desserts</a></li>
    <li><a href="Vegans">Vegans</a></li>
    <li><a href="Fast Foods">Fast Foods</a></li>
</ul>
    <!-- closed -->

<!-- Add section -->
<h1>Add A New Recipe</h1>
<form>
    <br>
<label for="recipe-name">Recipe Name:</label><br><br>
<input type="text" id="recipe-name" name="recipe-name" required><br><br>

<label for="Ingredients">Ingredients:</label><br>
<textarea id="ingredients" name="ingredients" rows="6" cols="50" required></textarea><br>

<label for="Instructions">Instructions:</label><br>
<textarea id="instruction" name="instruction" rows="6" cols="50" required></textarea><br>

<label for="Image Url">Image URl:</label><br>
<input type="text" id="images" name="image url"></input><br><br>

<label for="category">Recipe Category</label>
<select id="category" name="category" required>
<option value="">Select</option>
<option value="desserts">Dessert</option>
<option value="appetizers">Appetizers</option>
<option value="vegan">Vegan</option>
<option value="fast Foods">Fast Foods</option>
</select><br><br>

<button type="submit">Add Recipe</button>
<!-- add recipe close -->
<!-- Recipe List -->
<h2>Filter By category</h2>
<select>
    <option value="all">All</option>
    <option value="desserts">Dessert</option>
    <option value="vegan">Vegan</option>
    <option value="fast">Fast foods</option>  
</select>
<!-- closed -->
<!-- Recipe name -->
<h3>Shorma</h3>
<img src="../images 22.jpg" alt="">
<p>Deliciuos and tasty food for everyone</p>
<a href="https://en.wikipedia.org/wiki/Lists_of_foods">More Details</a>

<h3>Desserts</h3>
<img src="../333.jpg" alt="">
<p>Deliciuos and tasty food for everyone</p>
<a href="https://en.wikipedia.org/wiki/Lists_of_foods">More Details</a>

<h3>Afghan Sofra </h3>
<img src="../4444.jpg" alt="">
<p>Deliciuos and tasty food for everyone!</p>
<a href="https://en.wikipedia.org/wiki/Lists_of_foods">More Details</a>

<!-- Details -->
<h2>Cake Ingredients</h2>
<ul>
<li>2 cup of flour</li>
<li>spices</li>
<li>Sugar</li>
<li>Vegatable Oil</li>
</ul>
<h3>Instruction</h3>
<ol>
    <li> reheat oven to 350°F (175°C). Grease and flour two round pans.</li>
    <li> Mix sugar, flour, cocoa, baking powder in a bowl</li>
    <li>our into pans and bake for 30-35 minutes.
    Let cool before removing from pans and serving.</li>
</ol>
<img src="../download.jpg" alt="Image">

<p > <strong>Recipe by: JOHN USA</strong> </p>

<footer>
2025 My Recipe Book. All rights reserved. By Tooba Islamzay

</footer>

</form>






</body>
</html>
