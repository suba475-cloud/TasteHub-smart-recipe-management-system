# TasteHub-smart-recipe-management-system
A simple recipe finder app is built with HTML , CSS, js
TasteHub is a responsive recipe-management frontend built with HTML, CSS, Bootstrap 5 and JavaScript.

## Recipe catalogue
The demo includes 40 recipes across beverages, breakfast, Indian, Italian, Chinese, Mexican, fast food, snacks, healthy food and desserts. It is designed so more recipes can be added easily to the same structured data format.

## Smart quantity scaling
Every recipe stores:
- base serving count
- ingredient name
- base quantity
- unit

Open a recipe and change **How many people?** to 2, 4, 10, 100, 1000 or 5000. TasteHub calculates:

scaled quantity = base quantity × requested people ÷ base servings

The result is shown ingredient-by-ingredient.

For very large groups, this is a mathematical scaling tool, not a guarantee that a commercial kitchen can cook one giant batch identically. A real catering implementation should also consider yield loss, batch capacity, rounding, equipment and service waste.

## Current features
- Search by recipe, ingredient, tag or category
- Category browsing
- Recipe details
- Ingredient quantities
- Dynamic serving calculator up to 100,000 people
- Favorites
- Add Recipe
- Dark mode
- Responsive Bootstrap UI
- Local browser storage for favorites

## Java project extension
Recommended architecture:
Frontend (HTML/CSS/Bootstrap/JS)
→ Java Servlet/JSP or Spring Boot
→ MySQL

Then recipe data, users, favorites and CRUD operations can be persisted in a database.
