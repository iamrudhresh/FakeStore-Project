# Single-Page E-Commerce Application
This project is an SPA developed with React and React Router, facilitating product browsing, details viewing, and shopping cart management via the Fake Store API. With concise component design and efficient routing, it provides users a seamless experience for exploring and purchasing products.

## Technologies Used
- React
- React Router
- Tailwind CSS (for styling)

## Features Implemented

### 1. Fetch Product Data
- Utilized Axios to fetch product data from the provided API endpoint.

### 2. Display Products
- Created components to display products in a grid format.
- Each product component includes relevant information such as name, price, and image.

### 3. Pagination or Infinite Scrolling
- Implemented infinite scrolling to load products dynamically as the user scrolls.
- Enhanced user experience and performance for large product catalogs.

### 4. Product Details Page
- Developed a separate product details page/component to display comprehensive information about each product.
- Includes details like description, specifications, and reviews.

### 5. Shopping Cart Functionality
- Implemented a shopping cart component that allows users to add and remove products.
- Utilized React state management to maintain the cart state across components.

### 6. Search Functionality
- Implemented a search component that enables users to search for products by name or description.
- Product list filters dynamically based on the search query entered by the user.


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

# Project Directory Structure
public/ <br>
├── index.html <br>
├── manifest.json <br>
└── robots.txt <br> 
src/ <br>
├── components/ <br>
│   ├── Cart.js <br>
│   ├── Item.js <br>
│   ├── LoadingScreen.js <br>
│   └── Navbar.jsx <br>
├── helpers/ <br>
│   └── apiClient.js  <br>
├── pages/ <br>
│   ├── Details.jsx <br>
│   ├── Home.jsx <br>
├── App.css <br>
├── App.js <br>
├── App.test.js <br>
├── index.css <br>
├── index.js <br>
├── logo.svg <br>
├── reportWebVitals.js <br>
└── setupTests.js <br>

    
## Dependencies

This project relies on the following dependencies:

- React: A JavaScript library for building user interfaces.
   ##### (https://react.dev/)
- React Router DOM: A library for routing in React applications. 
   ##### (https://reactrouter.com/en/main)
- FakeStoreAPI: A mock API used to fetch product data.
  ##### (https://fakestoreapi.com/docs)
