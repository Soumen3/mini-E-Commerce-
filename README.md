


# E-Commerce Website

This is a React project that implements an e-commerce web site. Users can browse products from a JSON file, add them to the cart, remove them from the cart, and change the quantity. The project uses React Redux for state management and JSON Server for mocking a REST API.

# Technologies Used
  - React
  - React Redux
  - JSON Server
  - Axios

# Installation and Usage

To run this project, you need to have Node.js installed on your system. You can download it from the [official website](https://nodejs.org/en/download/current).

## Clone the repository
You can clone the repository using the following command:
```bash:
git clone https://github.com/Soumen3/mini-E-Commerce-.git
```
## Start the JSON Server
To start the JSON Server, run the following command:
```bash:
json-server ./db.json -p 8080
```
This will start the server on port 8080 and serve the data from the `db.json` file.

## Start the React app
To start the React app, run the following command:
```bash
npm start
```
This will start the app on port 3000 and open it in your browser.
# Folder Sructure
```kotlin
mini-e-commerce-/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── app/
│   │   └── store.js
│   │   └── ...
│   ├── features/
|   |   └── cart/
|   |   |   └── Cart.jsx
|   |   |   └── cartAPI.js
|   |   |   └── cartSlice.js
|   |   |   └── Cart.css
|   |   └── products/
|   |   |   └── Products.jsx
|   |   |   └── productsAPI.js
|   |   |   └── productsSlice.js
|   |   |   └── Product.css
│   ├── App.js
│   ├── index.js
│   └── ...
│
├── db.json
├── package.json
└── ...
```
# Features
The project has the following features:
 + Home page: Displays a list of products with their name, price, and image. Users can click on a product to view its details or add it to the cart.
 + Product details page: Displays the details of a selected product, such as its description, rating, and reviews. Users can also add the product to the cart or go back to the home page.
 + Cart page: Displays the items in the cart with their name, price, quantity, and total. Users can change the quantity of an item, remove an item from the cart, or clear the entire cart. Users can also proceed to checkout or go back to the home page.

# Contributing
If you want to contribute to this project, you can follow these steps:
+ Fork the repository
+ Create a new branch for your feature or bug fix
+ Make your changes and commit them with a descriptive message
+ Push your branch to your forked repository
+ Create a pull request to the original repository
+ Wait for your pull request to be reviewed and merged




# Getting Started with Create React App and Redux

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

