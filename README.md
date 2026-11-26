# Time2Cook 👨‍🍳

**Recipes that fit your time!**

Time2Cook is an interactive prototype of a mobile recipe app, created for an HCI (Human–Computer Interaction) course assignment. Instead of searching by ingredient or dish, users choose **how much time they have** and get recipes that fit, filtered by country.

🔗 **Live demo:** https://keku5951.github.io/Time2Cook/

---

## Features

- **Time-based categories**
  - 🍲 **Long Cooking** – more than 60 minutes
  - ⏱️ **Quick Cooking** – 10–30 minutes
  - 🥗 **No Cooking** – 0–10 minutes
- **Country selection** – a dropdown to filter recipes by cuisine (🇸🇪 Sweden, 🇮🇳 India, 🇮🇹 Italy, or 🌍 All countries)
- **Recipe details** – prep and cook time, ingredients, and step-by-step instructions (tap a step to tick it off)
- **Favorites** – save recipes with ❤️ or the *Save Recipe* button
- **Search** – find recipes within a category using 🔍
- **My Catalogue** – add your own recipes. Time2Cook sorts them into Long, Quick or No Cooking based on the prep and cook time you enter
- **Settings** – dark mode, text size (S / M / L) and clearing saved recipes

## How to use

1. Open the app and pick a **country** from the dropdown.
2. Choose a time category: **Long**, **Quick** or **No Cooking**.
3. Tap a recipe to see its ingredients and steps.
4. Tap **Save Recipe** to add it to **Favorites**.
5. Go to **📖 Catalogue** → **Add your own recipe** to create your own.

## Screens

| Screen | Purpose |
|---|---|
| Home | Country dropdown and the three time categories |
| Recipe list | Recipes in the chosen category and country, sorted by time |
| Recipe detail | Prep/cook time, ingredients, steps, save |
| Favorites | All saved recipes |
| Catalogue | User-created recipes, with an add form |
| Settings | Dark mode, text size, clear favorites |

## Run locally

No installation or build is needed. Download `index.html` and open it in any modern browser (Chrome, Safari, Edge, Firefox). It works on both desktop and mobile.

## Technology

- A single HTML file using plain HTML, CSS and JavaScript (no frameworks)
- Data such as favorites, your own recipes and settings is stored in the browser's `localStorage`, so it stays on your device only
- Hand-drawn style (Patrick Hand font) to match the original paper wireframe

## About this prototype

This is a **prototype** for an HCI course. It turns the paper wireframe sketch into an interactive version so the interaction flow can be tested and presented. The recipe content is sample data.

**Author:** Keerthana Kunkunuru
