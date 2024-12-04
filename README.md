Github repositorylink :
 # https://github.com/Ayushgreat/ShoppyGlobe-E-commerce-Application-.git

# ShoppyGlobe
ShoppyGlobe is a basic e-commerce application built using React and Redux. The application allows users to browse a list of products, view detailed product information, add products to a shopping cart, and manage cart items. It demonstrates key concepts of modern web development such as state management, component-based architecture, data fetching, and routing. This project is also optimized with lazy loading to enhance performance.

# Features
1. Product Browsing: Users can browse through various products fetched from an API.
2. Product Details: Users can view detailed information for a selected product, including descriptions and prices.
3 .Add to Cart: Users can add products to their shopping cart directly from the product list or detail page.
4. Cart Management: Users can view, modify, and remove items from their shopping cart.
Responsive Design: The application is fully responsive and works well on different screen sizes, including desktops, tablets, and mobile devices.
5.Lazy Loading: Certain components such as the product detail, cart, and 404 pages are lazily loaded to improve the initial load performance.

# Technology Stack
Frontend Framework: React
State Management: Redux
Routing: React Router
CSS Framework: Tailwind CSS
API for Products: DummyJSON
JavaScript: ES6+
Build Tool: Vite

# Features Breakdown

# Component Structure
App: The root component that serves as the entry point of the application.
Header: Displays the navigation bar, search input, and a shopping cart icon.
ProductList: Displays a list of products fetched from an external API.
ProductItem: Represents individual products in the list with an "Add to Cart" button.
ProductDetail: Displays detailed information about a selected product based on the route.
Cart: Shows the items added to the cart, allowing users to modify quantities or remove items.
CartItem: Represents individual items within the cart.
NotFound: Displays a 404 page for unknown routes.

# Redux Integration
1. State Management: Redux is used for managing global state, especially for handling the shopping cart and search functionality.
2. Actions and Reducers: Redux actions and reducers handle adding, removing, and modifying cart items, as well as managing the search query.
3. Selectors: Redux selectors are used to retrieve specific pieces of data (e.g., cart items, search query) from the global state.

# Data Fetching
1. API: The product data is fetched from the DummyJSON API using the useEffect hook.
2. Custom Hooks: A custom hook (useFetchProducts) is used to handle fetching product data and managing loading and error states.

# Routing
1. React Router: Routing is implemented to handle navigation between the home page, product detail page, and cart page. Unknown routes are handled by a 404 page.
2. Lazy Loading: Non-essential components like the product detail and cart pages are loaded lazily using React.lazy() and Suspense to improve performance.

# Performance Optimizations
1. Code Splitting: Components are split and lazily loaded to reduce the initial bundle size.
2. Responsive Layout: Tailwind CSS is used to ensure the application is fully responsive and accessible across a variety of devices.
