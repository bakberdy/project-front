# Recipe Web Application

This is a responsive recipe web application where users can view detailed recipes, including nutritional information, ingredients, and step-by-step instructions. Built with HTML, CSS, and JavaScript, the app provides a user-friendly experience on mobile, tablet, and desktop devices.

## Features

- **Recipe Display**: Each recipe page shows the title, author, and an overall rating.
- **Ingredients List**: View a complete list of ingredients for the recipe.
- **Step-by-Step Instructions**: Follow easy-to-understand steps to prepare the recipe.
- **Nutritional Information**: View nutritional details, including calories, fat, protein, and carbohydrates.
- **Favorite Recipes**: Save favorite recipes for quick access.
- **Recipe Search**: Search for recipes using keywords or titles.
- **Responsive Design**: Ensures a seamless experience across all device types.

## Folder Structure

```
project/
├── assets/                        # Folder for static assets
│   ├── setka_bottom.svg           
│   ├── setka_top.svg              
│   └── welcome_food.png           
├── favorite/                      # Folder for favorite recipes page
│   ├── css/                       
│   ├── html/                      
│   └── js/                        
├── search_page/                   # Folder for search page
│   ├── css/                       
│   ├── html/                      
│   └── js/                        
├── food_details/                  # Folder for detailed recipe view
│   ├── css/                      
│   ├── html/                      
│   └── js/                        
└── index.html                     # it is to github pages
```

## Styles and Design

The project uses the "Poppins" font for a clean and modern aesthetic. Custom CSS classes are applied to elements like the recipe card, header, ingredients list, and nutrition details. The CSS also includes media queries to ensure the application is responsive on different screen sizes.

### Main Components

- **Recipe Card**: Displays the main details of each recipe, including title, author, and rating.
- **Ingredients Section**: Lists all ingredients needed for the recipe.
- **Instructions Section**: Provides step-by-step preparation instructions.
- **Nutrition Section**: Displays key nutritional information in a visual format.
- **Favorites Section**: Allows users to save and manage their favorite recipes.
- **Search Section**: Lets users search for recipes by name or keyword.

## Responsive Design

Media queries in `styles.css` make the design responsive for different devices:

- **Desktop**: Full layout with larger font sizes and appropriate padding.
- **Tablet**: Adjusted margins and font sizes for a comfortable viewing experience on medium screens.
- **Mobile**: Stacked layout with optimized font sizes and padding for smaller screens.

## Technologies Used

- **HTML**: Provides the structure of the web pages.
- **CSS**: Handles styling and responsive design.
- **JavaScript**: Adds interactivity and dynamic content.

## Try it 
<a>https://bakberdy.github.io/recipe-web-app</a>
