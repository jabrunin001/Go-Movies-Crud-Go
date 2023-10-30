# Go Movie API

## Description

This project is a simple RESTful API for movies, written in Go. It allows users to retrieve, create, update, and delete movie entries. The API is built using the [Gorilla Mux](https://github.com/gorilla/mux) router.

## Features

- **Get All Movies**: Retrieve a list of all movie entries.
- **Get Single Movie**: Retrieve the details of a specific movie by ID.
- **Create Movie**: Add a new movie entry.
- **Update Movie**: Update the details of an existing movie by ID.
- **Delete Movie**: Remove a movie entry by ID.

## Installation

To run this project, make sure you have Go installed on your machine.

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd <project-directory>
   ```
3. Run the application:
   ```
   go run main.go
   ```

The server will start on port 8000.

## Usage

Once the server is running, you can use the following endpoints:

- **GET /movies**: Retrieve a list of all movies.
- **GET /movies/{id}**: Retrieve a specific movie by ID.
- **POST /movies**: Add a new movie. Provide movie details in the request body.
- **PUT /movies/{id}**: Update a specific movie by ID. Provide updated movie details in the request body.
- **DELETE /movies/{id}**: Remove a specific movie by ID.

## Dependencies

- [Gorilla Mux](https://github.com/gorilla/mux): A powerful URL router and dispatcher for Go.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements

- [Gorilla Mux](https://github.com/gorilla/mux) for providing the router.
- All contributors and users of this project.

---

This README provides a basic overview of your project, how to install and run it, and how to contribute. You can customize it further to better suit your project's needs.
