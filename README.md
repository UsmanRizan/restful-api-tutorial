
# 🎬 Express Movies API

A simple RESTful API built with Express.js that allows you to manage a list of movies.

## 🚀 Features

- View all movies (`GET /movies`)
- View a specific movie (`GET /movies/:id`)
- Add a new movie (`POST /movies`)
- Update a movie (`PUT /movies/:id`)
- Delete a movie (`DELETE /movies/:id`)
- Input validation middleware

## 📦 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/express-movies-api.git
   cd express-movies-api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server.js
   ```

4. Server runs on:
   ```
   http://localhost:8000
   ```

## 🛠 Example Movie JSON

```json
{
  "title": "Inception",
  "genre": "Sci-Fi",
  "year": 2010
}
```

## 📬 API Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | `/movies`        | Get all movies           |
| GET    | `/movies/:id`    | Get a movie by ID        |
| POST   | `/movies`        | Add a new movie          |
| PUT    | `/movies/:id`    | Update a movie           |
| DELETE | `/movies/:id`    | Delete a movie           |

## 🧾 License

MIT

---

Made with ❤️ using Node.js + Express
