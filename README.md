# ExploreVista

Full-stack Web Application

## Screenshots of the Website

![](https://github.com/user-attachments/assets/ac54aab6-2aa4-4f40-b643-3c7a1ecf8418)

![](https://github.com/user-attachments/assets/ebfcbea5-5246-45d7-8bf1-8d3691542f43)

![](https://github.com/user-attachments/assets/ecc05686-c7b7-4304-9aec-76a8d3f0180f)

![](https://github.com/user-attachments/assets/49c103b5-628c-461e-8879-fdc030cd3e76)

![](https://github.com/user-attachments/assets/5e3b605d-e3e3-4d18-8bc7-d9ae9c772889)

## Key Features

User Authentication

Registration: New users can create an account.
Login: Existing users can log in with their credentials.
Logout: Users can log out of their account.
Session Management: Users remain logged in across sessions unless they choose to log out.
HotSpot (Travel Destination) Management

Add New HotSpot: Authenticated users can add HotSpots by providing information such as name, location, price, and description.
View HotSpots: All users can browse through a list of available HotSpots, including details and images.
Edit HotSpot: Users can update HotSpots they’ve added, modifying details like name, location, and description.
Delete HotSpot: Users can remove HotSpots they’ve added if they choose.
Reviews and Comments

Add Reviews/Comments: Users can share their experiences by posting reviews and comments on individual HotSpots.
Edit Reviews/Comments: Users can edit their own reviews and comments if needed.
Delete Reviews/Comments: Users can delete their reviews and comments.
Map Integration

Display HotSpot Locations: Each HotSpot’s location is shown on an interactive map, providing users with a geographic view of the site.
Map Interaction: Users can zoom in and out and view the exact location of each HotSpot.

## Technologies Used

Express.js: A minimal, flexible backend framework to streamline server-side development, especially useful for integrating various technologies in a full-stack application.
Express-Session: Enables effective cookie management to enhance user experience through client-server interactions.
Passport.js: Provides authentication and authorization functionalities.
MongoDB: A NoSQL database used to store information about users, HotSpots, reviews, and sessions.
Mongoose: An ORM (Object-Relational Mapping) library for seamless interaction with MongoDB.
Cloudinary: Manages and optimizes images uploaded by users, such as those associated with HotSpots.
Mapbox: Powers an interactive map that displays HotSpot locations with zoomable and cluster map features.
EJS (Embedded JavaScript Templates): A templating language used to create dynamic, server-rendered user interfaces.
Bootstrap: A CSS framework that enhances the visual appeal and responsiveness of the user interface.
Render: Used for hosting the complete application.
Website Functionality
Overview
TravelVenture is a web application that allows users to authenticate, add HotSpots, post reviews and comments, edit or delete their submissions, and view HotSpot locations on an interactive map. The application is built on a MongoDB database, storing all necessary data for users, reviews, and HotSpot details.
