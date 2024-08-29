# EAT24 Food Delivery Project

EAT24 is a comprehensive food delivery application that caters to the needs of first-year college students at VIT, providing a seamless and convenient way to order and enjoy meals without leaving the hostel. Built with a MERN stack (MongoDB, Express.js, React.js, Node.js), this project includes advanced features such as real-time location tracking and secure payment services.

## Problem Statement
First-year students at VIT are not allowed to go outside the campus without permission. Ordering food requires them to travel to the main gate, which incurs a cost of 20 rupees for a round trip. This process is both time-consuming and costly. Additionally, food often loses its warmth during this trip. To address these issues, we developed the EAT24 food delivery app to bring food directly to the students' hostels, allowing them to pick up their orders conveniently.

## Website link
https://eat24.onrender.com/

[![React](https://img.shields.io/badge/React-17.0+-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-14.x-brightgreen?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.x-green?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4.x-green?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1C?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Features

1. **User Authentication:**
   - Users can create accounts, log in, and securely authenticate their identity.
   - Authentication ensures a personalized experience and order history for each user.

2. **Add Food Items to Cart:**
   - Users can browse a variety of food items and add them to their shopping cart.
   - Cart functionality allows users to review and modify their selected items before placing an order.

3. **Food Ordering:**
   - Seamless and intuitive food ordering process for users.
   - Confirmation messages and order status updates keep users informed about the progress of their orders.

4. **MongoDB Database:**
   - The project is linked with a MongoDB database for efficient and reliable data storage.
   - User details, food items, and order information are securely stored and retrieved from the database.
5. **Secure Payment Services:**
   - Integrated payment services for secure transactions.
   - Supports multiple payment methods for user convenience.
6. **MongoDB Database:**
   - Efficient and reliable data storage with MongoDB.
   - Securely stores user details, food items, and order information.

# Unique Value Proposition
EAT24 stands out in the market by addressing specific challenges faced by first-year students at VIT. Unlike other food delivery apps, EAT24:

1. **Solves the Problem of Campus Restrictions:** Students cannot leave the campus without permission, making it challenging to get food. EAT24 delivers directly to their hostels, eliminating the need for bus rides and reducing the cost and time associated with food retrieval.
2. **Maintains Food Quality:** By delivering food directly to hostels, EAT24 ensures that food remains hot and fresh, addressing the issue of food losing its warmth during transportation.
3. **Provides Real-Time Updates:** Our app offers real-time location tracking and delivery updates, enhancing the user experience and ensuring transparency throughout the delivery process.
4. **Integrates Secure Payment Options:** EAT24 incorporates secure payment services, allowing users to make payments safely and conveniently within the app.
   
### Prerequisites
- Node.js and npm installed
- MongoDB installed and running
  
## Folder Structure
```bash
|-- EAT24
     |-- .gitignore
     |-- directoryList.md
     |-- package-lock.json
     |-- package.json
     |-- README.md
     |-- backend
     |   |-- .gitignore
     |   |-- jsconfig.json
     |   |-- package-lock.json
     |   |-- package.json
     |   |-- src
     |       |-- data.js
     |       |-- server.js
     |       |-- config
     |       |   |-- database.config.js
     |       |-- constants
     |       |   |-- httpStatus.js
     |       |   |-- orderStatus.js
     |       |-- middleware
     |       |   |-- auth.mid.js
     |       |-- models
     |       |   |-- food.model.js
     |       |   |-- order.model.js
     |       |   |-- user.model.js
     |       |-- routers
     |           |-- food.router.js
     |           |-- order.router.js
     |           |-- user.router.js
     |-- frontend
         |-- .gitignore
         |-- jsconfig.json
         |-- package-lock.json
         |-- package.json
         |-- README.md
         |-- public
         |   |-- favicon.ico
         |   |-- index.html
         |   |-- layers-2x.png
         |   |-- layers.png
         |   |-- loading.svg
         |   |-- logo192.png
         |   |-- logo512.png
         |   |-- manifest.json
         |   |-- marker-icon-2x.png
         |   |-- marker-icon.png
         |   |-- marker-shadow.png
         |   |-- robots.txt
         |   |-- star-empty.svg
         |   |-- star-full.svg
         |   |-- star-half.svg
         |   |-- foods
         |   |   |-- food-1.jpg
         |   |   |-- food-2.jpg
         |   |   |-- food-3.jpg
         |   |   |-- food-4.jpg
         |   |   |-- food-5.jpg
         |   |   |-- food-6.jpg
         |   |-- icons
         |       |-- foods.svg
         |       |-- orders.svg
         |       |-- profile.svg
         |       |-- users.svg
         |-- src
             |-- App.js
             |-- AppRoutes.js
             |-- axiosConfig.js
             |-- index.css
             |-- index.js
             |-- reportWebVitals.js
             |-- components
             |   |-- AuthRoute
             |   |   |-- AuthRoute.js
             |   |-- Button
             |   |   |-- Button.js
             |   |   |-- button.module.css
             |   |-- ChangePassword
             |   |   |-- ChangePassword.js
             |   |-- DateTime
             |   |   |-- DateTime.js
             |   |-- Header
             |   |   |-- Header.js
             |   |   |-- header.module.css
             |   |-- Input
             |   |   |-- Input.js
             |   |   |-- input.module.css
             |   |-- InputContainer
             |   |   |-- InputContainer.js
             |   |   |-- inputContainer.module.css
             |   |-- Loading
             |   |   |-- Loading.js
             |   |   |-- loading.module.css
             |   |-- Map
             |   |   |-- Map.js
             |   |   |-- map.module.css
             |   |-- NotFound
             |   |   |-- NotFound.js
             |   |   |-- notFound.module.css
             |   |-- OrderItemsList
             |   |   |-- OrderItemsList.js
             |   |   |-- orderItemsList.module.css
             |   |-- PaypalButtons
             |   |   |-- PaypalButtons.js
             |   |-- Price
             |   |   |-- Price.js
             |   |-- Search
             |   |   |-- Search.js
             |   |   |-- search.module.css
             |   |-- StarRating
             |   |   |-- StarRating.js
             |   |   |-- starRating.module.css
             |   |-- Tags
             |   |   |-- Tags.js
             |   |   |-- tags.module.css
             |   |-- Thumbnails
             |   |   |-- Thumbnails.js
             |   |   |-- thumbnails.module.css
             |   |-- Title
             |       |-- Title.js
             |       |-- title.module.css
             |-- hooks
             |   |-- useAuth.js
             |   |-- useCart.js
             |   |-- useLoading.js
             |-- interceptors
             |   |-- authInterceptor.js
             |   |-- loadingInterceptor.js
             |-- pages
             |   |-- Cart
             |   |   |-- CartPage.js
             |   |   |-- cartPage.module.css
             |   |-- Checkout
             |   |   |-- CheckoutPage.js
             |   |   |-- checkoutPage.module.css
             |   |-- Dashboard
             |   |   |-- Dashboard.js
             |   |   |-- dashboard.module.css
             |   |-- Food
             |   |   |-- FoodPage.js
             |   |   |-- foodPage.module.css
             |   |-- Home
             |   |   |-- HomePage.js
             |   |-- Login
             |   |   |-- LoginPage.js
             |   |   |-- loginPage.module.css
             |   |-- Orders
             |   |   |-- OrdersPage.js
             |   |   |-- ordersPage.module.css
             |   |-- OrderTrack
             |   |   |-- OrderTrackPage.js
             |   |   |-- orderTrackPage.module.css
             |   |-- Payment
             |   |   |-- PaymentPage.js
             |   |   |-- paymentPage.module.css
             |   |-- Profile
             |   |   |-- ProfilePage.js
             |   |   |-- profilePage.module.css
             |   |-- Register
             |       |-- RegisterPage.js
             |       |-- registerPage.module.css
             |-- services
                 |-- foodService.js
                 |-- orderService.js
                 |-- userService.js
 ```

# ScreenShots:

![Alt text](C:\Users\m.pavan ganesh\Desktop\projects\eat24\EAT24\ScreenShots\food_review.png?raw=true "Food Review") 

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/EAT24.git
   cd EAT24
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB:
   - Configure your MongoDB connection in `config/database.js`.

4. Start the application:
   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:5500` to access EAT24.
