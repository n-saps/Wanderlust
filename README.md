# Wanderlust

Wanderlust is a robust, dynamic web application designed as a clone of Airbnb. It allows users to browse, create, and manage property listings. The application is built using a modern JavaScript stack, 
leveraging server-side rendering to deliver a fast and responsive user experience.

## Key Features
Wanderlust supports the following core functionalities:
1. Property Management (CRUD): Users can Create, Read, Update, and Delete property listings seamlessly.
2. Cloud Media Storage: Fully integrated with Cloudinary for secure, optimized image uploads and storage.
3. Middleware & Security: Custom middleware functions restrict unauthorized access and protect specific routes (e.g., only allowing owners to edit their listings).
4. Data Validation: Server-side validation using predefined schemas ensures that only clean and correctly formatted data reaches the database.
5. Dynamic Templating: Utilizes Embedded JavaScript (EJS)to generate dynamic, data-driven HTML pages injected with custom CSS styling.

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
- Prerequisites
Before you begin, ensure you have the following installed on your local machine:
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
