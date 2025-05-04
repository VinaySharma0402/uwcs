# 🏙️ Urban Waste Control

A smart and scalable web application to streamline urban waste management by allowing the public to report garbage issues and enabling municipal employees to resolve them efficiently.

---

## 📌 Project Overview

The Urban Waste Control System is designed to bridge the communication gap between city residents and municipal waste management authorities. It allows residents to submit complaints about garbage pile-ups, unclean streets, or overflowing bins. Municipal workers can then view these complaints, resolve them, and mark them as completed — all within the system.

---

## 🚀 Features

### 👤 Public Users
- Register and log in securely.
- Report garbage issues with:
  - Location
  - Description
  - Image (optional)
- Track the status of submitted complaints.

### 🛠️ Municipal Workers
- Log in with secure credentials.
- View reported complaints by area.
- Mark issues as resolved.
- Generate reports on completed tasks.

---

## 🔒 Security Features

- **JWT Authentication** for user sessions.
- **Role-Based Access Control (RBAC)** for route and data protection.
- **Email Verification** during registration.

---

## 🛠️ Tech Stack

| Layer         | Technology                    |
|---------------|-------------------------------|
| **Backend**   | Node.js, Express.js           |
| **Frontend**  | HTML, CSS                     |
| **Database**  | MongoDB (via Mongoose)        |
| **Security**  | JSON Web Tokens (JWT), bcrypt |
| **Other**     | Nodemailer (Email verification) |

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/uwcs.git
   cd Urban-Waste-Control
   ```

2. **Install Dependencies:**
```bash
npm install
```

4. **Create a .env file:**

```bash
PORT=3000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```
4. **Run the server:**

```bash
npm start
Visit http://localhost:3000 in your browser.
```

---

## 🧪 Future Enhancements
- Add support for other city services like drainage, electrical faults, etc.

- Push notifications or SMS alerts for complaint status updates.

- Mobile app integration.

- AI-based garbage detection from user-uploaded images.

## 👨‍💻 Contributors

| Name                   | Role                      | GitHub                                                  |
|------------------------|---------------------------|---------------------------------------------------------|
| Vishwasjeet Kr Gupta   | Team Lead, Full Stack     | [@vishwas7782](https://github.com/vishwas7782)          |
| Vinay Sharma           | Backend, DBMS             | [@VinaySharma0402](https://github.com/VinaySharma0402)  |
| Prarthi Kumari         | UI/UX Designer, Backend   | [@prarthi1909](https://github.com/@prarthi1909)         |
| Nishu Kumar            | Backend                   | [@Nishukr](https://github.com/Nishukr)                  |





