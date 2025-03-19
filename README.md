## DietApp

A meal planning application that generates customized meal plans based on user dietary preferences, restrictions, and nutritional goals.

## Overview

DietApp generates personalized meal plans based on user-selected diet protocols, meal frequency, cuisine preferences, and dietary restrictions. By the use of the LLM, the app will produce detailed meal plans containing ingredients, nutritional information, and preparation instructions. The application creates diverse meal options that adhere to nutritional guidelines while accommodating user preferences.

## Exemplary user input
The user selects options from dropdown menus to specify their preferences:
- Type of diet (e.g., low glycemic, high-protein, carnivore, etc.)
- Number of meals (e.g., 3 meals per day)
- Cuisine type (e.g., Italian, French, Asian, etc.)
- Whether the meals should be vegetarian or vegan
- Any allergens to avoid (e.g., gluten, nuts, lactose)

# Tech stack 
**Backend**
- Python
- FastAPI
- MongoDB
- LLM API integration (most probably pplx-api)
- Node.js
- Redis (in the future, for caching)

**Frontend**
- Svelte

**Tools**
- Docker
