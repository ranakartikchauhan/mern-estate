---

# Real Estate Marketplace

Welcome to Real Estate Marketplace, a full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This platform facilitates buying, selling, and renting properties.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely. Passwords are hashed and stored securely in the database.
  
- **Property Listings**: Users can list properties for sale or rent with details such as property type, location, price, amenities, and contact information.

- **Search and Filter**: Users can search for properties based on various criteria such as location, price range, property type, and amenities.

- **Property Details**: Each property listing has a detailed view showing all relevant information about the property.

- **Booking and Inquiry**: Users can book appointments to view properties or inquire about listings directly through the platform.

- **User Profiles**: Users have profiles where they can manage their property listings, view their booking history, update their information, and track their interactions with other users.

- **Responsive Design**: The application is built with responsive design principles, ensuring a seamless experience across devices.

## Technologies Used

- **Frontend**: React.js, React Router, Redux for state management, Bootstrap for styling
  
- **Backend**: Node.js, Express.js
  
- **Database**: MongoDB with Mongoose ORM
  
- **Authentication**: JSON Web Tokens (JWT)
  
- **Deployment**: The application is deployed on [Render](#) and uses MongoDB Atlas for database hosting.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository: `git clone <repository-url>`
  
2. Navigate to the project directory: `cd real-estate-marketplace`
  
3. Install dependencies: `npm install`
  
4. Create a `.env` file in the root directory and add the necessary environment variables:

    ```
    PORT=5000
    MONGODB_URI=<your-mongodb-uri>
    JWT_SECRET=<your-jwt-secret>
    ```

5. Run the development server: `npm start`

6. Navigate to `http://localhost:3000` in your web browser to view the application.

## Deployment

This project is deployed on render. You can access the live version of the application [here](#).
