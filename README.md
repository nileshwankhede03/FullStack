# 📝 Notes Organiser

A full-stack Notes Organiser web application where users can create, update, delete, and manage notes in real time.

🔗 **Live Demo:**  
https://notes-organiser-y6ms.onrender.com/

---

## 🚀 Features

- Create new notes
- Edit existing notes
- Delete notes
- View all notes dynamically
- REST API based backend
- MongoDB database integration
- Clean and responsive UI

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Axios
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Mongoose)

### Deployment
- Render (Backend + Frontend)

---

## 📂 Project Structure

```
notes-organiser/
│
├── client/          # React Frontend
├── server/          # Node + Express Backend
└── README.md
```

---

## ⚙️ Installation & Setup (Local)

### 1️⃣ Clone the repository

```bash
git clone <your-repo-link>
cd notes-organiser
```

### 2️⃣ Setup Backend

```bash
cd server
npm install
npm start
```

### 3️⃣ Setup Frontend

```bash
cd client
npm install
npm start
```

---

## 🌐 API Endpoints

| Method | Endpoint        | Description     |
|--------|------------------|-----------------|
| GET    | /api/notes       | Get all notes   |
| POST   | /api/notes       | Create new note |
| PATCH  | /api/notes/:id   | Update note     |
| DELETE | /api/notes/:id   | Delete note     |

---

## 🧠 How It Works

- React UI sends requests using Axios
- Express server handles REST APIs
- Mongoose connects to MongoDB
- Notes stored in MongoDB collection
- Render hosts the full project online

---

## 📌 Future Improvements

- User authentication
- Search notes
- Categories / tags
- Dark mode
- Rich text editor

---

## 👨‍💻 Author

**Nilesh Bhausaheb Wankhede**

---

## 📃 License

This project is for educational purposes.
