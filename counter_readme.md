# Simple Counter Program

A minimal, interactive counter application built with vanilla JavaScript, HTML, and CSS. This project demonstrates basic DOM manipulation and event handling without any external dependencies.

![Counter Demo](https://img.shields.io/badge/status-active-success.svg)
![Made with JavaScript](https://img.shields.io/badge/made%20with-JavaScript-yellow.svg)

## 🎯 Features

- **Increment/Decrement**: Increase or decrease the counter value by 1
- **Reset Functionality**: Reset counter back to 0 with a single click
- **Responsive Design**: Clean, centered layout that works on all screen sizes
- **Smooth Animations**: Hover effects on buttons for better user experience

## 🚀 Demo

The counter starts at 0 and can be:
- Increased by clicking the "Increase" button
- Decreased by clicking the "Decrease" button
- Reset to 0 by clicking the "Reset" button

## 📁 Project Structure

```
counter-program/
│
├── index.html          # HTML structure
├── counter.css         # Styling
├── counter.js          # JavaScript logic
└── README.md           # Documentation
```

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/counter-program.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd counter-program
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server (recommended)
   npx serve
   ```

## 💻 Usage

### Basic Usage

1. Open `index.html` in any modern web browser
2. Click the buttons to interact with the counter:
   - **Increase**: Adds 1 to the counter
   - **Decrease**: Subtracts 1 from the counter
   - **Reset**: Sets the counter back to 0

### Code Example

The core JavaScript functionality:

```javascript
// Initialize counter
let count = 0;

// Increase button
increaseBtn.onclick = function () {
    count++;
    countLabel.textContent = count;
}

// Decrease button
decreaseBtn.onclick = function () {
    count--;
    countLabel.textContent = count;
}

// Reset button
resetBtn.onclick = function () {
    count = 0;
    countLabel.textContent = count;
}
```

## 🎨 Customization

### Change Button Colors
Edit `counter.css`:
```css
button {
    background-color: rgb(255, 124, 124); /* Change this */
}

button:hover {
    background-color: rgb(210, 52, 52); /* And this */
}
```

### Modify Counter Size
```css
#countLabel {
    font-size: 10rem; /* Adjust size here */
}
```

## 📖 How It Works

### HTML Structure
- Container div centers all elements
- Label displays the counter value
- Three buttons for user interaction

### CSS Styling
- Flexbox/block layout for centering
- Hover effects on buttons for interactivity
- Responsive font sizing

### JavaScript Logic
1. **DOM Selection**: Grabs button and label elements
2. **Event Listeners**: Attaches click handlers to buttons
3. **State Management**: Tracks counter value in `count` variable
4. **Conditional Styling**: Changes color based on counter value

## 🔧 Technical Details

- **No Dependencies**: Pure vanilla JavaScript
- **Browser Compatibility**: Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance**: Lightweight with minimal DOM manipulation
- **Accessibility**: Semantic HTML structure

## 🤝 Contributing

Contributions are welcome! Here are some ideas for improvements:

- Add keyboard shortcuts (↑ for increase, ↓ for decrease)
- Add increment/decrement by custom amounts
- Add sound effects
- Add animation when counter changes
- Add dark mode toggle
- Save counter value to localStorage

### How to Contribute

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments

- Built as a learning project to practice DOM manipulation
- Inspired by classic counter examples in web development tutorials

## 📧 Contact

Have questions or suggestions? Feel free to open an issue or reach out!

---

⭐ If you found this project helpful, please consider giving it a star on GitHub!