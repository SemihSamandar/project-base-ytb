# project-base-ytb

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black)

A base project for a Node.js backend, generated with **Express** and using **EJS** as the view engine.

## ✨ What's inside

- Express app with `morgan` logging, `cookie-parser`, JSON and form body parsing
- Static files served from `public/`
- 404 and error handling middleware
- Example routes:

| Method | Route    | Description        |
|--------|----------|--------------------|
| GET    | `/`      | Renders the home page |
| GET    | `/users` | Sample users endpoint |

## 🚀 Getting Started

```bash
git clone https://github.com/SemihSamandar/project-base-ytb.git
cd project-base-ytb/api
npm install
npm start
```

The server runs at **http://localhost:3000**.

## 📁 Project Structure

```
api/
├── app.js            # Express app setup
├── bin/www           # Server entry point
├── routes/
│   ├── index.js
│   └── users.js
├── views/            # EJS templates
└── public/stylesheets/
```
