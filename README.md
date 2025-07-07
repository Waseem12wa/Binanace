# Advanced Sweep Detection System (Version 3)

## Overview
This project is a real-time crypto market sweep detector and analytics dashboard. It connects directly to Binance's public WebSocket API to visualize price action, detect sweep patterns, and display live trading signals with high accuracy.

**Key Features:**
- Real-time price chart for selected crypto pairs (BTC/USDT, ETH/USDT, etc.)
- Live sweep detection (bullish/bearish) using configurable thresholds
- Signal strength and statistics (accuracy, win rate, etc.)
- Fully customizable via UI controls
- Modern, responsive design

## Folder Structure
```
version3/
  ├── index.html   # Main HTML file (links to CSS & JS)
  ├── style.css    # All styles for the dashboard
  ├── app.js       # All JavaScript logic (data, detection, chart, UI)
  └── README.md    # This documentation
```

## How to Use
1. **Download or clone the repository.**
2. **Open `version3/index.html` in your web browser.**
   - No build step or server required; all logic runs in the browser.
   - Requires an internet connection to load Chart.js and connect to Binance.
3. **Select your trading pair and adjust detection settings as desired.**
4. **View live price chart, signals, and statistics in real time.**

## Requirements
- Modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (for Binance WebSocket and Chart.js CDN)

## How It Works
- Uses Binance WebSocket API for live price and volume data.
- Detects sweeps (sharp moves past recent highs/lows) and logs signals.
- All detection logic and UI updates are handled in `app.js`.
- No backend or server-side code required.

## Customization
- You can easily modify the UI, detection logic, or add new features by editing `style.css` and `app.js`.
- To add more trading pairs, update the dropdown in `index.html` and the symbol mapping in `app.js`.

## License
This project is for educational and personal use. Please check Binance API terms for commercial usage.

---

**Enjoy real-time crypto sweep detection!** 