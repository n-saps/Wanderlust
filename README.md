# Wanderlust

Wanderlust is a full-stack web application inspired by Airbnb that enables users to discover, create, and manage property listings. The platform allows users to share accommodations, explore listings posted by others, and interact through reviews.
This project demonstrates a complete end-to-end web development workflow, including backend API design, database integration, authentication, and dynamic frontend rendering. It follows a structured MVC architecture and reflects real-world application design principles.

## Key Features
1. Listings Management
   - Create, edit, and delete property listings
View detailed information for each listing
Store listing data in a structured database

## Tech Stack
- Frontend: EJS (Embedded JavaScript templates), HTML5, CSS3
- Backend: Node.js, Express.js (Inferred from standard routing and server.js)
- Database: MongoDB / Mongoose (Inferred from the models/ and schema.js directory)
- Cloud Services: Cloudinary (For handling image assets)

## Project Structure
This repository contains several files and directories that supports a standard Model-View-Controller (MVC) architecture:
Directories
- controllers/: Contains the core logic for handling incoming requests and returning responses.
- models/: Defines the database schemas and models for the application's data.
- views/: Contains the EJS templates that generate the UI the user interacts with.
- routes/: Houses the routing files that map URLs to their corresponding controllers.
- public/: Stores static assets such as custom CSS files, images, and client-side JavaScript.
- utils/: Contains reusable helper functions and error-handling utilities.
- init/: Includes initialization scripts, likely used to seed the database with initial data.
  
Key Files
- server.js: The main entry point that starts the server.
- cloudConfig.js: Contains the configuration settings to connect the app with Cloudinary for image uploads.
- middleware.js: Custom middleware functions, typically used for authentication, authorization, or request validation.
- schema.js: Likely contains server-side validation schemas to ensure incoming data is formatted correctly before hitting the database.
- package.json & package-lock.json: Keeps track of all project dependencies and their specific versions.
- .gitignore: Tells Git which files to ignore.

## Getting Started
- Before you begin, ensure you have the following installed on your local machine:
1. Node.js (v14 or higher)
2. MongoDB (Local or Atlas setup)
3. A Cloudinary account for image uploads.
- Installation
1. Clone the repository:
2. Install all dependencies defined in the package.json:
3. Set up Environment Variables: Create a .env file in the root directory. You will need to add your specific cloud configurations and database credentials:
4. Initialize the Database: Run the initialization script to populate the database with sample data.
5. Start the Application: Run the main server file:
6. The application should now be running. Check your terminal for the port number (usually http://localhost:3000 or 8080).
