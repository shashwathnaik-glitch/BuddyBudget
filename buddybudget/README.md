# BuddyBudget

## How to Run

### 1. Backend (Spring Boot)
The backend is a Java Spring Boot application located in the `backend` folder.

**Prerequisites:**
- Java 17+ (installed)
- VS Code Extension: `Spring Boot Extension Pack` (installed)

**How to Start:**
Option A: **Using VS Code (Recommended)**
1. Open the `backend/pom.xml` file.
2. VS Code should detect the Spring Boot project.
3. Go to the "Spring Boot Dashboard" in the side panel (Leaf icon).
4. Right-click on `buddybudget` (or `backend`) and click **Start** or **Debug**.

Option B: **Using Terminal**
1. Open a terminal in VS Code (`Ctrl+` `).
2. Navigate to the backend directory:
   ```bash
   cd buddybudget/backend
   ```
3. Run the application using Maven:
   ```bash
   mvn spring-boot:run
   ```
   *(Note: This requires Maven to be installed on your system path. If not, use Option A)*

The backend will start on **http://localhost:8080**.

### 2. Frontend (Static Web)
The frontend consists of static HTML/CSS/JS files located in the `frontend` folder.

**Prerequisites:**
- VS Code Extension: `Live Server` (installed)

**How to Start:**
1. Open `buddybudget/frontend/index.html` in VS Code.
2. Click the **"Go Live"** button in the bottom-right corner of the VS Code status bar.
   *Or, right-click inside the file editor and select "Open with Live Server".*
3. The application should open in your default browser (usually at `http://127.0.0.1:5500/buddybudget/frontend/index.html`).

## Notes
- Ensure the backend is running *before* you try to interact with any API features from the frontend.
