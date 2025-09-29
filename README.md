# zomato-dish-description-generator
A free AI-powered tool to generate appetizing dish descriptions from Excel files using Groq API.

# Dish Description Generator

A free, browser-based tool to instantly generate appetizing 2-line descriptions for menu items using AI (powered by Groq). Upload an Excel file with dish names, enter your Groq API key, and download the updated file with descriptions.

## Features
- **Quick & Easy**: Processes Excel files locally in your browser—no server uploads.
- **AI-Powered**: Uses Groq API for fast, high-quality descriptions (you provide your own free API key).
- **Customizable**: Set word limits per description.
- **Free to Use**: Runs client-side; no costs beyond your API usage (Groq has a generous free tier).

## How to Use
1. Visit the live tool: [https://Shrutik2712.github.io/dish-description-generator/zomato_dish_description_generator.html](https://Shrutik2712.github.io/zomato-dish-description-generator/zomato_dish_description_generator.html).
2. Get a free Groq API key: Sign up at [console.groq.com](https://console.groq.com) and create a key (takes 1 minute).
3. Upload your Excel file (.xlsx or .xls) with dish names in Column A (starting from row 1 or 2).
4. Enter your API key and optional word limit.
5. Click "Generate Descriptions" and download the updated Excel with added descriptions in Column B.

**Example Input Excel**:
| A          |
|------------|
| Pizza     |
| Burger    |

**Output**: Descriptions like "Savor the cheesy delight of our classic pizza, topped with fresh ingredients." (2 lines each).
