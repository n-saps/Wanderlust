# Wanderlust

Wanderlust is a robust, dynamic web application designed as a clone of Airbnb. It allows users to browse, create, and manage property listings. The application is built using a modern JavaScript stack, 
leveraging server-side rendering to deliver a fast and responsive user experience.

## Key Features
Based on the application's underlying architecture
, Wanderlust supports the following core functionalities:
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

## Project Architecture
