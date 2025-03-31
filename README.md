# Finance Tracker

## 🚀 Overview
Finance Tracker is a full-stack web application that allows users to track their expenses, categorize spending, and gain insights into their financial habits. Built with **React (Vite) for the frontend**, **FastAPI for the backend**, and **PostgreSQL for data storage**, this app ensures a smooth and efficient experience.

## 🛠️ Tech Stack
- **Frontend:** React (Vite) + Tailwind CSS
- **Backend:** FastAPI (Python) + SQLAlchemy
- **Database:** PostgreSQL
- **Authentication:** JWT-based authentication
- **Hosting (Optional):** Vercel (Frontend), Render/Fly.io (Backend & DB)

## ✨ Features
- 🔐 **User Authentication** (Register/Login with JWT)
- 📊 **Expense Tracking** (Add, Edit, Delete expenses)
- 🏷️ **Category-based Expense Filtering**
- 📈 **Spending Insights** (Charts & Graphs)
- 📂 **Export Reports** (Download expenses in CSV format)

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Monametsi-s/finance-tracker.git
cd finance-tracker
```

### 2️⃣ Backend Setup (FastAPI)
#### Install dependencies:
```sh
cd backend
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

#### Set up environment variables:
Create a `.env` file in the backend directory and add:
```
DATABASE_URL=postgresql://username:password@localhost/finance_tracker
SECRET_KEY=your_jwt_secret
```

#### Run migrations:
```sh
alembic upgrade head
```

#### Start FastAPI server:
```sh
uvicorn main:app --reload
```

### 3️⃣ Frontend Setup (React)
#### Install dependencies:
```sh
cd frontend
npm install
```

#### Start the frontend server:
```sh
npm run dev
```

### 4️⃣ Access the App
- **Backend API Docs:** `http://localhost:8000/docs`
- **Frontend:** `http://localhost:5173`

## 📌 API Endpoints
| Method | Endpoint            | Description         |
|--------|--------------------|---------------------|
| POST   | `/auth/register`   | Register a new user |
| POST   | `/auth/login`      | Login and get token |
| GET    | `/expenses`        | Get all expenses |
| POST   | `/expenses`        | Add new expense |
| PUT    | `/expenses/{id}`   | Update an expense |
| DELETE | `/expenses/{id}`   | Delete an expense |

## 🎯 To-Do List
- [ ] Add Income Tracking
- [ ] Implement Recurring Expenses Feature
- [ ] Multi-Currency Support
- [ ] Dark Mode

## 🤝 Contributing
Feel free to submit issues and pull requests! 🚀

## 📜 License
This project is licensed under the MIT License.

