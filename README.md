
# 🚀 RestUsersAPI

A professional and lightweight REST API built with **Node.js** and **Express.js** to manage user data. Supports full CRUD operations: Create, Read, Update, and Delete. Data is stored in a mock JSON file.

---

## 📂 Project Structure

```
RestUsersAPI/
├── MOCK_DATA.json       # JSON file storing all user data
├── index.js             # Main server file with all routes
├── package.json         # Project metadata and dependencies
```

---

## 🔧 Features

- 🧾 List all users
- 🔍 Get user by ID
- ➕ Add a new user
- 📝 Update user details
- ❌ Delete a user

---

## 🛠️ Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [fs Module](https://nodejs.org/api/fs.html)

---

## 📬 API Endpoints

| Method | Endpoint            | Description          |
|--------|---------------------|----------------------|
| GET    | `/api/users`        | List all users       |
| GET    | `/api/users/:id`    | Get single user      |
| POST   | `/api/users`        | Add a new user       |
| PATCH  | `/api/users/:id`    | Update user info     |
| DELETE | `/api/users/:id`    | Delete a user        |

---

## ▶️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/ANKITKUMARBARIK/RestUsersAPI.git
cd RestUsersAPI
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the server

```bash
node index.js
```

Server runs on: `http://localhost:8000`

---

## 📢 Tips

- Use tools like **Postman** or **Thunder Client** to test your API easily.
- To add more data, simply update the `MOCK_DATA.json` file or use the `POST` endpoint.

---

## 🧑‍💻 Author

Made with ❤️ by **ankit**(https://github.com/ANKITKUMARBARIK)

---

## 📜 License

This project is licensed under the GNU License.
