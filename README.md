# MERN AMAZONA

# LESSON
1. Introduction
2. Install tools
3. Create React App
4. Create Git Repo
5. List Products
    1. Create Products Array
    2. Add Product Images
    3. Render Products
    4. style products
6. Add routing
    1. npm i react-router-dom
    2. create route for home screen
    3. create router for product screen
7. Create Node.JS Server
    1. run npm init in root folder
    2. Update package.json set type: module
    3. Add .js to imports
    4. npm install express
    5. Create server.js
    6. Add start command as node backend/server.js
    7. require express
    8. create route for / return backend is ready.
    9. move product.js from frontend to backend
    10. create route for /api/products
    11. return products
    12. run npm start
8. Fetch products from backend
    1. set proxy in package.json
    2. npm install axios
    3. use state hook
    4. use effect hook
    5. use reducer hook
9. Manage State by Reducer hook
    1. define reducer
    2. Update fetch data
    3. get state from usReducer
10. Add bootstrap UI Framework
    1. npm install react-bootstrap bootstrap
    2. update App.js
11. Create product and Rating Component
    1. Create Rating Component
    2. Create Product Component
    3. Use Rating component in Product component
12. Create Product Details screen
    1. fetch product from backend
    2. Create 3 columns for image, info and action
13. Create Loading and Message Component
    1. Create Loading Component
    2. Use Spinner Component
    3. Create Message Component
    4. Create utils.js to define getError function
14. Implement Add to Cart
    1. Create React Context
    2. Define Reducer
    3. Create Store Provider
    4. Implement Add to Cart button click handler
15. Complete Add to Cart
    1. Check exist item in the cart
    2. Check count in stock in backend
16. Create Cart Screen
    1. Create 2 columns
    2. display items list
    3. Create Action column
17. Complete cart Screen
    1. click handler for increase/decrease item
    2. Click handler for remove item
    3. click handler for checkout
18. Create Sign in screen
    1. Create sign in form
    2. Add email and password
    3. Add sign in button