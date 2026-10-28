 # 🌐 Facebook Clone Website

This is a **Facebook Clone Website** that I created while learning Git and GitHub through a tutorial. The project helped me understand the basics of web development and how to use Git for version control.

The website is inspired by Facebook's user interface and aims to recreate a social media-style layout using web technologies.

## 📌 About the Project

The main purpose of this project is to practice website development and learn how to manage code using Git and GitHub.

Through this project, I learned how to initialize a Git repository, track changes, commit files, and push my project to GitHub.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (if implemented)
* Git
* GitHub

## ✨ Features

* Facebook-inspired website layout.
* Simple and user-friendly interface.
* Social media-style design.
* Organized HTML and CSS code.
* Version control using Git and GitHub.

## 📂 Project Structure

```text
facebook-clone-website/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 💻 Code Example

### 1. HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>facebook</h1>
        <input type="text" placeholder="Search Facebook">
    </header>

    <main>
        <section class="post-box">
            <h2>Welcome to My Facebook Clone</h2>
            <p>This is a sample social media website created for learning purposes.</p>
            <button onclick="showMessage()">Like 👍</button>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
```

### 2. CSS (`style.css`)

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f2f5;
    margin: 0;
    padding: 0;
}

header {
    background-color: #1877f2;
    color: white;
    padding: 15px 20px;
    display: flex;
    align-items: center;
    gap: 20px;
}

header h1 {
    margin: 0;
    font-size: 30px;
}

header input {
    padding: 10px;
    border: none;
    border-radius: 20px;
}

main {
    max-width: 600px;
    margin: 30px auto;
    padding: 15px;
}

.post-box {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #1877f2;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #145dbf;
}
```

### 3. JavaScript (`script.js`)

```javascript
function showMessage() {
    alert("Thanks for liking this post!");
}
```

## 🔧 Git Commands Used

The following commands demonstrate how I managed the project using Git.

### Initialize a Git Repository

```bash
git init
```

### Check the Status of Files

```bash
git status
```

### Add Files to the Staging Area

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Initial commit"
```

### Connect to a GitHub Repository

Replace the example URL with your own GitHub repository URL.

```bash
git remote add origin https://github.com/YOUR-USERNAME/facebook-clone-website.git
```

### Push Code to GitHub

```bash
git branch -M main
git push -u origin main
```

## 📚 What I Learned

While creating this project, I learned:

* How to structure a basic website using HTML.
* How to style web pages using CSS.
* How to add simple interactivity using JavaScript.
* How to initialize and manage a Git repository.
* How to commit changes and upload code to GitHub.
* How version control helps developers manage their projects.

## 🚀 Future Improvements

In the future, I plan to improve this project by adding:

* User login and registration.
* Creating and sharing posts.
* Like and comment functionality.
* User profile pages.
* Responsive design for mobile devices.
* Backend and database integration.

## ⚠️ Disclaimer

This project is created for educational purposes as part of my Git and GitHub learning journey. It is inspired by Facebook but is not affiliated with or endorsed by Meta or Facebook.

## 👨‍💻 Author

Created with ❤️ while learning Git and GitHub.

---

⭐ **If you find this project interesting, feel free to explore the repository!**
