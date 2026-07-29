# 🏠 Tile Gallery Platform - Mock API

A lightweight mock REST API for the **Tile Gallery Platform**, built with **JSON Server**. It provides product data for the frontend during development, enabling browsing, searching, and filtering of tile collections without a custom backend.

---

## 🚀 Live API

> Will be added after deployment.

---

## 🛠️ Tech Stack

- Node.js
- JSON Server

---

## ✨ Features

- 📦 Mock REST API for tile data
- 🔍 Supports frontend search and filtering
- ⚡ Fast local development with JSON Server
- 📄 JSON-based data storage
- 🔄 Easy to extend with additional resources

---

## 📁 Project Structure

```text
.
├── db.json
├── package.json
└── public/
    └── images/
        └── tiles/
```

---

## 📦 Installation

Clone the repository.

```bash
git clone https://github.com/golamrabbi73/assignment08-server.git
```

Navigate into the project.

```bash
cd assignment08-server
```

Install dependencies.

```bash
npm install
```

---

## ▶️ Running the Server

```bash
npm run server
```

The API will be available at:

```text
http://localhost:3004
```

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/tiles` | Get all tile products |
| GET | `/tiles/:id` | Get a single tile product |

> *(Available endpoints depend on the resources defined in `db.json`.)*

---

## 📄 Database

All mock data is stored inside:

```text
db.json
```

Images are served from:

```text
public/images/tiles/
```

---

## 🚀 Deployment

This project can be deployed using:

- Render
- Railway
- Vercel (Static + JSON Server alternative)

---

## 👨‍💻 Author

**Md. Golam Rabbe**

GitHub: https://github.com/golamrabbi73

---

## 📄 License

This project is developed for educational and portfolio purposes.
