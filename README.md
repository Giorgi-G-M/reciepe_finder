# 🍽️ Recipe Finder App  

A simple and responsive web app for discovering recipes from around the world. It uses **[TheMealDB API](https://www.themealdb.com/api.php)** to fetch meal data and display it in an elegant card-based layout. Users can search for meals by keywords, view ingredients, instructions, and even watch YouTube tutorials for each recipe.

---

## 🚀 Features  

- 🔎 **Search Recipes** by meal name or keyword  
- 📝 **Detailed Recipe View** with instructions and category tags  
- 🛒 **Ingredients List** with measurements  
- ▶️ **YouTube Tutorial Link** for each recipe (if available)  
- ⚡ **Responsive Design** for mobile and desktop  
- ❌ **Error Handling** for empty searches or no results  

---

## 🖼️ Demo  

![Screenshot](screenshot.png)  
*(Replace with your own screenshot or GIF of the app)*  

---

## 🛠️ Technologies Used  

- **HTML5** – Structure  
- **CSS3** – Styling & Responsive Layout  
- **Vanilla JavaScript (ES6)** – Fetching API data & DOM manipulation  
- **Font Awesome** – Icons  

## 📱 Responsive Design

    The app is fully responsive:

    On smaller screens, the search bar stacks vertically.

    Meal cards switch to a single-column layout.

    Ingredients list adapts to smaller widths.


## 🔗 API

This app uses TheMealDB API:

Search meals: https://www.themealdb.com/api/json/v1/1/search.php?s={query}

Lookup meal by ID: https://www.themealdb.com/api/json/v1/1/lookup.php?i={id}

---
recipe-finder-app/
│
├── index.html        # Main HTML page
├── style.css         # Stylesheet
└── script.js         # JavaScript logic
