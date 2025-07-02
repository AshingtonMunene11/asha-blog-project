# 📝 Ash Blog 

Asha Blog is a simple, single-page blog post manager built with HTML, CSS, and vanilla JavaScript. It allows users to view, add, edit, and delete blog posts using a local JSON API powered by JSON Server.

## 🚀 Features

- View a list of blog post titles and images
- Click on a post to view its full details (title, content, and author)
- Add a new blog post using a form
- Edit a post’s title and content
- Delete a post from the list

## 📸 Demo


## 🔧 Technologies Used

- HTML5 & CSS3
- JavaScript (ES6)
- [JSON Server](https://github.com/typicode/json-server) for the mock backend
- Live Server (optional) for live reloading during development

## 📁 Project Structure

├── index.html
├── css/
│ └── index.css
├── src/
│ └── script.js
├── db.json
└── README.md

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AshingtonMunene11/asha-blog-project.git
cd asha-blog-project
npm install -g json-server
json-server --watch db.json --port 3000
```
Your API will be running at: 👉 http://localhost:3000/posts
4. Open the frontend
You can open index.html directly in your browser, or use Live Server:

🧪 API Endpoints
Method	Endpoint	Description
GET	/posts	Get all blog posts
GET	/posts/:id	Get a single blog post
POST	/posts	Add a new blog post
PATCH	/posts/:id	Edit a blog post
DELETE	/posts/:id	Delete a blog post

✨ Author

