# 💱 Currency Converter

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html5.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://css3.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A simple, responsive **real-time currency converter** built with vanilla HTML, CSS, and JavaScript. Convert between 150+ world currencies with live exchange rates and country flags!

## ✨ Features
- **Live Exchange Rates**: Fetches real-time rates using free API.
- **150+ Currencies**: Supports major and minor currencies with flags.
- **Responsive Design**: Works on desktop, tablet, and mobile.
- **Easy UI**: Input amount, select from/to currencies, instant conversion.
- **No Backend Required**: Pure client-side, instant load.
- **Swap Visualization**: Arrow icon between currencies.

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3 (Flexbox), Vanilla JavaScript (ES6+)
- **APIs**:
  - [ExchangeRate-API](https://www.exchangerate-api.com/) - Free live rates
  - [FlagsAPI](https://flagsapi.com/) - Country flags
  - [Font Awesome](https://fontawesome.com/) - Icons
- **No dependencies/build tools** - Just open `index.html`!

## 🚀 Quick Start
1. Clone or download the repo.
2. Open `index.html` in any modern browser:
   ```cmd
   start Currancy-converter\index.html
   ```
3. Enter amount, select currencies, click **Get Exchange Rate**!

## 📱 Demo Screenshot
*(Add your screenshot here)*
```
[Clean UI with amount input, USD->INR flags, conversion result: 1 USD = 83.50 INR]
```

## 📖 Usage
1. Enter amount (defaults to 1).
2. Choose **From** currency (e.g., USD 🇺🇸).
3. Choose **To** currency (e.g., EUR 🇪🇺).
4. Click **Get Exchange Rate** for instant result.
5. Rate updates automatically on page load.

**Example**: 100 USD → EUR = 92.50 EUR (live rate).

## 📁 Project Structure
```
Currancy-converter/
├── index.html      # Main UI
├── style.css       # Responsive styling
├── code.js         # Core logic & API calls
├── app.js          # Alternate implementation (unused)
└── README.md       # You're reading it!
```

## 🔗 APIs & Credits
- **Exchange Rates**: [exchangerate-api.com](https://www.exchangerate-api.com/) (Free tier, no key needed)
- **Flags**: [flagsapi.com](https://flagsapi.com/)
- **Inspiration**: Modern web dev best practices

## 🚀 Potential Enhancements
- Add swap button (reverse currencies).
- Conversion history/localStorage.
- Favorites currencies.
- Error handling for offline mode.
- Dark mode toggle.

## 🤝 Contributing
1. Fork the repo.
2. Create feature branch (`git checkout -b feature/amazing-feature`).
3. Commit changes (`git commit -m 'Add amazing feature'`).
4. Push & PR!

## 📄 License
This project is [MIT](LICENSE) licensed - use freely!

---

⭐ **Star if useful!** Questions? Open an issue.
