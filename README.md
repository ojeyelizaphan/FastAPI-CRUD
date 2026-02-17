
---

# FastAPI-CRUD

A simple full-stack CRUD application for managing products.

Built with:

* Backend: FastAPI + SQLAlchemy
* Database: SQLite
* Frontend: React

---

## Project Structure

```
FastAPI-CRUD/
│
├── backend/
│   ├── main.py
│   ├── models.py
│   ├── database.py
│   └── schemas.py
│
├── frontend/
│   ├── src/
│   └── package.json
│
└── README.md
```

---

## Backend Setup

1. Create virtual environment:

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

2. Install dependencies:

```bash
pip install fastapi uvicorn sqlalchemy
```

3. Run the server:

```bash
uvicorn main:app --reload
```

Backend runs at:

```
http://127.0.0.1:8000
```

API docs:

```
http://127.0.0.1:8000/docs
```

SQLite database (`test.db`) is auto-created on first run.

---

## Frontend Setup

Inside the `frontend` folder:

```bash
npm install
npm start
```

Frontend runs at:

```
http://localhost:3000
```

---

## API Endpoints

* `POST /products` — Create product
* `GET /products` — Get all products
* `GET /products/{id}` — Get single product
* `PUT /products/{id}` — Update product
* `DELETE /products/{id}` — Delete product

---

## Key Concepts

* RESTful API design
* Dependency injection
* SQLAlchemy ORM
* CORS configuration
* Full-stack integration (React + FastAPI)

---

## Author

Jabuya Ojey

---

