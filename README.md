# Haryana Waste Management Control System

A web-based waste management monitoring system for Haryana, built with HTML, CSS, and JavaScript. Deployed on GitHub Pages with CSV files as the database.

## 🎯 Features

- **Interactive Map**: Visual map of Haryana's 22 districts with color-coded red flag markers
- **Red Flag System**: Citizens report waste issues (garbage pile-up, stagnant water)
- **Auto-Deployment**: When a district reaches 3 red flags, cleaning services are automatically deployed
- **Cleaning Log**: Timestamped records of all cleaning operations with filters
- **Real-time Statistics**: Live dashboard showing total flags, active regions, and daily cleanups
- **Glassmorphism UI**: Modern design with frosted glass effects, smooth animations, and dark mode

## 🔧 Setup

1. Fork or clone this repository
2. Enable GitHub Pages in Settings → Pages
3. Select main branch as source
4. Your site will be live at the provided URL

## 📊 Updating Data

Edit CSV files directly on GitHub:
- **Add flags**: Update `red_flags` column in `regions.csv`
- **Log cleaning**: Add rows to `cleaning-log.csv`
- Changes reflect automatically on the website

## 🛠️ Tech Stack

- HTML5, CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- PapaParse for CSV parsing
- Google Fonts (Poppins)
- GitHub Pages for hosting

## 📱 Responsive Design

Optimized for desktop, tablet, and mobile devices with touch-friendly interface.

## 📄 License

MIT License - Free to use and modify
