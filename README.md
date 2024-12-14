# Recipe-Book

A simple web-based **Recipe Book** application where users can add, view, and store recipes. The app allows users to input the title, ingredients, and instructions for recipes, and displays the list of saved recipes. When a user clicks on a recipe, it shows the full details of the recipe.

## Features

- Add new recipes with a title, ingredients, and instructions.
- View a list of all added recipes.
- Click on any recipe in the list to view its details.
- Store recipes locally in the browser using `localStorage` so they persist even after the page reloads.
- Simple and user-friendly interface.

## Technologies Used

- **HTML**: Structure of the webpage and form elements.
- **CSS**: Styling of the page to make it visually appealing and responsive.
- **JavaScript**: Logic for adding, storing, and displaying recipes, as well as managing local storage.

## How to Use

1. **Add a Recipe**: 
   - Enter the **Recipe Title**, **Ingredients**, and **Instructions** in the form fields.
   - Click the **Add Recipe** button to add the recipe to your recipe book.
   
2. **View Recipe List**: 
   - All added recipes will be displayed in the recipe list.
   - Each recipe will be clickable, and upon clicking, you can see the full details of that recipe.

3. **Recipe Details**: 
   - When a recipe is clicked, the full **Ingredients** and **Instructions** are shown below the list.
   - You can close the recipe details by clicking the **Close** button.

4. **Persistence**: 
   - The recipes are stored in **localStorage**, so they will remain available even after a page reload.

## Example

- **Add Recipe**:
   - Title: `Spaghetti Carbonara`
   - Ingredients: `Spaghetti, Eggs, Pancetta, Parmesan Cheese`
   - Instructions: `Boil the spaghetti. Fry the pancetta. Mix eggs and cheese. Combine all ingredients.`
- **Recipe List**:
   - `Spaghetti Carbonara`
   - `Pancake`
   - `Chicken Curry`

## Code Explanation

- **HTML Structure**:
   - A form is used to input recipe details (title, ingredients, and instructions).
   - A section to display the list of recipes and a separate section for showing recipe details.

- **CSS Styling**:
   - Basic styling is applied to the form, buttons, and recipe list to make it visually appealing.
   - The layout is simple with responsive design for different screen sizes.

- **JavaScript Functionality**:
   - Recipes are stored and retrieved from **localStorage** using `localStorage.setItem()` and `localStorage.getItem()`.
   - Recipes are displayed in a list, and clicking a recipe shows its detailed information.
   - Recipes are added when the "Add Recipe" button is clicked, and if the fields are empty, an alert is shown.
   - Recipe details can be closed using a **Close** button.

