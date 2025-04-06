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

--------------------------------------------------------------------------------

# Flexbox Layout

This project demonstrates a responsive layout using CSS Flexbox. The layout consists of a parent container that holds three child elements, showcasing how to effectively use Flexbox properties for creating flexible and responsive designs.

## Overview

The layout is designed to be fully responsive, utilizing Flexbox to arrange child elements in a visually appealing manner. The parent container takes up the full height and width of the viewport, while the child elements are styled to maintain a consistent size and appearance.

## CSS Structure

The CSS code is organized into several sections, each serving a specific purpose. Below is a detailed explanation of each section.

### Global Styles

```css
* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}
```
- **Universal Selector (`*`)**: Resets margin and padding for all elements to ensure consistent spacing across browsers.
- **Font Family**: Sets the default font to 'Poppins', with a fallback to sans-serif.
- **Box Sizing**: Uses `border-box` to include padding and border in the element's total width and height.

### HTML and Body Styles

```css
html, body {
    height: 100%;
    width: 100%;
}
```
- **Height and Width**: Ensures that both the `html` and `body` elements take up the full height and width of the viewport, allowing the parent container to fill the screen.

### Parent Container Styles

```css
.parent {
    height: 100%;
    width: 100%;
    background-color: lightblue;
    display: flex;
    align-items: center; /* Centering the elements along the cross axis */
    justify-content: space-evenly; /* Centering the elements along the main axis */
    flex-wrap: wrap; /* Prevents shrinking of flex items when the window size is reduced */
}
```
- **Height and Width**: The parent container occupies the full height and width of the viewport.
- **Background Color**: Sets a light blue background for the parent container.
- **Flexbox Properties**:
  - `display: flex;`: Enables Flexbox layout for the parent container.
  - `align-items: center;`: Centers child elements vertically within the parent container (cross axis).
  - `justify-content: space-evenly;`: Distributes child elements evenly along the main axis.
  - `flex-wrap: wrap;`: Allows child elements to wrap onto the next line if there isn't enough space, maintaining responsiveness.

### Child Element Styles

```css
.child1, .child2, .child3 {
    height: 280px;
    width: 280px;
    background-color: crimson;
    border: 4px solid #fff;
}
```
- **Height and Width**: Each child element is set to a fixed size of 280px by 280px.
- **Background Color**: Sets a crimson background for each child element.
- **Border**: Adds a 4px solid white border around each child element for visual separation.

## Conclusion

This layout effectively demonstrates the power of CSS Flexbox in creating responsive designs. By adjusting the properties of the parent and child elements, you can easily modify the layout to suit your needs.

Feel free to customize the styles further to explore the capabilities of Flexbox!


---------------------------------------------------------------------------
# 👨‍💻 Author
Made with ❤️ by Aishik Mitra
