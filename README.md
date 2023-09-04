# odin-recipes

This project is an assignment for the Foundations Course on theodinproject.com.  The assignment is to create a recipe website consisting of a main index page and a few recipes.  I will be using recipes I found on the internet that I am actually using for family dinners this week. I intend to include links to the orinial recipe sites.

This will likely be an easy assignment as I have been studying html, css, and javascript on another site (freeCodeCamp).  I am working on this as review, and because this project will be revisited on later in this course.

Assignment text:
---------------------------------------------------------------------------------------------
Iteration 1: initial structure
Within the odin-recipes directory, create an index.html file.
Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.
Iteration 2: recipe page
Create a new directory within the odin-recipes directory and name it recipes.
Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use here.
For now, just include an h1 heading with the recipe’s name as its content.
Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.
Iteration 3: recipe page content
Your new recipe page should have the following content:

An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or the recipe site we linked to earlier.

Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.

Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: add more recipes
Add two more recipes with identical page structures to the recipe page you’ve already created.
Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.
Example:

 <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
Your links won’t be flashy, but for now just focus on building them out.
------------------------------------------------------------------------------------------------

Things I learned:

1. I spent an embarrassing amount of time trying to figure out why the image wasn't loading while working on the first recipe.  I finally realized that I was using href="..." for the img tag instead of src="...".  A simple mistake, but I'm glad I made it as I don't think I'll be messing that one up again.

2. Read an article on TOP about not overdoing projects or spending too much time on things not essential to the assignment.  Helped resist the urge to work much longer or try to manipulate things in html that I now I will work out with css later.