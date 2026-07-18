# 📝 Notepad API

A secure and scalable RESTful API for a note-taking application built with **Node.js**, **Express.js**, and **MongoDB**. The API enables users to create, organize, update, and delete notes while providing secure authentication and efficient data management.

## 🚀 Features

- 🔐 User Authentication (JWT)
- 👤 User Registration & Login
- 📝 Create Notes
- 📄 View All Notes
- ✏️ Update Existing Notes
- 🗑️ Delete Notes
- 🔍 Search Notes
- 📂 Organize Notes
- 🔒 Protected Routes
- ✅ Input Validation
- ⚡ RESTful API Architecture
- 🛡️ Secure Password Hashing with bcrypt

---

# 🛠️ Tech Stack

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

### Tools

- Postman
- Git
- GitHub
- VS Code

---

# 📂 Project Structure

```
notepad-api/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── utils/
├── .env
├── server.js
└── package.json
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/notepad-api.git
```

Navigate to the project directory

```bash
cd notepad-api
```

Install dependencies

```bash
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

# ▶️ Run the Server

Development mode

```bash
npm run dev
```

Production mode

```bash
npm start
```

---

# 📡 API Endpoints

## Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | User login |

## Notes

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/notes | Get all notes |
| GET | /api/notes/:id | Get a single note |
| POST | /api/notes | Create a new note |
| PUT | /api/notes/:id | Update a note |
| DELETE | /api/notes/:id | Delete a note |

---

# 🔒 Security

- JWT Authentication
- Password Hashing (bcrypt)
- Protected API Routes
- Environment Variables
- Input Validation
- Error Handling

---

# 📬 API Testing

The API can be tested using:

- Postman
- Thunder Client
- Insomnia

---

# 🌟 Future Improvements

- Note Categories
- Rich Text Editor
- File Attachments
- Favorite Notes
- Archive Notes
- Soft Delete
- Tags
- Pagination
- Rate Limiting
- Swagger API Documentation

---

# 🤝 Contributing

Contributions are welcome!

Fork the repository and submit a pull request.

---

# 📬 Contact

**Helya Saeed**

💼 LinkedIn: https://linkedin.com/in/your-linkedin

💻 GitHub: https://github.com/yourusername

🌐 Portfolio: https://yourportfolio.com

---

# ⭐ Support

If you found this project useful, don't forget to ⭐ **Star** this repository!
