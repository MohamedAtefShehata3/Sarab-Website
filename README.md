# 🍔 Sarab — Fast Food & Restaurant Website

A fully responsive, multi-section restaurant landing page built with **HTML5, CSS3, and vanilla JavaScript**, enhanced with interactive UI components such as a live menu filter, product detail modals, an image gallery lightbox, a testimonials carousel, an animated countdown timer, and scroll animations.

---

## 🚀 Live Preview
*(Add your live demo link here once deployed — e.g. Netlify / Vercel / GitHub Pages)*

---

## ✨ Features

- **Sticky Navbar** with scroll-spy active-link highlighting and a smooth-scroll navigation system
- **Search Overlay** with category shortcuts and trending search tags
- **Hero Section** with animated stat counters (customers, menu items, chefs, years of experience)
- **Category Browser** to quickly filter the menu by food type
- **Dynamic Menu Grid** with client-side filtering (Burgers, Pizza, Chicken, Wraps, Pasta, Desserts)
- **Menu Item Detail Modal** — clicking any dish opens a popup with price, calories, prep time, rating, tags, and a quantity selector with an "Add to Cart" interaction
- **Limited-Time Offer Section** with a live JavaScript countdown timer
- **Image Gallery with Lightbox** — custom-built popup viewer with next/previous navigation
- **Video Popup** (Magnific Popup) for a "Watch Our Story" YouTube trailer
- **Testimonials Slider** powered by Swiper.js
- **Table Reservation & Contact Forms** with simulated submission states and success feedback
- **Newsletter Signup** with inline validation feedback
- **Scroll Animations** throughout the page using AOS (Animate on Scroll)
- **Fully Responsive Design** — built mobile-first with Bootstrap 5's grid system

---

## 🛠️ Tech Stack

| Category         | Technology                                   |
|-------------------|-----------------------------------------------|
| Markup / Styling  | HTML5, CSS3, custom `style.css`               |
| Framework         | Bootstrap 5.3                                 |
| Interactivity     | Vanilla JavaScript, jQuery                    |
| Animations        | AOS (Animate on Scroll)                       |
| Carousel / Slider | Swiper.js                                     |
| Lightbox / Popup  | Magnific Popup                                |
| Icons             | Font Awesome                                  |
| Fonts             | Google Fonts — Playfair Display, Poppins, Dancing Script |

---

## 📁 Project Structure

```
sarab-restaurant/
├── index.html
├── css/
│   ├── bootstrap.min.css
│   ├── aos.css
│   ├── swiper-bundle.min.css
│   ├── all.min.css
│   ├── magnific-popup.css
│   └── style.css
├── js/
│   ├── jquery-3.7.1.min.js
│   ├── bootstrap.bundle.min.js
│   ├── aos.js
│   ├── swiper-bundle.min.js
│   ├── jquery.magnific-popup.min.js
│   └── main.js
└── img/
```

---

## ⚙️ Getting Started

1. Clone or download the repository
2. Open `index.html` directly in your browser — no build step or server required

```bash
git clone https://github.com/your-username/sarab-restaurant.git
cd sarab-restaurant
open index.html
```

---

## 🧩 Key JavaScript Functionality (`main.js`)

- Scroll-based navbar state and active section highlighting
- Smooth-scroll navigation with automatic mobile menu collapse
- Search overlay open/close logic with category and trending-tag interactions
- Menu filtering system synced across filter buttons and category cards
- Menu item modal population from `data-*` attributes on each card
- Cart quantity controls and simulated "Add to Cart" flow
- Reservation and contact form submission simulation with success states
- Custom image gallery lightbox with keyboard (`Esc`) support
- Live countdown timer for the special offer section
- Newsletter subscription feedback
- Animated number counters triggered on scroll into view

---

## 📌 Notes

This project was built for practicing and showcasing front-end skills: DOM manipulation, event handling, responsive layout, and integrating third-party libraries (Bootstrap, jQuery, Swiper, AOS, Magnific Popup) into a cohesive, production-style landing page.

---

## 👤 Author

**Mohamed** — Full Stack Web Development Student
Focus: Angular (Frontend) & ASP.NET C# (Backend)

---

## 📄 License

This project is for educational and portfolio purposes.
