# FinTrade Frontend

AI-powered platform for Swing and Position trading analysis with real-time data visualization.

## 🚀 Tech Stack

- **React 18** - UI Library
- **Vite 5** - Build Tool & Dev Server
- **Tailwind CSS 3** - Utility-first Styling
- **Framer Motion** - Smooth Animations
- **Recharts** - Interactive Charts
- **Lucide React** - Modern Icons

## 🔧 Local Development

### Prerequisites
- Node.js 16+ and npm

### Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/fintrade-frontend.git
cd fintrade-frontend
```

2. Install dependencies
```bash
npm install
```

3. Run development server
```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## 🏗️ Build for Production
```bash
npm run build
```

The optimized production build will be in the `dist/` folder.

## 👀 Preview Production Build
```bash
npm run preview
```

## 🌐 Deployment

- **Frontend**: Deployed on Render as a static site
- **Backend API**: https://sentiquant.onrender.com

## 📁 Project Structure
```
fintrade-frontend/
├── src/
│   ├── App.jsx          # Main application component with all features
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles & Tailwind directives
├── public/
│   └── vite.svg         # Favicon
├── index.html           # HTML template
├── package.json         # Dependencies & scripts
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── render.yaml          # Render deployment configuration
└── README.md            # This file
```

## ✨ Features

- ✅ **Stock Analysis** - Swing & Position Trading strategies
- ✅ **Portfolio Builder** - AI-powered portfolio creation
- ✅ **Strategy Comparison** - Side-by-side analysis
- ✅ **Dark Mode** - Full dark theme support
- ✅ **Responsive Design** - Mobile-first approach
- ✅ **Real-time Data** - Live market data integration
- ✅ **Interactive Charts** - Data visualization with Recharts

## 🎨 Key Components

### Pages
- **Home** - Landing page with gradient hero
- **Stocks List** - Browse all available stocks
- **Analysis** - Detailed stock analysis (Swing/Position)
- **Portfolio** - Build custom portfolios
- **Compare** - Compare trading strategies

### Features
- **Dark Mode Toggle** - Seamless theme switching
- **Responsive Navigation** - Mobile-friendly navbar
- **Loading States** - Skeleton loaders for better UX
- **Error Handling** - User-friendly error messages
- **Form Validation** - Input validation for all forms

## 🔑 API Integration

The frontend connects to the Flask backend at:
```
https://sentiquant.onrender.com
```

### API Endpoints Used
- `GET /api/stocks` - Fetch all stocks
- `GET /api/analyze/{type}/{symbol}` - Get stock analysis
- `POST /api/portfolio/{type}` - Create portfolio
- `GET /api/compare/{symbol}` - Compare strategies

## 🎯 Environment Variables (Optional)

Create `.env.local` for custom configuration:
```bash
VITE_API_BASE_URL=https://sentiquant.onrender.com
```

## 📝 Development Notes

- The app uses **template literals** for dynamic class names
- **Framer Motion** handles all animations
- **Tailwind's dark mode** uses class-based strategy
- **React hooks** manage all state and side effects

## 🐛 Troubleshooting

### Port already in use
```bash
# Kill process on port 5173
npx kill-port 5173
```

### Build fails
```bash
# Clear node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

### Styles not applying
```bash
# Rebuild Tailwind
npm run build
```

## 📄 License

MIT License - feel free to use this project for learning and development.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📧 Support

For issues or questions, please open an issue on GitHub.

---

Built with ❤️ using React + Vite + Tailwind CSS
```

---

## 🎯 Complete Folder Structure

After creating all files:
```
fintrade-frontend/
├── src/
│   ├── App.jsx              ✅ (Renamed from App.js)
│   ├── main.jsx             ✅ (New)
│   └── index.css            ✅ (New)
├── public/
│   └── vite.svg             ✅ (New)
├── index.html               ✅ (New)
├── package.json             ✅ (New)
├── vite.config.js           ✅ (New)
├── tailwind.config.js       ✅ (New)
├── postcss.config.js        ✅ (New)
├── render.yaml              ✅ (New)
├── .gitignore               ✅ (New)
└── README.md                ✅ (New)