# 🔲 QR Gen Studio
A remarkably fast, production-ready utility tool dedicated to generating, stylizing, and downloading crisp QR codes on the fly.

## 📝 Overview
QR Gen Studio allows individuals and marketing professionals to rapidly transform standard text or URLs into scalable QR codes. Developed using Vite and Tailwind CSS v4, the studio emphasizes zero load-time metrics and relies on `qrcode.react` to render flawless canvas images that are instantly downloadable via `file-saver`.

## ✨ Key Features
- **Instant Rendering**: Characters typed are immediately transformed graphically onto the QR canvas.
- **Download Automation**: Utilizing the `file-saver` capability, clients simply click to export their generated SVGs/PNGs instantly.
- **Celebratory UI Mechanics**: Integrates `canvas-confetti` and `framer-motion` for delightful generation confirmations.
- **Lucide Tooling**: Visual cues managed efficiently with `lucide-react` vector data.

## 🛠 Tech Stack
- Platform Engine: `React 19` + `Vite`
- Rendering Tools: `qrcode.react`
- Utilities: `file-saver`, `canvas-confetti`
- CSS Framework: `Tailwind CSS 4`

## 🚀 Getting Started

```bash
# Jump into the studio environment
cd qr-gen-studio

# Fetch the React dependencies
npm install

# Initialize the Vite module hot-reloading server
npm run dev
```


## 🌐 Deployment

### Vercel / Netlify (Recommended)
1. Push this repository to GitHub.
2. Connect your GitHub account to [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com).
3. Select this project and use the following settings:
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`

### GitHub Pages
1. Install the gh-pages package: `npm install gh-pages --save-dev`
2. Add deployment scripts to your `package.json`.
3. Run `npm run deploy`.

## 👨‍💻 Developer
**Kartik Shete**
