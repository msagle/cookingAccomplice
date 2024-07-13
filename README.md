# cookingAccomplice
I needed a personal project to work on, so I asked chatGPT for help... 

✨ *Sure! Here’s an idea for a full-stack coding project centered around cooking that focuses on personal management and is not social. This project will help users organize their cooking and meal planning activities efficiently, providing a comprehensive solution for managing recipes, meal plans, pantry items, and shopping lists:* ✨

### Project Overview
"Cooking Accomplice" is a web application designed to help users manage their cooking activities. Users can create personalized meal plans, generate shopping lists based on their recipes, track pantry items, and discover new recipes. The app will feature an intuitive interface for planning and organizing meals without social interaction.

### Frontend
**Tech Stack:** React, TypeScript
- **Homepage:** Display an overview of the user's meal plan for the week, upcoming meals, and a search bar for recipes.
- **Meal Plan Page:** Allow users to create and view their weekly meal plans.
- **Recipe Detail Page:** Show details of a specific recipe, including ingredients, instructions, and nutritional information.
- **Pantry Management Page:** Track items in the user’s pantry, including quantities and expiration dates.
- **Shopping List Page:** Automatically generate and manage shopping lists based on the user’s meal plan and pantry items.
- **Search and Filter:** Implement a search functionality with filters for cuisine type, dietary preferences, preparation time, etc.

### Backend
**Tech Stack:** Node.js, Express.js
- **User Authentication:** Implement user signup, login, and authentication using JWT (JSON Web Tokens).
- **Recipe Management:** Handle CRUD (Create, Read, Update, Delete) operations for recipes.
- **Meal Plan Management:** Allow users to create, read, update, and delete their meal plans.
- **Pantry Management:** Manage user’s pantry items, including tracking quantities and expiration dates.
- **Shopping List Management:** Generate and manage shopping lists based on recipes and pantry items.
- **Search Functionality:** Implement a search API that allows querying the recipe database based on various criteria.

### Database
**Tech Stack:** MongoDB (NoSQL)
- **Users Collection:** Store user information such as username, email, hashed password, profile picture, dietary preferences, etc.
- **Recipes Collection:** Store recipe information including title, ingredients, instructions, nutritional information, etc.
- **Meal Plans Collection:** Store user meal plans, linked by user ID.
- **Pantry Items Collection:** Store pantry items for each user, linked by user ID.
- **Shopping Lists Collection:** Store shopping lists generated for each user, linked by user ID.

### APIs

**User API:**
| Method | Route | Description |
| ------- | ------- | -------|
| POST | /signup | Register a new user.|
| POST | /login | Authenticate a user.|
| GET | /user/:id | Retrieve user information.|
| PUT | /user/:id | Update user information.|


**Recipe API:**
| Method | Route | Description |
| ------- | ------- | -------|
| GET | /recipes | Retrieve a list of recipes (with optional filters).|
| GET | /recipes/:id | Retrieve a single recipe by ID.|
| POST | /recipes | Submit a new recipe.|
| PUT | /recipes/:id | Update an existing recipe.|
| DELETE | /recipes/:id | Delete a recipe.|


**Meal Plan API:**
| Method | Route | Description |
| ------- | ------- | -------|
| GET | /mealplans | Retrieve all meal plans for the authenticated user.|
| GET | /mealplans/:id | Retrieve a single meal plan by ID.|
| POST | /mealplans | Create a new meal plan.|
| PUT | /mealplans/:id | Update an existing meal plan.|
 DELETE | /mealplans/:id | Delete a meal plan.|


**Pantry API:**
| Method | Route | Description |
| ------- | ------- | -------|
| GET | /pantry | Retrieve pantry items for the authenticated user.|
| POST | /pantry | Add a new pantry item.|
| PUT | /pantry/:id | Update an existing pantry item.|
| DELETE | /pantry/:id | Delete a pantry item.|


**Shopping List API:**
| Method | Route | Description |
| ------- | ------- | -------|
| GET | /shoppinglists | Retrieve all shopping lists for the authenticated user.|
| GET | /shoppinglists/:id | Retrieve a single shopping list by ID.|
| POST | /shoppinglists | Create a new shopping list.|
| PUT | /shoppinglists/:id | Update an existing shopping list.|
| DELETE | /shoppinglists/:id | Delete a shopping list.|

---

**current state:**
- [X] make repo
- [ ] set up project
- [ ] basic frontend ui 
- [ ] user api
- [ ] recipe api
- [ ] meal plan api
- [ ] pantry api
- [ ] shopping list api
- [ ] user authentication
- [ ] design database
- [ ] set up database
***
