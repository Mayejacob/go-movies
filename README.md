# Simple Movie API with Go and Gorilla Mux

This is a simple movie API implemented in Go using the Gorilla Mux router. The API supports basic CRUD operations (Create, Read, Update, Delete) for managing a collection of movies.

## Features

- List all movies
- Retrieve details of a specific movie by ID
- Add a new movie to the collection
- Update details of an existing movie
- Delete a movie from the collection

## Dependencies

- [Gorilla Mux](https://github.com/gorilla/mux): A powerful URL router and dispatcher for golang.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Mayejacob/go-movies.git


2. **Navigate to the project directory:**

```bash
cd your-repository

3. **Run the Application**

To run the application, use the following command:

```bash
go run main.go

    The server will start on port 8000 by default.

    ## API Endpoints

    - **List all movies:** `GET /movies`
    - **Retrieve details of a specific movie:** `GET /movies/{id}`
    - **Add a new movie:** `POST /movies`
    - **Update details of an existing movie:** `PUT /movies/{id}`
    - **Delete a movie:** `DELETE /movies/{id}`

## Example Usage

### List all movies

```bash
curl http://localhost:8000/movies


curl http://localhost:8000/movies/1
