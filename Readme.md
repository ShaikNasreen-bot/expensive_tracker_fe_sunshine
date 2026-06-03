# Expense Tracker — Frontend

Interactive web UI for the Expense Tracker Management System, built with **Streamlit**.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Streamlit | Frontend Web UI |
| Requests | API Communication |
| Pandas | Data Handling |
| Plotly | Interactive Charts |

---

## Features

| Feature | Description |
|---|---|
| 📊 Dashboard | KPI cards + Pie, Bar, Category charts |
| ➕ Add Expenses | Form with validation |
| 👁️ View Expenses | Full table with totals |
| ✏️ Update Expenses | Fetch by ID and edit |
| 🗑️ Delete Expenses | View table then delete by ID |
| 🔍 Search Expenses | Search by title or category |
| 🔃 Sort Expenses | Sort by any field, asc/desc |
| 🎛️ Filter Expenses | Filter by category |
| 📈 Analyze Expenses | Charts by category / payment / date |

---

## Setup

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Create secrets file

Create `.streamlit/secrets.toml`:

```toml
backend_server = "https://your-backend-url.onrender.com"
```

### 3. Run locally

```bash
streamlit run app.py
```

Frontend runs at: `http://localhost:8501`

---

## Project Architecture

```
User Browser
     ↓
Streamlit Frontend  (app.py)
     ↓  HTTP Requests
FastAPI Backend     (main.py)
     ↓  SQL Queries
MySQL Database      (expenses_db)
```

---

## Author

Your Name — Built for learning Full Stack Python Development.
