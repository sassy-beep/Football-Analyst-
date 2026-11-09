# Football-Analyst-
project using database management system 
## 🚀 Features
- **Dashboard:** Overview of teams, players, matches, goals, and top scorers.
- **Player Analytics:** Track goals, assists, xG, xA, ratings, shots, and other performance metrics.
- **Player Comparison:** Compare players using season statistics and per-90-minute metrics.
- **Data Management:** Add, update, and delete players, matches, and player statistics.
- **SQL Lab:** Explore SQL concepts including JOIN, GROUP BY, HAVING, subqueries, views, and transactions.
- **Database Design:** Primary keys, foreign keys, constraints, indexes, triggers, and stored procedures.

## 🛠️ Tech Stack
| Technology | Purpose |
|---|---|
| React 18 + Vite | Frontend |
| CSS + Lucide Icons | UI Design |
| Node.js + Express | Backend API |
| MySQL 8.0+ | Database |
| mysql2 | Database Connectivity |

## 📂 Project Structure
```text
FootballIQ/
├── database.sql
├── README.md
├── ER_DIAGRAM.md
├── backend/
│   ├── .env.example
│   ├── package.json
│   └── src/
└── frontend/
    ├── index.html
    ├── package.json
    └── src/
```

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd FootballIQ
```

### 2. Setup MySQL Database
- Open MySQL Workbench.
- Execute `database.sql`.
- This creates the FootballIQ database, tables, and sample records.

### 3. Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file using `.env.example` and configure your MySQL credentials.

```bash
npm run dev
```

Backend runs at `http://localhost:5000`.

### 4. Setup Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the Vite URL (typically `http://localhost:5173`).

## 📊 Database Concepts Implemented

- Relational Database Design
- Primary & Foreign Keys
- SQL Joins and Aggregate Functions
- Subqueries and Views
- Stored Procedures
- Triggers and Constraints
- Database Indexing
- Transactions and Query Optimization

To demonstrate practical DBMS concepts through a football analytics application with an interactive frontend, REST API, and relational MySQL database.
