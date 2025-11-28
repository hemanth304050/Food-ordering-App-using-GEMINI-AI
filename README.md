# Food-ordering-App-using-GEMINI-AI


# DHK Foodies Delivery App 🍔🛵

DHK Foodies is a modern, single-page web application designed for Browse restaurants, ordering food, and managing user profiles. ✨ Built with React and styled with Tailwind CSS, this application offers a seamless and interactive user experience.

## ✨ Features

-   **🎬 Splash Screen**: An engaging entry point to the application.
-   **🔐 User Authentication**: Secure sign-up and login functionality with local storage for session persistence.
-   **🍽️ Restaurant Discovery**: Browse a list of restaurants with details like cuisine, address, and ratings.
-   **📖 Menu Exploration**: View detailed menus for each restaurant, categorized for easy navigation.
-   **🛒 Interactive Cart**: Add or remove items from the cart with real-time updates.
-   **🎛️ Advanced Filtering and Sorting**:
    -   Filter restaurants by dietary preferences (Veg/Non-Veg).
    -   Sort restaurants by relevance or price (low to high, high to low).
    -   Filter restaurants by food categories.
-   **🔍 Search Functionality**: A modal-based search to quickly find restaurants by name, cuisine, or address.
-   **✅ Seamless Checkout Process**:
    1.  **Cart Review**: A comprehensive view of the items in the cart.
    2.  **Address Form**: A modal to enter and submit the delivery address.
    3.  **Payment Gateway**: A mock payment modal with options for Card, UPI, and Cash on Delivery.
-   **🎉 Order Confirmation**: A summary page displayed after a successful order, showing order details and a simulated delivery status.
-   **🧾 Order History**: Logged-in users can view their past orders with details and status.
-   **👤 User Profile**: A dedicated page for users to view their account information, including username, user ID, phone number, and membership date.
-   **📱 Responsive Design**: A mobile-first design that ensures a great user experience across all devices.

## 💻 Technologies Used

-   **⚛️ React**: For building the user interface components.
-   **🎣 React Hooks**: (`useState`, `useEffect`, `useRef`) for managing component state and side effects.
-   **💨 Tailwind CSS**: For a utility-first approach to styling.
-   **🎨 Lucide Icons**: A collection of simply beautiful open-source icons.
-   **🔧 Babel**: Used for transpiling JSX into JavaScript.

## 🚀 Getting Started

To run this project locally, follow these steps:

1.  **💾 Download the HTML file**: Save the provided code as `index.html`.
2.  **🌐 Open in a browser**: Open the `index.html` file in any modern web browser.

No special installation or build steps are required as the project uses CDNs for all necessary libraries.

## 📁 File Structure

The entire application is contained within a single HTML file. Here's a breakdown of the key components and their roles:

-   `RestaurantCard`: Displays a summary of a restaurant.
-   `FoodMenuItem`: Shows a single item in a restaurant's menu.
-   `FilterSidebar`: A slide-in sidebar for applying filters to the restaurant list.
-   `RestaurantMenuPage`: Displays the full menu of a selected restaurant.
-   `CartView`: A modal that shows the items in the shopping cart.
-   `AuthModal`: A modal for user login and sign-up.
-   `DeliveryAddressModal`: A form for users to enter their delivery address.
-   `PaymentModal`: A mock payment interface.
-   `OrderConfirmation`: A page to confirm that an order has been successfully placed.
-   `ProfilePage`: Displays the logged-in user's profile information.
-   `SearchModal`: A modal for searching through the list of restaurants.
-   `SplashScreen`: The initial loading screen.
-   `App`: The main component that manages the overall state and renders all other components.

## 🤖 Deployment

This project was deployed by Gemini AI.
## link --> https://dhkfoodies.netlify.app/
