# apexride
ApexRide is a car modification parts store website focused on displaying automotive tuning accessories for modern vehicles.
# ApexRide - Car Modification Store (Assignment 02)

## Project Overview
This is a dynamic web application built for car enthusiasts to manage and explore car modification parts.

## Features
- **Full CRUD:** Add, Edit, Delete, and View products.
- **Advanced Filtering:** Search by name, filter by category, price, and rating.
- **Persistent Theme:** Dark/Light mode toggle that stays active across all pages using LocalStorage.
- **Responsive UI:** Fully responsive design using Tailwind CSS.

## Array Methods Implemented
1. `map()` - To render product cards.
2. `filter()` - For searching and deleting products.
3. `reduce()` - To calculate average price and ratings in stats.
4. `sort()` - To sort products by price and rating.
5. `find()` - To locate a product for editing.
6. `every()` - To validate data integrity.
7. `some()` - To check for premium products.
8. `push()` - To add new products.

## String Methods Implemented
1. `trim()` 2. `toUpperCase()` 3. `substring()` 4. `concat()` 5. `includes()` 
6. `replace()` 7. `split()` 8. `join()` 9. `charAt()` 10. `indexOf()`

## Folder Structure
- `/index.html` (Home Page)
- `/src/pages/` (About, Products, Contact, Auth)
- `/src/constants/themeConstants.js` (Global Theme Logic)
- `/src/pages/products/products-logic.js` (CRUD & Filter Logic)
