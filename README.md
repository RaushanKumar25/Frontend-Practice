# 🌐 Learning Frontend

This repository contains all my HTML and CSS practice files from the early stages of my frontend learning journey.

## 🧠 Topics Practiced

- HTML Boilerplate
- Text Formatting & Tags
- CSS Basics: Color, Margin, Padding
- Flexbox & Grid Layouts
- Simple Web Page Layouts

### 📅 5 July 2025  
- Practiced Box Model  
- Created `padding.html`

  -------------------------------------
|           Margin (Outer)          |
|   ----------------------------    |
|   |       Border Area         |   |
|   |  -----------------------  |   |
|   |  |   Padding Area      |  |   |
|   |  |  -----------------  |  |   |
|   |  |  |  Content Area |  |  |   |
|   |  |  -----------------  |  |   |
|   |  -----------------------  |   |
|   ----------------------------    |
-------------------------------------


# 6 july 2025
## 📤 Display Property in CSS
The `display` property defines how an element is displayed on the page. Common values include:

- `block` – starts on a new line and takes full width (e.g., `<div>`)
- `inline` – sits inline with text (e.g., `<span>`)
- `inline-block` – similar to inline but respects height/width
- `none` – hides the element

In displayproperty.html, I’ve shown examples of different display types with visual separation.

### 📏 Relative Units in CSS

Today, I explored the most essential **relative units** in CSS that help create scalable, flexible, and responsive layouts.

#### 🔹 Units I Studied:

- **% (Percentage)**  
  Defines size relative to the parent element. Commonly used for width, height, padding, margin.

- **em**  
  Relative to the font size of the parent element. Example: `2em` means 2 times the parent's font size.

- **rem (Root em)**  
  Relative to the font size of the root (`<html>`) element. More consistent and predictable than `em`.

- **vh (Viewport Height)**  
  1vh = 1% of the browser viewport’s height. Very useful for full-screen sections.

- **vw (Viewport Width)**  
  1vw = 1% of the browser’s width. Helps in creating layouts that adapt to screen size.

#### 📁 File Added

I created a file called `relative-units.html` where I demonstrated:

- Responsive boxes using `%` width
- Font scaling using `em` and `rem`
- Full-screen sections using `vh` and `vw`
- Comparison table for understanding practical use

This learning helps me design layouts that look good on all screen sizes and devices.

# 7th july 2025
## 📌 Position Property in CSS  

Today I explored one of the most powerful layout tools in CSS — the `position` property. This property allows you to control how elements are placed on the page in relation to their parent or the viewport.

### 🔹 Position Values Learned:

- **static** – Default position; the element follows normal page flow.
- **relative** – Positioned relative to its normal position.
- **absolute** – Positioned relative to the nearest positioned ancestor (or the viewport if none exists).
- **fixed** – Positioned relative to the viewport. Stays in place when scrolling.
- **sticky** – Switches between relative and fixed based on scroll position.

### 📁 Files Created:

- `position-demo.html` – Demonstrates all five position types with color-coded boxes and visual spacing examples.

### 🎯 Key Concepts Understood:

- How `absolute` behaves differently depending on its parent
- The magic of `sticky` elements for headers
- Why `z-index` becomes important when using `position`
- How combining `top`, `right`, `bottom`, and `left` affects placement

### 🧠 Takeaway:

Understanding positioning helps in creating navbars, modals, sidebars, and any element that needs precise placement. It’s essential for responsive layouts.

# 9th july 2025
# 🧊 CSS Float Property Demo  
📅 Date: 8 July 2025

This project demonstrates the use of the `float` property in CSS. The float property is used for positioning and formatting content — for example, letting elements float next to each other like in magazines or newspapers.

---

## 📦 What is `float` in CSS?

The `float` property in CSS is used to place an element to the left or right of its container, allowing text and inline elements to wrap around it.

### 🧠 Float Values:
- `left` – Element floats to the left
- `right` – Element floats to the right
- `none` – Default value (element does not float)
- `inherit` – Inherits the float value from its parent

---

## 🛠️ What I Did

- Created a container (`#container`) with a defined width and height
- Inside it, created a floating box (`.box`) using `float: left`
- Styled the box using height, width, margin, and border



