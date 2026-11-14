# AllTechCourses 🚀

A modern, responsive multi-page educational platform built with semantic HTML5 and vanilla CSS.

## 📁 Project Structure

```text
alltech-courses/
├── index.html        # Home page
├── about.html        # About Us page
├── course.html       # Courses catalog (Web Dev & DSA video lessons)
├── contact.html      # Contact & inquiry form
├── thank-you.html    # Form submission confirmation page
├── styles.css        # Responsive styling & typography
└── README.md         # Project documentation
```

## ✨ Features

- **Semantic HTML5**: Clean, accessible markup using native semantic tags (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`).
- **Modern Responsive Design**: Fluid typography, CSS Grid, and Flexbox adapting to mobile, tablet, and desktop screens.
- **Embedded Courses**: Curated video lessons for Web Development and Data Structures & Algorithms.
- **Accessible Navigation**: Skip link for screen readers, visible focus indicators, and dynamic active page state (`aria-current="page"`).
- **Form Ready**: Contact form pre-configured for static hosting (Netlify or GitHub Pages).

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in your preferred web browser, or use VS Code's **Live Server** extension.

## 📤 Pushing to GitHub

To push this project to a new GitHub repository:

```bash
# 1. Initialize git
git init

# 2. Add files
git add .

# 3. Commit
git commit -m "Initial commit: AllTechCourses website"

# 4. Set default branch to main
git branch -M main

# 5. Connect to your GitHub repository (replace with your repo URL)
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git

# 6. Push
git push -u origin main
```

## 🌐 Deploying

- **GitHub Pages**: Go to your repository settings -> **Pages** -> Select `main` branch `/ (root)` and save.
- **Netlify**: Drag and drop the folder into Netlify for instant deployment with contact form handling.
