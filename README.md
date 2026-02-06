# X (Twitter) Clone - Tailwind CSS

A responsive, dark-themed clone of the X (formerly Twitter) user interface, built using HTML and Tailwind CSS.

## 🚀 Features

- **Responsive Grid Layout**:
  - **Mobile**: Streamlined feed view.
  - **Tablet**: Adds the left navigation sidebar.
  - **Desktop**: Full 3-column layout including trends and suggestions.
- **Dark Mode UI**: Styled with `bg-black` and `text-white` to match the official X aesthetic.
- **Interactive Elements**:
  - Hover states on navigation, tweets, and buttons.
  - Sticky header with backdrop blur (`backdrop-blur-md`).
  - Sticky left sidebar for easy navigation.

## 🛠️ Technologies

- **HTML5**: Semantic markup structure.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.

## 📂 Project Structure

```
├── index.html          # Main application file
└── dist/
    └── output.css      # Compiled Tailwind CSS styles
```

## ⚡ How to Run

1. **Download** the project files.
2. Ensure the `dist/output.css` file exists (this contains the styles).
3. **Open** `index.html` in any modern web browser.

## 🔧 Development

To make changes to the styling, you will need the Tailwind CSS CLI installed.

1. **Watch for changes**:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```
   *(Note: Adjust the input path `./src/input.css` based on your actual source file location).*

## 📝 License

This project is a clone created for educational purposes.
