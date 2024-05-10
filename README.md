## Introduction
It is an e-commerce project that allows users to explore and purchase a wide range of products.

The project is built using ReactJS and employs state management through Context API. 

## Features

### Product List Page
The home page serves as the entry point to the application and displays a list of all available products. The page includes a dropdown filtering menu that allows users to filter products by category.
### Product Detail Page
Clicking on the "Discover Now" button on any product card redirects users to the product detail page. Here, users can view detailed information about the selected product. Additionally, a "Add to Basket" button is available to add the product to the user's shopping basket.
### Shopping Basket
The shopping basket can be accessed by clicking on the basket icon in the navigation bar. This page displays a list of selected products in the basket. Each product card includes "Remove" and "Add" buttons, allowing users to decrease or increase the quantity of a particular item. The changes in quantity are reflected in the count displayed on the basket icon in the navigation bar.
### Order Summary
Alongside the product listing in the basket page, an order summary card is provided. This card displays the names, category icons, and counts of the products in the basket. The prices of each item are multiplied by their respective counts to show the total price for each product. At the bottom, the total price of all products in the basket is calculated and displayed.


## Installation

To run the this project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/bsrakts/adolfha-ecommerce.git
```


2. Change to the project directory:

```bash
cd FakeStore-Project
``` 

3. Install the dependencies:

```bash
npm install
``` 

4. To start the development server and run the project, execute the following command:

```bash
npm start
``` 

This will start the application on your local machine, and you can access it in your web browser at http://localhost:3000.

    
## Dependencies

This project relies on the following dependencies:

- React: A JavaScript library for building user interfaces.
   ##### (https://react.dev/)
- React Router DOM: A library for routing in React applications. 
   ##### (https://reactrouter.com/en/main)
- FakeStoreAPI: A mock API used to fetch product data.
  ##### (https://fakestoreapi.com/docs)
