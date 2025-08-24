````md
# 🍲 Food Recipe App

A MERN stack application where users can add, edit, view, and favorite food recipes. It supports user authentication, recipe management, and favorites storage.

## 🚀 Features
- 🔐 User login & registration  
- 🍴 Add, edit, delete recipes  
- 📖 View recipe details with creator info  
- ❤️ Save favorite recipes  
- 🗂️ Separate pages for All, My, and Favorite recipes  

## 🛠️ Tech Stack
- **Frontend:** React (Vite), React Router, Axios, CSS  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose  
- **Other Tools:** CORS, dotenv, Nodemon  

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/your-username/food-recipe-app.git
````

### 2. Setup Backend

```bash
cd backend
npm install
nodemon server.js
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Setup Environment Variables

Create a `.env` file inside the **backend** folder with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 📌 API Endpoints

### User Routes

* `POST /user/register` → Register user
* `POST /user/login` → Login user

### Recipe Routes

* `GET /recipe` → Get all recipes
* `GET /recipe/:id` → Get a single recipe
* `POST /recipe` → Create a recipe
* `PUT /recipe/:id` → Update a recipe
* `DELETE /recipe/:id` → Delete a recipe

---

✨ Happy Cooking & Coding!

```

Do you also want me to add **sample user & recipe JSON data** in README so anyone testing can quickly insert into MongoDB?
```
