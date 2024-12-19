
# 🚀 **Job Portal Project | For learning purposes**

## 🌟 **Project Overview**

This job portal application connects **job seekers**, **employers**, and **administrators** in a streamlined platform. It features a **Node.js Express backend**, a **MySQL database**, and a responsive **frontend** built with **HTML, CSS, and JavaScript**.

### ✨ **Features**
- 👩‍💼 **Job Seekers**: Browse and apply for jobs effortlessly.  
- 🏢 **Employers**: Post and manage job listings.  
- 🔧 **Admins**: Oversee the portal, manage roles, and moderate job postings.  

---

## 📂 **Project Structure**

```plaintext
job_portal/
│
├── backend/                   # Backend code and API
│   ├── .env                   # Environment variables
│   ├── package.json           # Dependencies and scripts
│   ├── server.js              # Main server setup
│   ├── config/
│   │   └── db.js              # Database configuration
│   └── routes/
│       └── applicationRoutes.js  # Job application endpoints
│
└── frontend/                  # Frontend code and assets
    ├── index.html             # Main frontend HTML file
    ├── css/
    │   └── index.css          # Styling for the frontend
    └── js/
        └── job-applications.js # JavaScript for frontend interaction
```

---

## 🔧 **Backend Setup**

### 🛠️ **Prerequisites**
- [Node.js](https://nodejs.org/) and [npm](https://npmjs.com/)
- [MySQL](https://www.mysql.com/)

### ⚙️ **Configuration**

1. **Environment Variables**:
   Configure database connection details in `backend/.env`:
   ```plaintext
   DB_HOST='localhost'
   DB_USER='root'
   DB_PASSWORD='your_password'
   DB_NAME='job_board'
   DB_PORT=3306
   ```

2. **Install Dependencies**:
   Navigate to the `backend` directory and run:
   ```bash
   npm install
   ```

3. **Database Setup**:
   - Start your MySQL server.
   - Create a database named `job_board`.
   - Import initial data or setup SQL if provided.

### 🚀 **Scripts**

- Start the server:
  ```bash
  npm start
  ```

---

## 🖥️ **Frontend Setup**

The frontend uses **static HTML, CSS, and JavaScript**—no compilation is required.

### 📂 **Key Files**
- **index.html**: Main entry point for the UI.  
- **index.css**: Styles the portal's UI elements (e.g., navigation, buttons).  
- **job-applications.js**: Handles functionality like applying for jobs via `fetch` API calls.

---

## ▶️ **Running the Project**

1. **Start Backend**:  
   In the `backend` directory, run:
   ```bash
   npm start
   ```

2. **Access Frontend**:  
   Open `frontend/index.html` in your web browser.

---

## 📚 **Dependencies**

### **Backend**
- `bcrypt`: Password hashing.
- `body-parser`: Parse JSON request bodies.
- `cors`: Enable cross-origin requests.
- `express`: Server framework.
- `express-session`: Manage session data.
- `express-validator`: Validate user inputs.
- `mysql` and `mysql2`: MySQL database interface.

---

## 🤝 **Contributing**

We welcome contributions! Follow these steps:

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit changes:  
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push the branch and submit a pull request.

---

## 📝 **License**

This project is licensed under the **MIT License**.

---

