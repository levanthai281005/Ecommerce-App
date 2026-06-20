# E-Commerce Shopping App

## Project Overview

This project is a simple E-Commerce Shopping Application built with modern mobile development technologies. The application allows users to browse products, add items to a shopping cart, manage their cart, and complete a checkout process. Product data is retrieved from an external API, providing a realistic online shopping experience.

## Features

### Product Listing

- Display a list of products fetched from an external API (such as FakeStoreAPI or MockAPI).
- Show product image, name, and price.
- Allow users to add products to the shopping cart.
- Support product search and filtering by name or category.
- Handle loading and error states while fetching data.

### Product Details

- View detailed information about a selected product.
- Display product image, title, description, category, price, and rating.
- Allow users to add the product to the shopping cart directly from the detail page.

### Shopping Cart

- View all products added to the cart.
- Display product name, price, quantity, and subtotal.
- Increase or decrease product quantity.
- Remove products from the cart.
- Calculate and display the total cost of the order.

### Checkout

- Complete a checkout form with:
  - Full Name
  - Email Address
  - Shipping Address

- Validate all input fields before submission.
- Ensure the email format is valid.
- Display an order confirmation message with customer and order information after successful submission.

### User Authentication

- Implement user authentication using a mock authentication API or Firebase Authentication.
- Allow users to sign in before accessing protected features.

### API Integration

- Fetch product data from an external API.
- Manage loading indicators while data is being retrieved.
- Handle API errors gracefully and provide feedback to users.

### Responsive User Interface

- Create a clean and modern e-commerce user interface.
- Optimize the application for both smartphones and tablets.
- Provide an intuitive shopping experience with easy navigation.

## Technologies

- React Native / Expo
- NodeJS / Express
- TypeScript
- React Navigation or Expo Router
- Axios
- Context API / Redux Toolkit (for cart management)
- Firebase Authentication (optional)

## Learning Objectives

- Working with REST APIs
- State management in React Native
- Form validation and user input handling
- Navigation between multiple screens
- Building responsive mobile user interfaces
- Implementing authentication and shopping cart functionality
