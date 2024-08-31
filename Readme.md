# Mess Management System with Food Waste Management

## Overview
This project is a web-based application designed to manage a mess system efficiently while also addressing food waste management concerns. The system allows users to sign up, log in, and manage their accounts according to their roles (customer, manager, cadet). It provides features such as order management, inventory management, feedback collection, and more.

## Features
- **User Authentication**: Users can sign up and log in with their credentials. Authentication ensures secure access to the system. 
- **Role-Based Access Control**: Different roles (customer, manager, cadet) have different permissions and access levels within the system.
- **Order Management**: Customers can place orders for meals, and managers can view and manage these orders.
- **Inventory Management**: Managers can monitor and manage inventory levels, ensuring sufficient stock for meal preparation.
- **Feedback Collection**: Customers can provide feedback on the quality of meals, service, etc., helping improve the overall experience.
- **Food Waste Management**: The system includes features to track and minimize food waste. It provides insights into consumption patterns, allowing managers to optimize meal planning and reduce waste.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap (for styling)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (for storing user data, orders, inventory, etc.)
- **Authentication**: JSON Web Tokens (JWT) for user authentication
- **Email Service**: Nodemailer (for sending verification emails)
- **Environmental Variables**: dotenv (for managing sensitive information like database URIs, API keys)

## Setup
1. Clone the repository: `git clone https://github.com/SahilTwitZ/Mess-Management`
2. Install dependencies: `cd Mess-Management`
3. `npm install`
4. Set up environment variables:
  i. Create a `.env` file in the root directory.
  ii. Add the necessary environment variables, such as:
     - `MONGODB_URI`: MongoDB URI for database connection
     - `MAIL`: Email address for sending verification emails
     - `PASS`: Password or API key for email service
5. Start the server: Use the following command to start the server: `npm start`

## Access the Application
To access the application, follow these steps:
1. Open your web browser.
2. Navigate to the following URL: http://localhost:3000
(If you've configured a different port, replace 3000 with the appropriate port number.)
