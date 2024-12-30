# HackTrek: Vulnerable Web Application

## Overview
**HackTrek** is an interactive learning platform designed to teach security enthusiasts and professionals about common web application vulnerabilities. Built on the **MERN** stack (MongoDB, Express.js, React.js, Node.js), HackTrek offers hands-on challenges that simulate real-world security flaws, allowing users to develop and practice penetration testing skills in a controlled environment.

### Platform Challenges
- **SQL Injection**
- **Cross-Site Scripting (XSS)**
- **File Upload Vulnerabilities**
- **Weak Password Validation**
- **Admin Login Exploitation**

HackTrek also features an integrated **Chatbot** to assist users throughout the challenges, enhancing the learning experience.

---

## Prerequisites
Ensure the following software is installed before setting up HackTrek:
- **Node.js** (v14 or later)
- **MongoDB** (Local or cloud-based)
- **npm** (Node Package Manager)
- **Git** (For cloning the repository)

---

## Code Dependencies
### Backend
- **bcryptjs** – Password hashing.
- **jsonwebtoken** – Authentication through token creation and verification.
- **xss** – XSS sanitization for vulnerable endpoints.
- **multer** – File upload management.
- **dotenv** – Environment variable management.
- **body-parser** – Middleware to parse incoming request bodies.

### Frontend
- **axios** – API request handling.
- **react-router-dom** – Frontend routing.
- **Bootstrap** – UI styling and components.

Refer to the `package.json` files in the **backend** and **frontend** directories for a complete list of dependencies.

---

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/chiranthm-collab/HackTrek.git
cd HackTrek
```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the **backend** directory with the following variables:
   ```plaintext
   MONGO_URI=<your_mongo_connection_string>
   PORT=5000
   ```
4. Create an uploads folder to handle file uploads:
   ```bash
   mkdir uploads
   ```
5. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm start
   ```

---

## Features

### Challenges
- **SQL Injection** – Exploit insecure queries to bypass authentication.
- **XSS (Reflected & DOM-based)** – Inject malicious scripts and manipulate DOM.
- **File Upload Vulnerabilities** – Bypass file upload restrictions.
- **Admin Login Exploitation** – Gain unauthorized access by exploiting validation flaws.
- **Weak Password Validation** – Test and exploit weak password policies.

### Chatbot Assistant
HackTrek features a chatbot built within the MERN stack to provide:
- Step-by-step guidance on challenges.
- Educational content and solutions.

---

## Contribution
Contributions and feedback are welcome! If you encounter any issues or have suggestions for new challenges, submit them via **GitHub Issues**.

---

## License
HackTrek is licensed under the **MIT License**. Refer to the LICENSE file for full details.

---

## Happy Hacking! 🛡✨

