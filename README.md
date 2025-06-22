# Todo List App

Todo List App is a simple and intuitive task management application built with React and Vite. It allows users to add, complete, and remove tasks, keeping track of daily to-dos in a clean interface.

## Features

- Add new tasks with a text input  
- Mark tasks as completed or active  
- Delete tasks individually  
- Filter tasks by all, active, or completed (if implemented)  
- Persist tasks in `localStorage` (optional)  
- Responsive design for desktop and mobile  

## Technologies

- React (v19)  
- Vite for development and build tooling  
- CSS Modules (or plain CSS) for styling  

## Project Structure

```
Todo-list/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── TodoForm.jsx
│   │   ├── TodoList.jsx
│   │   └── TodoItem.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── eslint.config.js
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (>=14.x)  
- npm  

### Installation

```bash
git clone https://github.com/Jose-Pimenta/Todo-list.git
cd Todo-list
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Open your browser at `http://localhost:5173`.

### Build

Create a production build and preview it:

```bash
npm run build
npm run preview
```

## Customization

- Modify component styles in `src/index.css` or individual CSS modules.  
- Extend functionality by adding task filtering, due dates, or priority levels.  

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Jose Pimenta
