# 🖥️ Codian Collab

A **real-time, web-based** collaborative code editor that allows multiple users to code together in the same environment. The platform enables developers to **write, edit, and execute** code collaboratively with seamless communication.


## 📝 Overview
A full-stack web application that allows multiple users to write, edit, and run code simultaneously in real-time (similar to Google Docs for code).

### 🛠 Tech Stack
- **Backend:** Python (Flask), Socket.io
- **Frontend:** HTML, CSS, JavaScript
- **Networking:** WebSockets (Bi-directional communication)

### ✨ Key Features
- **Real-Time Sync:** Code updates instantly across all connected users using WebSockets.
- **Concurrency Handling:** Manages multiple users typing simultaneously without conflicts.
- **Lightweight Architecture:** Replaces heavy HTTP requests with persistent connections.


## 🚀 Getting Started
### 🔹 Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Kishordwngn/Real-Time-Collaborative-IDE.git
   cd Codian Collab
   ```
2. Create a virtual Environment:
   ```bash
    source venv/bin/activate    
   ```

3. Run:
   ```bash
   python app.py 
   ```

4. Open the app in your browser:
   ```
   http://localhost:5000
   # or replace "privateip" with your private IP address (e.g., 191.168.1.1)
   http://privateip:5000
   ```



