# 🎬 Go_Movie API

A simple RESTful API built with Go using the `gorilla/mux` router. This project implements basic **CRUD operations** for managing a list of movies.

## 🚀 Features

- 📥 Create a new movie
- 📄 Read all movies or a specific one
- 📝 Update existing movie details
- ❌ Delete a movie

## 📦 Tech Stack

- [Go](https://golang.org/)
- [gorilla/mux](https://github.com/gorilla/mux) for routing


## ▶️ Getting Started

1. Clone the repo  
   `git clone https://github.com/your-username/go-movies-api.git`

2. Navigate to the project  
   `cd go-movies-api`

3. Run the server  
   `go run main.go`

The server will start at `http://localhost:8080`

---

## 📫 API Endpoints

| Method | Endpoint        | Description            |
|--------|-----------------|------------------------|
| GET    | `/movies`       | Get all movies         |
| GET    | `/movies/{id}`  | Get a movie by ID      |
| POST   | `/movies`       | Create a new movie     |
| PUT    | `/movies/{id}`  | Update a movie by ID   |
| DELETE | `/movies/{id}`  | Delete a movie by ID   |

