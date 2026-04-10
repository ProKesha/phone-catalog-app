# React Phone Catalog

## Overview

React Phone Catalog is a modern e-commerce web application built with React and TypeScript. The project is designed to simulate a real online store experience, focusing on clean architecture, reusable components, and smooth user interactions.

The application allows users to browse products across multiple categories, view detailed product information, and manage their shopping experience through favorites and cart functionality. It demonstrates real-world frontend practices such as routing, state management, and working with dynamic data.

## Demo

You can view a live demo of the application here:  
👉 https://prokesha.github.io/phone-catalog-app/

## Key Features

- Product catalog for phones, tablets, and accessories  
- Product details page with image gallery and specifications  
- Sorting, filtering, and pagination via URL parameters  
- Search functionality with debouncing  
- Favorites management with persistence (localStorage)  
- Shopping cart with quantity control and total calculation  
- Responsive layout for different screen sizes  
- Error handling and loading states  
- “You may also like” product suggestions  

## Challenges

During development, several challenges were addressed:

### State Management
Managing cart and favorites with synchronization to localStorage required a clear and scalable approach using React Context.

### URL-Based State
Implementing sorting, pagination, and filtering through URL parameters (useSearchParams) to make the app shareable and consistent.

### Dynamic Product Variants
Handling product variations (color, capacity) and mapping them correctly to product IDs.

### Performance & UX
Optimizing re-renders, implementing debounced search, and ensuring smooth UI transitions.

### Error Handling
Building robust UI states for loading, empty results, and not-found pages.

## Installation & Setup

To run the project locally:

```bash
git clone https://github.com/ProKesha/phone-catalog-app.git
cd phone-catalog-app
npm install
npm start
