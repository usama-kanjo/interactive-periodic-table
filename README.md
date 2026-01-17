# ⚛️ Interactive Periodic Table

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/usama-kanjo/interactive-periodic-table?style=social)](https://github.com/usama-kanjo/interactive-periodic-table/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/usama-kanjo/interactive-periodic-table?style=social)](https://github.com/usama-kanjo/interactive-periodic-table/network/members)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

An interactive, responsive periodic table built with pure HTML, CSS, and JavaScript. Originally developed 5 years ago and recently modernized.

## 🌍 Available Languages
- [English](README.md) (Default)
- [Türkçe](docs/README_TR.md) (Turkish)

## 🎬 Live Demo

### Main Features
![Periodic Table Demo](demo.gif)

## ✨ Features

- **Complete Elements Display**: All 118 chemical elements visually organized
- **Interactive Details**: Click any element to view detailed information with animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean design with smooth transitions and hover effects
- **No Dependencies**: Built with vanilla technologies, no frameworks required
- **Fast Performance**: Lightweight and loads instantly

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure and markup |
| **CSS3** | Styling, animations, and responsive design |
| **Vanilla JavaScript** | Interactivity and dynamic content |
| **PHP** | Backend data processing (if applicable) |

## 📁 Project Structure

```
interactive-periodic-table/
├── index.html              # Main entry point
├── style.css              # Primary stylesheet
├── style1.css             # Additional styling modules
├── style2.css
├── style3.css
├── script.js              # Core JavaScript functionality
├── php.php                # PHP backend logic
├── demo.gif               # Main demonstration (auto-plays)
├── README.md              # This documentation
├── video/                 # Original video recordings
│   └── demo.mp4
└── .git/                  # Version control
```

## 🚀 Quick Start

### For All Users
1. Clone the repository:
   ```bash
   git clone https://github.com/usama-kanjo/interactive-periodic-table.git
   cd interactive-periodic-table
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Drag and drop into browser window

### For Linux Users (Recommended Methods)

#### **Option 1: VS Code Live Server** 🎯
```bash
# Install VS Code (if not installed)
sudo apt update
sudo apt install code

# Open project in VS Code
code .

# Install 'Live Server' extension
# Right-click index.html → 'Open with Live Server'
# Automatically opens at http://localhost:5500
```

#### **Option 2: Python HTTP Server**
```bash
cd interactive-periodic-table
python3 -m http.server 8080
# Visit http://localhost:8080
```

#### **Option 3: PHP Built-in Server**
```bash
cd interactive-periodic-table
php -S localhost:8000
# Visit http://localhost:8000
```

#### **Option 4: Direct Browser Open**
```bash
firefox index.html
# or
google-chrome index.html
# or
chromium index.html
```

## 🎮 How to Use

1. **Browse Elements**: Scroll through the periodic table
2. **View Details**: Click any element card to see detailed information
3. **Interactive Features**:
   - Hover over elements for preview
   - Click for full details with animation
   - Responsive layout adapts to screen size
4. **Navigation**: Click outside or use ESC to close details

## 🔧 Development

### File Organization
The project uses modular CSS for better maintainability:
- `style.css`: Main layout and global styles
- `style1.css`: Element card designs
- `style2.css`: Animation and transitions
- `style3.css`: Responsive breakpoints

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Opera 50+

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Improvement
- Add search/filter functionality
- Implement dark/light theme toggle
- Add element comparison feature
- Include historical information
- Add quiz/learning mode

## 🐛 Troubleshooting

### Common Issues

| Issue | Solution |
|-------|----------|
| Styles not loading | Ensure all CSS files are in same directory |
| JavaScript errors | Check browser console (F12) for details |
| PHP not working | Run with a PHP server (Option 3 above) |
| GIFs not animating | Check file paths in README.md |

### Quick Fixes
```html
<!-- Verify your HTML includes these lines -->
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="style1.css">
<link rel="stylesheet" href="style2.css">
<link rel="stylesheet" href="style3.css">
<script src="script.js"></script>
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@usama kanjo](https://github.com/usama-kanjo)
- Project: [Interactive Periodic Table](https://github.com/usama-kanjo/interactive-periodic-table)

## 🙏 Acknowledgments

- Periodic table data sourced from scientific resources
- Inspired by chemistry education tools
- Icons from [Font Awesome](https://fontawesome.com)
- Color palette from [Coolors](https://coolors.co)

---

⭐ **If you find this project useful, please give it a star on GitHub!**
