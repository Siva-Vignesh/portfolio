# 🚀 Siva's Portfolio Website

A modern, interactive portfolio website showcasing professional experience, projects, and skills with stunning animations and 3D effects.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

---

## ✨ Features

### 🎨 Visual Effects
- **3D Card Stack** - Interactive portfolio cards with auto-cycling animation and fan-out transitions
- **Rotating Square Background** - Animated geometric shapes in the Professional Overview section
- **Floating Particles** - Subtle animated elements throughout the page
- **Gradient Animations** - Smooth color transitions and glowing effects
- **Isometric 3D Cards** - Professional cards with perspective transforms

### 📂 Portfolio Sections

| Section | Description |
|---------|-------------|
| **Creative Showcase** | Photography & visual storytelling portfolio |
| **Technical Portfolio** | Code projects & GitHub repositories |
| **Education Website** | Home tuition center showcase |
| **Professional Portfolio** | Career & resume highlights |
| **Writer & Content** | Blogs, articles & content writing |

### 🎮 Interactive Elements
- **Tic Tac Toe Game** - Play against AI with confetti celebration on win
- **Tech Stack Gravity Simulator** - Physics-based interactive tech icons using Matter.js
- **Projects Modal** - Rocket button opens a stunning fullscreen projects showcase
- **Terminal Animation** - Typing effect with command-line interface styling

### 💼 Professional Overview
- Company logos (Capgemini & Wipro) with transparent backgrounds
- Experience timeline with 6.5+ years total
- Skills stack with progress bars
- Rotating square background animations

---

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom animations, 3D transforms, gradients
- **Tailwind CSS** - Utility-first styling
- **JavaScript** - Interactive features & animations

### Libraries & Icons
- **Font Awesome** - Icon library
- **Matter.js** - Physics engine for gravity simulator
- **Google Fonts** - Typography

---

## 📁 Project Structure

```
SJ/
├── siva.html          # Main portfolio page
├── README.md          # This file
├── index.html         # Landing page
├── home.html          # Home page variant
├── portfolio.html     # Portfolio page
├── couple.html        # Couple page
├── shaha.html         # Shaha's page
└── ...
```

---

## 🎯 Key Sections

### 1. Hero Section
- Animated background with rotating orbs
- Typing terminal effect
- Gradient text animations

### 2. Professional Overview
- Isometric 3D skill cards
- Experience timeline with company logos
- Rotating geometric background

### 3. Project Showcase
- 5 auto-cycling portfolio cards (every 3 seconds)
- Fan-out transition effects
- Floating rocket button for projects modal

### 4. Fun Zone
- Interactive Tic Tac Toe with AI
- Auto-reset after game end
- Confetti celebration on win

### 5. Tech Stack Gravity
- Physics-based floating tech icons
- Shake & Reset controls
- Matter.js powered simulation

### 6. Connect Section
- Social media links
- Contact information

---

## 🚀 Getting Started

1. **Clone or download** the repository
2. **Open** `siva.html` in a modern web browser
3. **Enjoy** the interactive experience!

```bash
# If using a local server
cd SJ
python -m http.server 8000
# Then open http://localhost:8000/siva.html
```

---

## 🎨 Customization

### Update Company Logos
Logos are loaded from Brandfetch CDN:
```html
<!-- Capgemini -->
<img src="https://cdn.brandfetch.io/idbJBNV8BD/theme/dark/symbol.svg" />

<!-- Wipro -->
<img src="https://cdn.brandfetch.io/id1uICo497/theme/dark/logo.svg" />
```

### Modify Card Cycle Speed
In the Portfolio Auto-Cycle Script:
```javascript
setInterval(cycleCards, 3000); // Change 3000 to desired ms
```

### Add New Portfolio Cards
Add new cards in the `portfolio-stack-container` div with classes like `portfolio-sixth-card`.

---

## 📱 Responsive Design

- ✅ Desktop optimized
- ✅ Tablet friendly
- ✅ Mobile responsive
- ✅ Touch interactions supported

---

## 🌟 Credits

- **Design & Development**: Siva
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **CSS Framework**: [Tailwind CSS](https://tailwindcss.com/)
- **Physics Engine**: [Matter.js](https://brm.io/matter-js/)
- **Brand Logos**: [Brandfetch](https://brandfetch.com/)

---

## 📄 License

This project is for personal portfolio use. Feel free to use as inspiration for your own portfolio!

---

<p align="center">
  Made with ❤️ by <strong>Siva</strong>
</p>

