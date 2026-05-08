# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.




# React Todo App

A simple and responsive Todo Application built using **React** and **Context API** for state management.

---

# 🚀 Features

* Add new todos
* Edit existing todos
* Delete todos
* Mark todos as completed
* Persistent state management using Context API
* Clean and responsive UI
* Component-based architecture

---

# 🛠️ Tech Stack

* React.js
* Context API
* JavaScript (ES6)
* CSS / Tailwind CSS (if used)
* Vite / CRA

---

# 📂 Project Structure

```bash
src/
│
├── components/
│   ├── TodoForm.jsx
│   ├── TodoItem.jsx
│   └── TodoList.jsx
│
├── context/
│   └── TodoContext.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone <your-repository-link>
```

Move into the project directory:

```bash
cd todo-app
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

# 🧠 Context API Usage

The application uses React Context API to manage global todo state.

### Functionalities handled by Context API:

* Add Todo
* Update Todo
* Delete Todo
* Toggle Completion Status

This helps avoid prop drilling and keeps state management clean and scalable.

---

# 📸 Screenshots

Add your project screenshots here.

```bash
/assets/screenshot.png
```

---

# 🔥 Future Improvements

* Add local storage support
* Add dark mode
* Add filters (Completed / Pending)
* Add due dates
* Backend integration

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Made with ❤️ using React and Context API.

