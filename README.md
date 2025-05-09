# airbnb-clone-project
## Overview
This is a project to enhance backend knowledge by building an Airbnb clone
Python and Django will be the main tools to build this project
This project aims to improve:
Database Design 
Api Design and Security 
CI/CD pipeline Integration 
Team Development 

## Team Roles
Frontend Developer: Develops the frontend UI using React
Backend Developers: Focuses on building the core logic, database design and api development
Database Administrators: Define relational database architecture for optimal data storage
Product Manager: Define goals, features and overall system reliability

## Technology Stack

  Python is a programming language for building projects
  Django is a Python framework used for building web apps and REST APIS
  Postgresql is A database management software for managing the database 
  Redis to cache frequent queries 
  Stripe/PayPal for secure payment processing
  Docker for consistent deployments across development and production environments
  Git/Github is a version control software and system that aids in code collaboration and history tracking
    
## DATABASE DESIGN

 A user table to store details such as guests and hosts. A user can have multiple listings
 A listing table to define properties available for booking. Multiple users can book a listing 
 A bookings Table to track reservations made by guests. A user can make multiple listings
 Reviews Table to store user-generated feedback on a listing. A user can leave multiple reviews
 The payments table is used to handle and record transactions. Each booking has one payment record
     
## Feature Breakdown

User authentication for secure login and signup
Property Listing: To create and manage property listings with search and filter functionality
Booking System and Payments for real-time booking availability and scheduling
Reviews and Ratings: Guests can leave reviews and ratings for properties

## API Security

    Authentication will be needed to ensure that only legitimate users can access the system
    Using Django's built-in authentication for login and logout views
    Using user models to handle and manage accounts
    Using the Rest framework permissions, certain endpoints can be restricted for authorisation
    API security will be important to protect user-sensitive data
    It also ensures that we implement authentication to avoid unauthorised access and control
    It will safeguard payment transactions by preventing fraudulent transactions
## CI/CD Pipeline

CI/CD are essential because it automates testing, development and integration
Each time a booking is up, CI will be needed to run tests and ensure changes don't break existing functionality
CD will be needed to ensure that new features are shipped faster
    TOOLS:
            Github Actions to automate testing and deployment within Github
            Docker and Kubernetes for Containerization and Deployment
            Pytest and Django Test Framework for unit testing automation
    
