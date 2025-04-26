# 🔄 Progress Bar with Circular Animation

## Demo.gif

![Image](https://github.com/user-attachments/assets/40e32486-c550-4733-8dc6-9bb6d1810fc6)

---

A visually appealing **circular progress bar** built with HTML, CSS, and JavaScript. The bar dynamically animates to show progress in a smooth and modern design, making it perfect for loading screens, skill indicators, or performance metrics.

---

## Features
- 🎯 **Dynamic Progress Update:** The progress bar smoothly increments to a specified percentage.
- 🎨 **Gradient Stroke:** The circular progress bar features a gradient stroke for a modern and polished look.
- 💻 **Responsive Design:** Scales seamlessly for all screen sizes and devices.
- 🕑 **Smooth Animation:** CSS animations create a visually engaging stroke animation around the circle.
- ✨ **Neumorphic Design:** A clean and subtle 3D look for the inner and outer circles.

---

## Technologies Used
- 🎨 **HTML:** Provides the structure for the circular progress bar and SVG elements.
- 🎨 **CSS:** Styles the progress bar with gradient strokes, neumorphic effects, and animations.
- ✨ **JavaScript:** Implements the dynamic percentage counter.

---

## How to Use

1. **View the Progress Bar:**
   - Open the `index.html` file in your browser to see the circular progress bar in action.

2. **Dynamic Percentage:**
   - The progress bar increments from `0%` to `65%` with smooth animations.

3. **Responsive Design:**
   - The design works seamlessly on all devices, including desktops and mobile phones.

---

## Key Code Snippets

### JavaScript for Dynamic Progress
The `setInterval` function increments the percentage and updates the progress bar:
```javascript
let number = document.getElementById("number");
let counter = 0;
setInterval(() => {
   if (counter == 65) {
      clearInterval();
   } else {
      counter += 1;
      number.innerHTML = counter + "%";
   }
}, 30);
```

🙋‍♀️ Author
Linga Bhavana – Frontend Developer

GitHub | urstrulybhavana1432@gmail.com

---


📬 **Contact**

For questions or suggestions, feel free to reach out:

- 📧 **Email**: [urstrulybhavana1432@gmail.com](mailto:urstrulybhavana1432@gmail.com)  
- 🐙 **GitHub**: [UrstrulyBhavana](https://github.com/UrstrulyBhavana)


---

📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

