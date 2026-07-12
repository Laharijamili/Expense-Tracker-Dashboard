# Expense-Tracker-Dashboard

## 📌 Intern Details
* **Domain:** Full Stack Web Development
* **Intern ID:** CITS2364
* **Name:** Jamili Lahari
* **Duration:** 6 Weeks
* **Organization:** CodTech IT Solutions

## 🚀 Project Overview
An Expense Tracker Dashboard designed to help users monitor, analyze, and manage their personal finances. This application provides a visual representation of income and spending habits, tracks monthly budgets, and generates breakdowns by category to promote better financial habits.

## ✨ Features
* **Income & Expense Logging:** Add, edit, and delete transactions with amount, date, and description.
* **Visual Analytics:** Interactive charts (pie charts, bar graphs) displaying monthly income vs. expense distributions.
* **Category Filtering:** Group expenses automatically by tags (e.g., Food, Rent, Entertainment, Utilities).
* **Budget Tracking:** Set monthly limits and receive visual alerts when spending approaches or exceeds the budget.

## 🛠️ Tech Stack
* **Frontend:** React, Chart.js / Recharts, CSS3, JavaScript (ES6)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB

## 🏃 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Expense-Tracker-Dashboard
   ```

2. **Set up the backend:**
   ```bash
   cd backend
   npm install
   ```
   * Create a `.env` file in the `backend` folder and add your configuration:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     ```
   * Start the server:
     ```bash
     npm start
     ```

3. **Set up the frontend:**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the application:**
   * Open your browser and navigate to `http://localhost:3000`.
