# E-COMMERS
This project is a feature-rich e-commerce application built using React.js. The project includes features like product listing, search with auto-suggestion, filters, sorting, lazy loading, product detail page, and a checkout page. The Redux toolkit is used for state management, and Tailwind CSS or Bootstrap is used for responsive design.
Features
User Registration: Allows users to register and create an account.
Product Listing: Displays products with a "load more" functionality to fetch new data from the faketstore API.
Search with Auto-Suggestion: Provides search suggestions and cached results for faster searches.
Filters: Includes filters for size, color, brand, and category.
Sorting: Supports sorting by price and popularity in ascending and descending order.
Product Detail Page: Displays detailed information about a product.
Checkout Page: Allows users to review their cart and proceed to checkout.


Technologies Used
React.js: For building the user interface.
Redux Toolkit: For state management.
Tailwind CSS/Bootstrap: For responsive design and styling.
JSON Server: For backend development

Installation
git clone https://github.com/your-username/e-commerce-project.git
cd e-commerce-project
npm install

Run the JSON Server:
json-server --watch db.json --port 8000

To Start The development server
npm start


#BackEnd
Set up JSON Server:
Create a db.json file in the root of your project. This file will act as your mock database:
{
  "users": [],
}
Run the JSON Server:npx json-server --watch db.json --port 5000
Start the development server:npm start


Project Structure
public/: Contains public assets like the index.html file and icons.
src/: Contains the main source code for the application.
components/: Contains React components.
contexts/: Contains context providers and state management.
reducers/: Contains Redux reducers and actions.
styles/: Contains CSS and styling files.
App.js: Main application component.
index.js: Entry point for the React application.
Context Data
The Contextdata context is used to manage the state for:

Products
Displayed products
Active category
Sort order
Current page
Pagination
It includes functions for loading more products and fetching data from APIs.

Additional Information
Author: Atish Chavan
Portfolio: https://portfolio-atish.netlify.app
