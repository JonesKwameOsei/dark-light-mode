# 🌗 Light-Dark Mode Project

## 📝 Overview

The **Light-Dark Mode Project** is a simple yet elegant implementation of a theme toggle feature for a website. It allows users to switch between light 🌞 and dark 🌙 modes dynamically, enhancing the user experience by providing a visually appealing and accessible interface.

## ✨ Features

- 🔄 **Dynamic Theme Switching**: Users can toggle between light and dark modes using a switch.
- 💾 **Persistent Theme**: The selected theme is saved in the browser's local storage, ensuring the user's preference is retained across sessions.
- 📱 **Responsive Design**: The project is designed to work seamlessly across different screen sizes and devices.
- 🎨 **Custom Illustrations**: The project uses SVG illustrations that adapt to the selected theme.
- 🧭 **Interactive Navigation**: A fixed navigation bar with smooth scrolling behavior for better usability.

## 🏗️ HTML Logic

- The HTML structure includes a **theme switcher** implemented using a checkbox input and a slider.
- Sections like **Home**, **About**, **Projects**, and **Contact** are organized for a clean layout.
- 🖼️ SVG images are used in the "About" section to visually represent concepts like innovation, problem-solving, and creativity.
- 🔗 Font Awesome icons are integrated for social media links in the "Contact" section.

## 🎨 CSS Logic

- 🎛️ **CSS Variables**: The project uses CSS custom properties (`--primary-color`, `--background`, etc.) to define theme-specific styles.
- 🌑 **Dark Mode Styling**: A `[data-theme="dark"]` attribute is used to apply dark mode styles dynamically.
- ✍️ **Google Fonts**: Custom fonts like Comfortaa, Kaushan Script, and Oswald are imported for a modern and professional look.
- 🕒 **Transitions**: Smooth transitions are applied to elements like the theme switcher for a polished user experience.
- 🖌️ **Box Shadows and Borders**: Subtle shadows and borders are used to enhance the visual hierarchy.

## ⚙️ JavaScript Logic

- 🔄 **Theme Toggle**: A JavaScript function dynamically updates the theme by toggling the `data-theme` attribute on the `<html>` element.
- 💾 **Local Storage**: The selected theme is stored in `localStorage` to persist the user's preference.
- 🖼️ **Image Adaptation**: JavaScript dynamically updates the source of SVG images to match the selected theme (light or dark).
- 🎛️ **Event Listeners**: The theme switcher is connected to an event listener to detect user interactions and apply the corresponding theme.

## 🚀 How It Works

The project works as follows:

1. 🌗 **Theme Switching**: When the user toggles the switch, JavaScript updates the `data-theme` attribute and applies the corresponding styles.
2. 💾 **Persistent Theme**: On page load, the script checks `localStorage` for the saved theme and applies it automatically.
3. 🖼️ **Dynamic Images**: The script updates the image sources to match the active theme, ensuring a cohesive design.
4. 🖱️ **Interactive Elements**: Navigation links and buttons are styled to provide visual feedback on hover and focus.

## 🛠️ Technologies Used

- 🧱 **HTML5**: For semantic structure and layout.
- 🎨 **CSS3**: For styling, animations, and responsive design.
- ⚡ **JavaScript**: For dynamic functionality and theme persistence.
- 🔗 **Font Awesome**: For scalable vector icons.
- ✍️ **Google Fonts**: For custom typography.
- 📝 **GitHub Flavored Markdown**: For writing documentation.

---

## 🏁 Conclusion
This project demonstrates the implementation of a light-dark mode toggle using modern web development practices. It combines HTML, CSS, and JavaScript to create a user-friendly and visually appealing interface. The use of local storage ensures a seamless experience for returning users, while the responsive design makes it accessible on all devices.
