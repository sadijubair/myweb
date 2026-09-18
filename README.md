# Sadi Jubair - Portfolio Template

A modern, responsive one-page portfolio template with glassmorphism effects, built with Tailwind CSS.

## 🚀 Features

- **Glassmorphism Design**: Modern glass effect on navbar and cards
- **Dark Mode Aesthetic**: Deep gray/black theme with animated blob backgrounds
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Elegant fade-in and hover effects
- **Modern Typography**: Space Grotesk font for sharp, clean look
- **Accent Colors**: Electric cyan/blue gradient accents

## 📦 Setup Instructions

### 1. Install Tailwind CSS

```bash
npm init -y
npm install -D tailwindcss
```

### 2. Generate output.css

Run the Tailwind CLI to process your CSS:

```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```

This command will:
- Read from `input.css`
- Generate `output.css` with all necessary styles
- Watch for changes (remove `--watch` for one-time build)

### 3. Open in Browser

Simply open `index.html` in your browser to view the portfolio.

## 📁 Project Structure

```
sadi-webfolio/
├── index.html           # Main HTML file
├── input.css           # Tailwind source file
├── output.css          # Generated CSS (created by Tailwind CLI)
├── tailwind.config.js  # Tailwind configuration
└── README.md           # This file
```

## 🎨 Customization

### Colors
The accent color (cyan/blue) can be changed in the HTML file. Look for classes like:
- `text-cyan-400`
- `bg-gradient-to-r from-cyan-500 to-blue-600`

### Typography
To change the font, update:
1. Google Fonts link in `index.html`
2. Font family in `tailwind.config.js`

### Sections
The portfolio includes:
- Hero Section
- About Me
- Tech Stack (Skills)
- Projects
- Contact Form

## 🛠️ Technologies

- HTML5
- Tailwind CSS 3.x
- Google Fonts (Space Grotesk)
- Vanilla JavaScript (for mobile menu)

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

Free to use for personal and commercial projects.

---

Built with ❤️ by Sadi Jubair
