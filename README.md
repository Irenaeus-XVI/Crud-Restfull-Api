# Crud-Restfull-Api

This is a simple CRUD RESTful API that was built using Node.js and Express.js. It allows users to perform basic CRUD operations (Create, Read, Update, Delete) on list of persons.

## Prerequisites

Before running this application, you need to have the following installed on your local machine:

- Node.js
- Docker
- Docker Compose

## Installation and Usage

1. Clone this repository to your local machine

        git clone https://github.com/Irenaeus-XVI/Crud-Restfull-Api.git
2. Navigate to the project directory using the terminal/command prompt

        cd Crud-Restfull-Api/

3. Run `docker-compose up` to start the containers

        docker-compose up
4. Navigate to `http://localhost:3000` on your web browser to access the frontend application

## API Endpoints

This RESTful API exposes the following endpoints:

- GET /persons - Retrieves a list of all persons in the collection
- GET /persons/:id - Retrieves an person with the specified ID
- POST /persons - Creates a new person in the collection
- PUT /persons:id - Updates an existing person with the specified ID
- DELETE /persons:id - Deletes an person with the specified ID

## Technologies Used

This application was built using the following technologies:

- Node.js
- Express.js
- Docker
- Docker Compose
- Bootstrap

## Contributing

If you'd like to contribute to this project, please fork the repository and make a pull request. Alternatively, you can open an issue on the repository and we'll get back to you as soon as possible.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
