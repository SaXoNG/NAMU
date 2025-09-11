# NAMU – National Art Museum of Ukraine Website

A static, responsive website for the **National Art Museum of Ukraine**, showcasing exhibitions, events, gallery, and contact information. Built with **HTML, SCSS, and JavaScript**.


## Live Demo
Experience the live website:  [NAMU](https://saxong.github.io/NAMU/);

---

## Features

- **Fully responsive design** for desktop and mobile devices.
- **Interactive image slider** with navigation dots for the gallery section.
- **Burger menu** for mobile navigation.
- **Smooth scroll** to top on newsletter form submission.
- **Structured SCSS architecture** with variables, mixins, and block-based styles.
- **Semantic HTML layout** with sections: header, main content, gallery, events, and footer.
- **Footer** includes subscription form, contact info, working hours, and social media links.

---

## Technologies Used

- **HTML5** – Semantic structure for content.
- **SCSS** – Modular and maintainable styling (`_vars.scss`, `_mixins.scss`, `_typography.scss`).
- **JavaScript** – DOM manipulation for slider, menu, and form behavior.
- **Responsive Design** – Media queries and flexible layouts for mobile and desktop.

---

## Project Structure
```
src/
├── fonts/ # Custom fonts
├── images/ # All images and icons
├── scripts/
│ └── main.js # JS logic for menu, slider, and form
├── styles/
│ ├── blocks/ # SCSS files for specific blocks (header, footer, main content, menu)
│ └── utils/ # SCSS utility files (\_vars, \_mixins, \_normalize, \_typography, utils)
└── index.html # Main HTML file
```

---

## JavaScript Features

- **Slider Navigation:** Updates active dot based on horizontal scroll.
- **Burger Menu:** Opens and closes mobile menu on click.
- **Form Submission:** Smooth scroll to top and clears input on valid submission.

---

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/SaXoNG/NAMU.git
```
2. Navigate into the project folder:

```bash
cd your-repo
```
3. Install dependencies:

```bash
npm install
```
4. Running the App:

```bash
npm start
```
## Node version

v20.18.0

