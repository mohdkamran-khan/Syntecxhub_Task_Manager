# Task Manager

A simple, clean & responsive task manager built with the **MERN** stack.  
Allows users to create, view, update, delete and search events with user authentication.

---

## 🧰 Features

- Add new tasks (title, description, location, category, date)  
- View all tasks
- Tasks sorted by date
- Update or delete tasks  
- Search/filter tasks by title, description.  
- User authentication (login / register)  
- Responsive UI
  
---

## 📸 Screenshots

- Home:
<img width="2104" height="1500" alt="taskhome" src="https://github.com/user-attachments/assets/638471e7-0e91-4ae5-9f1e-54fa34524837" />

---

- Login:
<img width="2104" height="1286" alt="tasklogin" src="https://github.com/user-attachments/assets/47d196f9-695c-486c-8f42-c9bea49da8f6" />

---

- Register:
<img width="2104" height="1286" alt="taskregister" src="https://github.com/user-attachments/assets/3b653daf-a69c-49ef-8252-4793907f6eff" />

---

- Add Task:
<img width="2104" height="1746" alt="add-task" src="https://github.com/user-attachments/assets/5e6e387a-33c5-4bb4-ab4f-1b0632801ace" />

---

- View Task:
<img width="2104" height="1500" alt="viewtask" src="https://github.com/user-attachments/assets/af83c072-8416-4cd4-9a4c-001e2f45ede1" />

---

- Edit Task:
<img width="2104" height="1500" alt="updatetask" src="https://github.com/user-attachments/assets/395b1f33-391f-4525-80d6-d58548e5bed7" />

---

- Search:
<img width="2104" height="1500" alt="searchtask" src="https://github.com/user-attachments/assets/f8d4c7a0-ccdd-4fd1-8f2e-58ae30e7bca1" />

---

## 🚀 Tech Stack

- **Frontend**: React, React Router  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (via Mongoose)  
- **State / Context**: React Context API  
- **Styling**: Tailwind CSS and Lucide Icons  
- **Authentication**: Basic (login/register) using user IDs as tokens 
- **Dev tools**: Axios for HTTP requests, React Toastify for notifications  

---

## Project Structure

```pgsql

Syntecxhub_Task_Manager
├── BACKEND
│   ├── public
│   └── src
│   │   ├── models
│   │   ├── Event.model.js
│   │   └── User.model.js
│   ├── app.js
│   ├── db.config.js
│   └── routes.js
│
├── .env
├── index.js
├── package.json 
   
├── FRONTEMD
│   ├── src
│   ├── components
│   │   ├── EventCard.jsx
│   │   ├── EventUpdateView.jsx
│   │   ├── EventView.jsx
│   │   ├── EventViewModel.jsx
│   │   ├── Footer.jsx
│   │   ├── Loader.jsx
│   │   ├── LoaderComponent.jsx
│   │   ├── Logo.jsx
│   │   └── Navbar.jsx
│   ├── context
│   │   └── MainContext.jsx
│   ├── layout
│   │   └── ProtectedLayout.jsx
│   ├── Pages
│   │   ├── AddEvent.jsx
│   │   ├── Dashboard.jsx
│   │   ├── Error.jsx
│   │   ├── Login.jsx
│   │   └── Register.jsx
│   ├── utils
│   │   ├──axiosClient.js
│   │   └── constants.js
│   │
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── event.png
├── index.html
├── package.json
└── README.md

```

---

## 🔧 Setup Instructions

Follow these steps to get the project running locally:

## Prerequisites

- Node.js & npm installed  
- MongoDB running (local or remote)  
- Git installed  
- Any IED like VS Code

### Clone & Setup

### 1️⃣ Clone the repository  
   ```bash
   git clone https://github.com/mohdkamran-khan/Syntecxhub_Task_Manager.git
   ```

### 2️⃣ Change directory to project
```bash
cd Syntecxhub_Task_Manager
```

### 3️⃣ Install backend dependencies
```bash
cd BACKEND
npm install
```
### 4️⃣ Create a .env file in BACKEND:
```env
PORT=4500
MONGO_URI=your_mongodb_connection_string
```

### 5️⃣ Start backend server
```bash
npm run dev
```
### 6️⃣ In a new terminal, install frontend dependencies
```bash
cd ../FRONTEND
npm install
```

### 7️⃣ Start frontend
```bash
npm start
```
This should open your React app in browser (usually at ```http://localhost:5173```).

--- 

## 💻 Use the app:

Register a new user

Login

Add, update, delete events

View your events

---

## ⚠️ Trade-offs & Future Improvements

-	Using user ID as token via custom headers
-	Dates stored as strings
- Basic form / field validation (Yup)	

---

## 📧 Contributing

Contributions are welcome. If you want to contribute:

1. Fork the repo
2. Create a feature branch `git checkout -b feature/your-feature`
3. Commit your changes `git commit -m "feat: add ..."`
4. Push and open a pull request

## 📄 License

```
This project is open-source and available under the [MIT License]
```

## 👨🏻‍💻 Author

Mohd Kamran Khan | You can reach me at: [mohdkamrankhan.dev@gmail.com]

🌐 **Portfolio:** [mohdkamran-khan.github.io/KAMRAN-portfolio](https://mohdkamran-khan.github.io/KAMRAN-portfolio/)
