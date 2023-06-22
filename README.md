
# TheEvent

TheEvent is a web engineering project that includes a frontend developed using HTML, CSS, and Bootstrap, with a backend developed using EJS, NodeJS, and MongoDB. The project implements 5 API endpoints for data handling.

## Getting Started

To get started with this project, you will need to have Node.js and MongoDB installed on your machine. Clone the repository to your local machine and run the following commands:


npm install
npm start


This will install all the necessary dependencies and start the project.

## Project Structure

The project has the following directory structure:


- public/
  - css/
  - js/
- views/
- routes/
- models/
- controllers/
- app.js


- The `public/` directory contains the CSS and JavaScript files for the frontend.
- The `views/` directory contains the EJS templates for rendering views.
- The `routes/` directory contains the API endpoints.
- The `models/` directory contains the database models.
- The `controllers/` directory contains the controller functions for each API endpoint.
- The `app.js` file is the main file that initializes the application and connects to the database.

## API Endpoints

The project implements the following API endpoints:

- `GET /`: Renders the home page.
- `GET /api/data`: Returns all the data in the database.
- `GET /api/data/:id`: Returns a specific data object based on the ID.
- `POST /api/data`: Adds a new data object to the database.
- `PUT /api/data/:id`: Updates a specific data object based on the ID.
- `DELETE /api/data/:id`: Deletes a specific data object based on the ID.

## Technologies Used

- HTML
- CSS
- Bootstrap
- EJS
- NodeJS
- MongoDB

## Contributing

Contributions to this project are welcome. If you find a bug or want to add a new feature, please create an issue or submit a pull request.
