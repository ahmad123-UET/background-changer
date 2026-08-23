# Background Changer
 
> **Live Demo:** [ahmad123-uet.github.io/background-changer](https://ahmad123-uet.github.io/background-changer/)
> **Repository:** [github.com/ahmad123-UET/background-changer](https://github.com/ahmad123-UET/background-changer)
 
Click a color, change the world — a minimalist yet satisfying background color switcher built with **React 19**, **Vite**, and **Tailwind CSS v4**. A hands-on project to practice React state management and component styling.
 
![Background Changer Screenshot](https://github.com/user-attachments/assets/6feb714e-08be-4d4c-b4d8-6ced5e2fad8b)
 
## Features
 
- Instant full-page background color switching with a single click
- Rainbow color options — Blue, Red, Green, Yellow, Orange, Indigo, Violet
- Clean floating button panel fixed at the bottom of the screen
- Smooth and responsive UI built with Tailwind CSS
- Zero page reload — powered by React `useState` hook
## Tech Stack
 
| Technology | Purpose |
|---|---|
| React 19 | UI library — component-based architecture |
| Vite 8 | Lightning-fast build tool and dev server |
| Tailwind CSS v4 | Utility-first styling |
| JavaScript (ES6+) | Core programming language |
| GitHub Actions | Automated CI/CD deployment |
| GitHub Pages | Live hosting |
 
## Getting Started
 
### Run locally
 
```bash
# Clone the repository
git clone https://github.com/ahmad123-UET/background-changer.git
 
# Navigate to project folder
cd background-changer
 
# Install dependencies
npm install
 
# Start development server
npm run dev
```
 
Open `http://localhost:5173` in your browser.
 
### Build for production
 
```bash
npm run build
```
 
Or view it directly via the **[Live Demo](https://ahmad123-uet.github.io/background-changer/)** — no setup needed.
 
## Key Learnings
 
- Using React `useState` hook for real-time UI state management
- Building and styling components with Tailwind CSS utility classes
- Setting up a Vite + React project from scratch
- Deploying a React app to GitHub Pages using GitHub Actions CI/CD
## Deployment
 
This project is automatically deployed to GitHub Pages via **GitHub Actions** on every push to the `main` branch. The workflow:
1. Installs dependencies (`npm install`)
2. Builds the project (`npm run build`)
3. Deploys the `dist/` folder to GitHub Pages

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
