# ExploreVista

Full-stack Web Application

## Screenshots of the Website

![](https://github.com/user-attachments/assets/c04d6bc2-b08a-4394-8f22-62a29c3dfe5b)

![](https://github.com/user-attachments/assets/aa475636-4a66-42ce-8ffa-c419d6dd7b66)

![](https://github.com/user-attachments/assets/7184fea8-d758-4d0a-8749-26cb4574eb2a)

![](https://github.com/user-attachments/assets/294699af-7696-49e9-b70a-3c583f057945)

![](https://github.com/user-attachments/assets/e9977dd1-e664-4d70-9d5f-0243686224b8)

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
