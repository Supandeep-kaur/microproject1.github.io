# Microproject 1 – Express.js Website

This project is a simple Express.js web application created for COMP2140.  
It includes multiple web pages, a JSON API, and a modern Login/Sign-In interface.

## 📌 Features
- Express.js backend server  
- Static website using HTML, CSS, and JavaScript  
- Route to return JSON data  
- Fetch API using async/await  
- Beautiful Login and Sign-In pages  
- Dropdown navigation with Login → (Login / Sign In)  
- Full background image on authentication pages  
- Notification + auto-redirect after login  
- JSON data displayed as dynamic cards

## 📁 Project Structure
project-folder/
├── app.js
├── package.json
├── data/
│ └── courses.json
├── public/
│ ├── index.html
│ ├── about.html
│ ├── courses.html
│ ├── login.html
│ ├── signin.html
│ ├── styles/style.css
│ └── scripts/main.js
└── README.md

---

## 🚀 Features

### 🖥️ **Frontend (Public Pages)**  
- Home, About, Courses pages  
- Professional modern UI  
- Responsive layout  
- Login dropdown menu  
- Login & Sign-In forms  
- Background image authentication screens  
- Notification popup after login  
- Auto-redirect to homepage  

---

### 🧠 **Backend (Express.js)**  
- Serves static web pages  
- Loads and returns JSON data through:
- Uses `express.static()` for serving frontend  
- Organized routes for each page  

---

### 📦 **API Route Example**

```js
app.get('/api/courses', (req, res) => {
res.json(coursesData);
});
 Open browser:
http://localhost:3000



