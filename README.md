# eGood Positive Pulse Connects

## 📝 Problem Statement

### Current Situation
Small businesses and individual professionals need an online platform to showcase their services, connect with potential customers, and facilitate real-time communication. Existing solutions are either too expensive or lack essential features like instant messaging.

### What I Developed
I built a web-based platform with the following features:
- User registration with username, email, password, gender, and user type (user/investor/startup)
- Login authentication with password hashing using bcrypt
- Business directory where users can browse and connect with startups
- Real-time chat functionality using Socket.IO for instant messaging
- Payment processing page for transactions
- Responsive UI with professional styling

### Key Implementation Details
- **Registration:** Users can register as User, Investor, or Startup. Startups can associate with their company.
- **Login:** Secure authentication with bcrypt password hashing
- **Real-time Messaging:** Socket.IO enables instant communication between users
- **Chat Rooms:** Users can join company-specific chat rooms to communicate with startups

### Deliverables Completed
- ✅ Registration and login system with secure authentication
- ✅ Business listing/directory page
- ✅ Real-time messaging capability via Socket.IO
- ✅ Payment processing page
- ✅ Professional, responsive UI

---

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
