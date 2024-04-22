### API Specification

## Users
### `/users/signup` (POST)
Create new user.
### `/users/login` (POST)
Login existing user.
### `/users/{user_id}` (POST)
Update user profile.
### `/users/{user_id}` (GET)
Retrieve information about a given user.

## Ingredients
### `/ingredients/` (POST)
Add a new ingredient.
### `/ingredients/{ingredient_id}` (GET)
Retrieve information about a given ingredient.

## Recipes
### `/recipes/` (POST)
Add a new recipe.
### `/recipes/{recipe_id}` (GET)
Retrieve information about a given recipe.

## Ratings
### `/ratings/{recipe_id}` (POST)
User assigns rating to recipe.