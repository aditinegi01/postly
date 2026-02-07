📸 Postly — Image Sharing & Feed Platform
Postly is a full-stack image sharing application that allows users to securely authenticate, upload images with descriptions, view a public feed, and manage their posts.
The project focuses on clean backend architecture, secure cloud storage, and a simple interactive UI.

✨ Key Highlights
Secure user authentication (Sign up / Login / Logout)
Image upload with description
Public feed to view posts
Users can delete their own posts
Cloud-based image storage
Clean RESTful API design
Lightweight interactive frontend

🧠 Tech Stack
Backend
Python
FastAPI (High-performance REST APIs)
SQLAlchemy ORM
SQLite database
Uvicorn ASGI server

Frontend
Streamlit (Interactive UI)

Cloud & Tools
ImageKit.io (Cloud image storage)
python-dotenv (Environment variable management)

## 📁 Project Structure

postly/
│
├── app/
│ ├── init.py
│ ├── app.py # FastAPI app setup
│ ├── db.py # Database configuration
│ ├── users.py # Authentication logic
│ ├── images.py # Image upload & feed APIs
│ └── schemas.py # Pydantic schemas
│
├── frontend.py # Streamlit frontend
├── main.py # Application entry point
├── test.db # SQLite database
├── .env # Environment variables
├── pyproject.toml # Dependencies & project config
└── README.md
