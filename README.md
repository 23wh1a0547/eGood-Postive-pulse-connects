# eGood Positive Pulse Connects

A full-stack real-time communication platform built with Node.js, Express, Socket.IO, and MySQL.

## 📋 Project Overview

This is a web application that enables real-time messaging and user management. It includes user registration, login, business directory, and payment functionality.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Real-time:** Socket.IO
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** bcrypt for password hashing

## 📁 Project Structure

```
postive_pulse_connects/
├── business.html      # Business directory page
├── index.js           # Backend server (Express + Socket.IO)
├── index1.html        # Home/Landing page
├── login.html         # User login page
├── payment.html       # Payment processing page
├── register.html      # User registration page
├── script.js          # Frontend JavaScript
└── Style.css         # Global styles
```

## 🚀 Getting Started

### Prerequisites

- Node.js installed
- MySQL server installed and running
- MySQL credentials configured in `index.js`

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install express mysql2 cors body-parser socket.io bcrypt
   ```

3. Configure MySQL database:
   - Create a database named `connect_pulse`
   - Update the database credentials in `index.js` if needed

4. Start the server:
   ```bash
   node index.js
   ```

5. Open the frontend in your browser (e.g., via Live Server on port 5500)

## 🔑 Features

- User Registration & Login
- Real-time Messaging (Socket.IO)
- Business Directory
- Payment Processing
- Gender-based User Types
