# 📐 CSS Units Demo – rem, em, vw, vh, vmin, vmax Explained

This project demonstrates how different CSS units work in practice — including `px`, `%`, `em`, `rem`, `vw`, `vh`, `vmin`, and `vmax`. It's a great visual reference for learning how relative and absolute sizing behaves in web development.

## ✨ Features

- Clear layout structure using parent-child elements
- Visual comparison of units like `vw`, `vh`, `em`, `rem`
- Includes helpful comments and explanations inside the CSS
- Responsive behavior with viewport-based units
- Typography scaling with `em` and `rem`

## 💻 Tech Stack

- HTML
- CSS (with detailed comments)
- Google Fonts: [Poppins](https://fonts.google.com/specimen/Poppins)

## 📂 File Structure

📁 root/ ├── index.html └── style.css



> 📝 All logic is inside `style.css`. The file is heavily commented to serve as a learning reference.

## 📸 Demo Preview

| Element         | Description                         |
|----------------|-------------------------------------|
| `#parent`       | Uses `vw` for width, `px` for height |
| `#child`        | Uses `vw` for font size              |
| `#parent2`      | Uses `em` units based on parent size |
| `h1`, `h2`, `h3`| Font sizes using `em`                |

## 🧠 Key Concepts Illustrated

### CSS Units
| Unit    | Description                                           |
|---------|-------------------------------------------------------|
| `%`     | Relative to parent element                            |
| `vw`    | 1% of the **viewport's width**                        |
| `vh`    | 1% of the **viewport's height**                       |
| `vmin`  | 1% of the **smaller dimension** of the viewport       |
| `vmax`  | 1% of the **larger dimension** of the viewport        |
| `em`    | Relative to **parent element’s font size**            |
| `rem`   | Relative to **root element’s font size** (default: 16px) |
| `px`    | Absolute pixel value                                  |

### `rem` Deep Dive
```css
html {
  font-size: 16px; /* default in most browsers */
}
```


---------------------------------------------------------------------------
# 👨‍💻 Author
Made with ❤️ by Aishik Mitra
