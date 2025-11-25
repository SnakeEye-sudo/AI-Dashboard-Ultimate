# AI-Dashboard-Ultimate
🚀 Ultimate AI-Powered Dashboard with Real-time Weather, News, Crypto Prices, Quotes &amp; More! 100% Free APIs | Glassmorphism UI | Live Demo Available

## 🌐 Live Demo

**[👉 Click Here to View Live Dashboard](https://snakeeye-sudo.github.io/AI-Dashboard-Ultimate/)**

---

## ✨ Features

- **🌤️ Real-time Weather** - Live weather data from Open-Meteo API for Patna, Bihar
- **💰 Cryptocurrency Prices** - Live Bitcoin, Ethereum, and Cardano prices with 24h changes
- **💭 Random Quotes** - Inspirational quotes from famous personalities
- **📰 Latest Tech News** - Top technology headlines from India
- **🎯 Fun Facts** - Random interesting facts to expand your knowledge
- **💻 GitHub Stats** - Your GitHub profile statistics
- **🎨 Glassmorphism UI** - Modern, beautiful interface with smooth animations
- **📱 Fully Responsive** - Works perfectly on all devices
- **⚡ Fast & Lightweight** - Pure HTML, CSS, and Vanilla JavaScript
- **🆓 100% Free APIs** - No API keys required!

---

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with Glassmorphism effects
- **JavaScript (ES6+)** - Interactive functionality
- **Free APIs:**
  - [Open-Meteo](https://open-meteo.com/) - Weather Data
  - [CoinGecko](https://www.coingecko.com/) - Cryptocurrency Prices
  - [Quotable](https://github.com/lukePeavey/quotable) - Random Quotes
  - [NewsAPI Proxy](https://saurav.tech/NewsAPI/) - News Headlines
  - [Useless Facts](https://uselessfacts.jsph.pl/) - Random Facts
  - [GitHub API](https://api.github.com/) - GitHub Stats

---

## 🚀 Quick Start

### Option 1: View Live Demo
Simply visit: [https://snakeeye-sudo.github.io/AI-Dashboard-Ultimate/](https://snakeeye-sudo.github.io/AI-Dashboard-Ultimate/)

### Option 2: Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/SnakeEye-sudo/AI-Dashboard-Ultimate.git
```

2. **Navigate to directory**
```bash
cd AI-Dashboard-Ultimate
```

3. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## 📸 Screenshots

The dashboard features:
- Purple gradient background
- Glassmorphism card design
- Smooth hover animations
- Live updating data
- Interactive buttons for new quotes and facts

---

## 🎯 API Endpoints Used

| Service | Endpoint | Description |
|---------|----------|-------------|
| Weather | `api.open-meteo.com` | Real-time weather |
| Crypto | `api.coingecko.com` | Cryptocurrency prices |
| Quotes | `api.quotable.io` | Random quotes |
| News | `saurav.tech/NewsAPI` | Tech news headlines |
| Facts | `uselessfacts.jsph.pl` | Random facts |
| GitHub | `api.github.com` | User statistics |

---

## ⚙️ Features in Detail

### Weather Card
- Current temperature in Patna
- Wind speed information
- Auto-updates every 5 minutes

### Crypto Card
- Bitcoin, Ethereum, Cardano prices
- 24-hour price change percentage
- Color-coded gains/losses (green/red)
- Auto-updates every 5 minutes

### Quote Card
- Inspirational quotes
- Author attribution
- "New Quote" button for instant refresh

### News Card
- Top 4 latest technology news
- Headlines from Indian sources
- Article descriptions
- Auto-updates every 5 minutes

### Fun Fact Card
- Random interesting facts
- "New Fact" button for instant refresh

### GitHub Stats Card
- Your public repositories count
- Followers and following count
- Auto-updates every 5 minutes

---

## 🔄 Auto-Refresh

The dashboard automatically refreshes data every 5 minutes for:
- Weather information
- Cryptocurrency prices
- News headlines
- GitHub statistics

---

## 🎨 Customization

### Change Location for Weather
Edit line ~280 in `index.html`:
```javascript
const response = await fetch('https://api.open-meteo.com/v1/forecast?latitude=YOUR_LAT&longitude=YOUR_LONG&current_weather=true');
```

### Change GitHub Username
Edit line ~350 in `index.html`:
```javascript
const response = await fetch('https://api.github.com/users/YOUR_USERNAME');
```

### Modify Colors
Edit the CSS gradient in `index.html` around line ~16:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is [MIT](LICENSE) licensed.

---

## 👨‍💻 Author

**Er. Sangam Krishna (SnakeEye)**
- GitHub: [@SnakeEye-sudo](https://github.com/SnakeEye-sudo)
- Location: Bettiah, West Champaran, Bihar, India

---

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

## 🙏 Acknowledgments

- Thanks to all the free API providers
- Inspired by modern dashboard designs
- Built with ❤️ for the developer community

---

## 📌 Project Status

✅ Fully functional and deployed
🔄 Actively maintained
🆓 100% Free to use

---

**Made with 💚 by SnakeEye-sudo**
