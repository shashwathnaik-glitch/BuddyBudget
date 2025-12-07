# BuddyBudget 💰

> **Master Your Wealth.** Experience the art of financial clarity with BuddyBudget.

BuddyBudget is a premium finance tracking application designed to help you track expenses, set ambitious goals, and watch your savings grow. It combines powerful financial tools with gamification elements to keep you motivated.

## ✨ Features

- **💸 Comprehensive Tracking:** Log expenses and income with ease.
- **🎯 Budgets & Goals:** Manage monthly budgets and set financial goals.
- **📊 Smart Dashboard:** Get instant insights into your total savings, income, and expenses.
- **🎮 Gamification:** Maintain daily streaks, earn XP, and level up as you manage your finances.
- **🌍 Multi-Currency Support:** Seamlessly switch between USD, INR, and EUR.
- **📱 Responsive Design:** accessible on various devices.

## 🛠️ Tech Stack

- **Backend:** Java 17, Spring Boot 3.2.3, Maven
- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript, Remix Icons

## 🚀 How to Run

### 1. Backend (Spring Boot)
The backend is located in the `buddybudget/backend` folder.

**Prerequisites:**
- Java 17+
- VS Code Extension: `Spring Boot Extension Pack`

**Start the Backend:**
*   **Option A (VS Code):** Open `buddybudget/backend/pom.xml`, go to the "Spring Boot Dashboard", and click **Start**.
*   **Option B (Terminal):**
    ```bash
    cd buddybudget/backend
    mvn spring-boot:run
    ```
    *Server will start on `http://localhost:8080`*

### 2. Frontend (Static Web)
The frontend is located in the `buddybudget/frontend` folder.

**Prerequisites:**
- VS Code Extension: `Live Server`

**Start the Frontend:**
1.  Open `buddybudget/frontend/index.html`.
2.  Click **"Go Live"** in the VS Code status bar (bottom-right).
3.  The app will open in your browser (default: `http://127.0.0.1:5500`).

## ⚠️ Notes
- **Crucial:** Ensure the **backend is running first** before interacting with the frontend to ensure API calls work correctly.
