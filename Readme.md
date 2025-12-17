Here is a **short, crisp, and clean README.md**, optimized for **quick reading**, **GitHub visitors**, and **interviewers**.
(No extra text, no repetition, very professional.)

---

# 🔗 URL Shortener Web Application

A **full-stack URL Shortener** built using the **MERN stack**, featuring **JWT authentication**, **role-based access**, **click analytics**, and **server-side rendering** with EJS.

---

## ✨ Features

* User **signup & login** with JWT authentication
* Generate **short URLs** using nanoid
* **Automatic redirection** to original links
* Track **click count & visit timestamps**
* **Role-based access control** (NORMAL / ADMIN)
* Persistent login using **JWT stored in cookies**
* **Server-side rendered UI** with EJS

---

## 🛠 Tech Stack

* **Frontend:** EJS, HTML, CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, Mongoose
* **Auth:** JWT, Cookies
* **Utility:** nanoid
* **Architecture:** MVC

---

## 🔄 Application Flow

1. User signs up or logs in
2. JWT token is generated and stored in cookies
3. User submits a long URL
4. Server creates a short URL and stores it in MongoDB
5. Each visit is logged with a timestamp
6. User views URLs and analytics on dashboard

---

## ▶️ Run Locally

```bash
git clone https://github.com/saijal-02/URL-Shortener-Web-Application.git
cd URL-Shortener-Web-Application
npm install
npm start
```

Server runs at:

```
http://localhost:8001
```

---

## 📌 Future Improvements

* Password hashing (bcrypt)
* Token expiration & refresh
* UI enhancements
* Public analytics view

---

## 👨‍💻 Author

**Saijal Gupta** – MERN Stack Developer

---

If you want, I can also:
✔ Make a **one-line resume description**
✔ Create a **LinkedIn project post**
✔ Add **screenshots/demo section**
