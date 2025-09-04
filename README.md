# Streak Café ☕️

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3\&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)](#)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap\&logoColor=white)](#)
[![AOS](https://img.shields.io/badge/AOS-Animations-blue)](#)
[![Swiper](https://img.shields.io/badge/Swiper-Carousel-blueviolet)](#)
[![SweetAlert2](https://img.shields.io/badge/SweetAlert2-Alerts-ff69b4)](#)

**Streak Café** is a responsive front‑end website for a coffee shop, created as the final project for NTI. It was built using **HTML, CSS, JavaScript, and Bootstrap**, with extra libraries for animations, sliders, and alerts.

---

## 📖 Overview

The website represents a modern café with multiple pages, smooth animations, interactive alerts, and a shopping cart simulation using `localStorage`. It demonstrates front‑end development skills and the integration of third‑party libraries.

---

## 🔎 Project Structure

Main files and folders included in the project:

* `index.html` — root entry file (redirect or general entry)
* `pages/homepage.html` — main landing page (includes AOS, Swiper, SweetAlert2)
* `pages/coffee_collection.html` — coffee collection / menu page
* `pages/individual_coffee_profile.html` — individual coffee profile page
* `pages/brewing_guides_hub.html` — brewing guides hub
* `pages/omar_s_story.html` — personal story page
* `pages/shopping_cart_checkout.html` — shopping cart and checkout (uses localStorage)
* `css/` — stylesheets (`style.css`, `main.css`)
* `imgs/` — images for hero sections, coffee items, gallery, etc.

---

## 🧩 Tech Stack & Libraries

* **HTML5 / CSS3 / JavaScript (Vanilla)**
* **Bootstrap 5.3.2** (layout & responsive design)
* **Font Awesome 6.4.0** (icons)
* **AOS v2.3.1** (scroll animations)
* **Swiper v11** (carousel/slider)
* **SweetAlert2 v11** (alerts & modals)
* **localStorage** for cart and login simulation

---

## 🚀 Getting Started

### Requirements

* Any modern web browser
* (Optional) VS Code with Live Server extension for local preview

### Run Locally

1. Clone or download the repository.

   ```bash
   git clone https://github.com/<your-username>/streak-cafe.git
   cd streak-cafe
   ```
2. Open `pages/homepage.html` directly in your browser, or
3. Start a local server for best results:

   ```bash
   # Python 3
   python -m http.server 5500
   # Visit:
   # http://localhost:5500/pages/homepage.html
   ```

> For GitHub Pages deployment, ensure the main page is accessible as `index.html` in the root directory, or use a redirect from the root to `/pages/homepage.html`.

---

## ⚙️ Customization

* **Styles:** Modify `css/style.css` and `css/main.css`.
* **Images:** Replace or add files inside `imgs/` and update paths in HTML.
* **Content:** Update text and sections in `pages/*.html`.
* **Animations:** Configure AOS in the HTML `data-aos` attributes or adjust `AOS.init()` settings.
* **Alerts:** Customize SweetAlert2 calls in the `<script>` sections of HTML files.

---

## 🛒 Shopping Cart

* The cart is client‑side only, built with JavaScript and `localStorage`.
* Test it by adding products from the collection pages and viewing them in `pages/shopping_cart_checkout.html`.
* Data will persist in your browser until cleared.

---

## ✅ Checklist

* [ ] Responsive on mobile, tablet, and desktop
* [ ] Navigation links scroll or redirect correctly
* [ ] AOS animations run smoothly
* [ ] SweetAlert2 alerts trigger correctly
* [ ] Forms validate required fields

---

## 📌 Future Improvements

* Integrate a real backend or Firebase for persistent cart and authentication
* Add an admin dashboard for managing menu items
* Optimize images and minify CSS/JS for performance
* Add light/dark mode toggle

---

## 📸 Screenshots

<img width="1858" height="962" alt="Screenshot 2025-09-04 200336" src="https://github.com/user-attachments/assets/a503583f-9731-4b96-94ae-4515e891f6da" />



---

## 🙌 Acknowledgments

* **NTI** – project basis
* **Bootstrap, AOS, Swiper, SweetAlert2** – for providing excellent front‑end tools

---
