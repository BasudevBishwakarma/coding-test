# 🧩 Compatto - Coding Test

A minimal HTML + Tailwind CSS website landing page using Tailwind CLI and PostCSS.

## 📁 Structure

 **compatto/**
  - **app/**
    - `index.html`
  - **assets/**
    - **css/**
      - `tailwind.css` – Tailwind input file with `@tailwind` directives
      - `tailwind-output.css` – Generated file (don't edit manually)
      - `global.css` – Custom global styles
      - `fonts.css` – Font-face declarations
  - `tailwind.config.js`
  - `postcss.config.js`
  - `package.json`

## ⚙️ Setup

```bash
npm install
npm run dev
Then open app/index.html in browser (or use Live Server).

🛠 Scripts
npm run dev – Watch and compile Tailwind

npm run build – Build minified CSS
