# CHANEL E-Commerce Front-End Showcase

A luxury e-commerce showcase page inspired by CHANEL, covering multi-category product lines including **Shoes, Handbags, Jewellery, and Clothes**, complete with interactive UI and video elements.

> This project was developed in **2022** as a hands-on learning practice for core web development and layout techniques. Refactoring and modernization are planned for future updates!

⚠️ **Note on Assets**: While based on CHANEL's aesthetic, most product photos and media assets used in this project were sourced directly from the official CHANEL website for personal educational and portfolio demonstration purposes only.

---

## 🎨 Layout & Technical Features

Built using purely native web development skills without any external frameworks or libraries:

* **Typography & Styling**: Imported Google Fonts (`Cinzel`, `Exo`, `Kaushan Script`, `GFS Didot`, etc.) to match luxury brand aesthetics, using CSS pseudo-elements (`::after`, `::before`) for customized section borders and decorative line accents.
* **Flexbox Grid System**: Extensively utilized CSS Flexbox (`display: flex`) across multi-category product grids (`.product-shoes`, `.product-handbags`, `.product-jewellery`, `.product-clothes`) and responsive layouts (`.row`).
* **Responsive Breakpoints**: Configured custom media query breakpoints for smooth mobile adaptability:
  * **`1239px`**: Optimizes layout distribution for desktop and wide screens.
  * **`756px`**: Rebuilds mobile view with a fixed slide-out navigation overlay (`position: fixed`).
* **Interactive UI & Hover Effects**: Embedded CSS `:hover` states on product Quick View links, navigation, social icons, and smooth image scale transitions (`transform: scale(1.15)`) on video thumbnail sliders.
* **Dynamic Media Switcher**: Integrated lightweight vanilla JavaScript (`document.querySelector(".slider").src`) to dynamically switch featured video sources.

---

## 💖 Credits & Acknowledgements

The visual elements and brand design concepts in this application were inspired by or sourced from:

### 👜 Brand Inspiration & Media Assets
* All product photos, brand logos, and copy belong exclusively to **[CHANEL](https://www.chanel.com)**.

### 🖼️ Icon Attributions
* Social media icons (Instagram, Facebook, etc.) used in the footer and navigation buttons are standard third-party vector assets.

---

*Feel free to star ⭐ this repository if you enjoy this front-end showcase!*