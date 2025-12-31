# 🚀 NexaFlow Landing Page

A modern, responsive SaaS landing page built with React.js featuring smooth animations, contemporary design, and full mobile support.

![NexaFlow](https://img.shields.io/badge/React-18.2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 🎨 Modern gradient design with purple/pink theme
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎭 Smooth animations and transitions
- 🧭 Sticky navigation with blur effect
- 💫 Interactive hover effects
- ⚡ Fast performance
- 🎯 Clean component structure

## 🛠️ Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/nexaflow-landing.git
cd nexaflow-landing
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the development server**
```bash
npm start
```

4. **Open your browser**
Navigate to `http://localhost:3000`

## 📦 Build for Production
```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## 🌐 Deployment

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

### Deploy to Netlify

1. Build the app:
```bash
npm run build
```

2. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

3. Deploy:
```bash
netlify deploy --prod --dir=build
```

### Deploy to GitHub Pages

1. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

2. Add to `package.json`:
```json
"homepage": "https://yourusername.github.io/nexaflow-landing",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

3. Deploy:
```bash
npm run deploy
```

## 📁 Project Structure
```
nexaflow-landing/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── App.js          # Main component
│   ├── App.css         # Styling
│   ├── index.js        # Entry point
│   └── index.css       # Global styles
├── .gitignore
├── package.json
└── README.md

## 🎨 Customization

### Change Colors

Edit the gradient colors in `src/App.css`:
```css
.app {
  background: linear-gradient(to bottom right, #0f172a, #581c87, #0f172a);
}
```

### Modify Content

Edit the content arrays in `src/App.js`:
```javascript
const features = [
  {
    icon: <Zap className="w-6 h-6" />,
    title: "Your Feature",
    description: "Your description"
  }
];
```

### Add New Sections

Add new section components in `src/App.js` and style them in `src/App.css`.

## 📦 Dependencies

- **React** (^18.2.0) - UI library
- **React DOM** (^18.2.0) - React rendering
- **lucide-react** (^0.263.1) - Icon library
- **react-scripts** (5.0.1) - Build configuration

## 🐛 Troubleshooting

### Port already in use
```bash
PORT=3001 npm start
```

### Module not found
```bash
rm -rf node_modules package-lock.json
npm install
```

### Build errors
```bash
npm cache clean --force
npm install
npm run build
```

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

Sahil Burele - sahilburele6789@gmail.com

Project Link: [https://github.com/yourusername/nexaflow-landing](https://github.com/yourusername/nexaflow-landing)

## 🙏 Acknowledgments

- Icons by [Lucide](https://lucide.dev/)
- Built with [React](https://reactjs.org/)
- Styled with pure CSS

---

⭐ If you found this helpful, please give it a star!


Built with ❤️ using React.js
