
# Status Management Web Application

## Overview

The Status Management Web Application is a simple tool designed to manage statuses and transitions between them. This web-based solution provides an intuitive interface to organize and define the relationships between statuses. Key features include adding, deleting, and transitioning between statuses, as well as providing automatic classifications and API support.

### Key Features:

- **Manage Statuses:** Create, update, or delete statuses, including marking one status as "initial."
- **Define Transitions:** Establish transitions between statuses with unique names and visual indicators.
- **Automatic Classification:** Statuses are classified as "initial," "final," or "orphan."
- **Real-Time Updates:** Changes are updated in real-time without reloading.
- **API Support:** REST API endpoints to replicate all GUI functionalities.
- **Reset Configuration:** A simple reset button to clear all configuration.

## Requirements and Installation Instructions

### Prerequisites

- **Backend:** Python (>= 3.7)
- **Frontend:** Node.js (>= 14.0)
- **Database:** SQLite (default)

### Installation

#### Backend Setup

1. **Clone the Repository:**  
   ```bash
   git clone https://your-repo-url.git
   cd your-repo-folder/backend
   ```

2. **Create a Virtual Environment and Activate It:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts ctivate  # For Windows
   ```

3. **Install Dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Backend Server:**  
   ```bash
   python app.py
   ```

#### Frontend Setup

1. **Navigate to the Frontend Folder:**  
   ```bash
   cd ../frontend
   ```

2. **Install Dependencies:**  
   ```bash
   npm install
   ```

3. **Start the Frontend Development Server:**  
   ```bash
   npm start
   ```

The application will open in your browser at `http://localhost:3000`, with the backend API running on `http://localhost:5000`.

## Architecture and Technologies

### Backend

- **Framework:** Flask (Python)
- **Database:** SQLAlchemy with SQLite
- **API:** REST (Flask-RESTful)
- **Other Libraries:** Flask-CORS

### Frontend

- **Framework:** React
- **State Management:** Hooks (useState, useEffect)
- **HTTP Client:** Axios
- **Styling:** CSS-in-JS (or any alternatióm7¡¨×´óm7