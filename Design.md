Maelicious - Design
---

### Introduction

My goal is to create a webserver to store and nicely display the numerous recipes I have stored in image format across several hard drives and cloud services. The recipes will be stored on my own MySQL database in text form for easy searching and relationship manipulation. 

I will have been successful in this project across two steps.

1. Successfully created a React website that uses HTTP requests to a RESTful API connected to a relational database. This will all be locally hosted, but all MVP functionality completed

2. Migrate the entire application to a VPS and host the website live on the web

---

### Requirements

- [ ] Search Bar
    - [ ] Recipe Titles
    - [ ] All recipes using the ingredient ‘x’
    - [ ] Cooking Type (E.g. one-pot, slow-cooked, roast, etc)
    - [ ] Meal Types (E.g. Dinner, Snack, Dessert, etc)
- [ ] Meal Queue
    - [ ] A queue of recipes for weekly planning
    - [ ] Allow editing of the queue
        - [ ] Removing meals
        - [ ] Confirming a meal was cooked
        - [ ] Alter the order of meals
    - [ ] Tied to user’s account
    - [ ] Generate a list of ingredients needed for the week
- [ ] Account-Based
    - [ ] Queue tied to user’s account
    - [ ] Cookies/Sessions
    - [ ] Create Account/Log In Page
        - [ ] Password strength check
        - [ ] Dynamic password strength bar
    - [ ] alted hash stored in DB
    - [ ] Email address used as username
    - [ ] Store date account was created and the most recent login
- [ ] Menu Bar
    - [ ] Meat Types dropdown
    - [ ] Meal Type dropdown
    - [ ] Cooking Type dropdown
    - [ ] Most Popular
- [ ] Recipe Grid
    - [ ] Sort by A-Z/Price/Time
    - [ ] Filters on ingredients, meal-type, meat types, food groups, etc.
    - [ ] Display in pages
- [ ] Ingredient Page
    - [ ] Search for an ingredient or click on it from a recipe
    - [ ] Image and a brief description
    - [ ] All recipes that use the ingredient
    - [ ] Display how often the recipe is made
    - [ ] Back button
- [ ] Recipe Page
    - [ ] Ingredients
    - [ ] Tags
    - [ ] Instructions
    - [ ] Proportion Multiplier
    - [ ] Back button
- [ ] API
    - [ ] Receives HTTP requests from website
    - [ ] Returns relevant data
    - [ ] Creates accounts in database
    - [ ] Successfully logs in users
- [ ] Database
    - [ ] Stores and returns recipes
    - [ ] Stores passwords securely
    - [ ] Relationships correctly established
    - [ ] Indexes created on searchable attributes

---

### Minimum Viable Product

- [ ] Website
    - [ ] Display recipes in a grid
    - [ ] Clicking on a recipe will load the full recipe page
- [ ] API
    - [ ] Receives HTTP requests from website
    - [ ] Returns relevant data
- [ ] Database
    - [ ] Stores and returns recipes

---

### Estimated work

| Stage         | Time        | 
|---            |---          |
| Database      | 17/07/2022  |
| Website MVP   | 24/07/2022  |
| API MVP       | 08/08/2022  |
| | |


---

### Detailed design

#### Tech stack

1. Dynamic Website 
   - Express Web Framework 
   - Main Language: TypeScript
2. API
    - RESTful API
    - Built using Node.js
    - Main Language: TypeScript
3. Relational Database
    - MySQL
4. Hosting on VPS

#### Dataflow diagrams




#### User interaction

---

### Risk assessment

< What could go wrong? >

Example:

#### Missing core requirement

We are at risk of missing something key to our client within out initial design.

##### Likelihood

Medium

##### Impact if this occurs

High as it requires immediate attention and work

#### Mitigation

Attempt to complete a thorough design and get the client to sign off before work begins