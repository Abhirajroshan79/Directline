# Direct Line - Landing Page

This repository contains the static landing page for **Direct Line**, a peer-to-peer messenger and calling app that works both online and offline via a Bluetooth mesh network.

## 🚀 Getting Started

This is a static website, meaning it requires no backend or build tools to run. 

### Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge).

### Running locally
1. Clone or download this repository.
2. Open `index.html` directly in your web browser.
3. No local server is strictly necessary, though you can use tools like VS Code's Live Server for a better development experience.

## 📁 File Structure
- `index.html` - The main structure, content, and interactive JavaScript of the page.
- `style.css` - All design tokens, layout rules, animations, and typography styles.
- `README.md` - Documentation for the repository.

## 🌐 Deployment (GitHub Pages)
Since this site is fully static, it is perfectly suited for **GitHub Pages**.
1. Create a repository on GitHub (e.g., `username.github.io` or a project repo).
2. Upload these files (`index.html` and `style.css`) to the root of the repository.
3. Go to **Settings > Pages** in your GitHub repo and enable deploying from the `main` branch.
4. Your site will be live within minutes!

## ✨ Features Showcased
- **Responsive Design**: Adapts seamlessly to mobile, tablet, and desktop screens.
- **Scroll Reveals**: Smooth entry animations tied to scroll position (via IntersectionObserver).
- **Dynamic Text Cycling**: Animated headline feature swapping.
- **Canvas Mesh Animation**: A custom interactive HTML5 `<canvas>` diagram demonstrating the routing mesh offline vs online modes.
- **Simulated File Download**: A dynamic UI showing simulated progress and file blob generation for APK downloading.

## 🛠 Built With
- Semantic HTML5
- Vanilla CSS3 (Custom Properties, Flexbox, CSS Grid, animations)
- Vanilla JavaScript (ES6)
