# 📝 To-Do List App

A simple, clean, and responsive To-Do List web app built using **HTML, CSS, and JavaScript**. Tasks are saved in the browser's **localStorage**, so your list stays intact even after refreshing or closing the page.

## ✨ Features

- ➕ Add new tasks
- ✅ Mark tasks as complete / incomplete
- ❌ Delete individual tasks
- 🧹 Clear all completed tasks at once
- 💾 Data persistence using **localStorage**
- 📊 Live task counter ("X tasks left")
- 📱 Fully responsive design

## 🛠️ Built With

- **HTML5** – structure
- **CSS3** – styling and animations
- **JavaScript (Vanilla)** – functionality and DOM manipulation
- **localStorage API** – data persistence

## 🚀 Getting Started

### Prerequisites

Just a web browser. No installations or dependencies required.

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Haniabatool72/todo-list-app.git
   ```
2. Navigate to the project folder
   ```bash
   cd todo-list-app
   ```
3. Open `index.html` in your browser

That's it — no build tools or servers needed!

## 📂 Project Structure

```
todo-list-app/
│
├── index.html      # Main HTML, CSS, and JS file
└── README.md        # Project documentation
```

## 🎯 How It Works

- Tasks are stored as objects (`{ id, text, completed }`) inside a JavaScript array
- Every time a task is added, completed, or deleted, the array is saved to `localStorage` as JSON
- On page load, tasks are read back from `localStorage` and rendered to the screen

## 🔮 Future Improvements

- [ ] Add due dates for tasks
- [ ] Add task categories/tags
- [ ] Add edit functionality for existing tasks
- [ ] Drag-and-drop task reordering
- [ ] Dark mode toggle

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Haniabatool72/todo-list-app/issues).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Hania Batool**
- GitHub: [@Haniabatool72](https://github.com/Haniabatool72)

---

⭐ If you like this project, give it a star on GitHub!
