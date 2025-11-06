# 🖥️ Mohamed Taha El Khoudimi — Interactive Desktop Portfolio

A personal portfolio website that simulates a modern desktop operating system to present my story, projects, and work experience in a creative and memorable way.
This site blends clean engineering, user experience, and visual design to reflect how I approach product building — clear structure, efficient functionality, and engaging detail.

---

## ✨ Core Concept

**Interactive OS Environment**

* Full desktop simulation with a taskbar, start menu, and draggable windows
* Smooth boot sequence, glass effects, and realistic micro-interactions
* Clickable folders and windows that open sections like *About, Resume, Projects, Skills, and Contact*

**Goal:** Deliver an immersive experience that feels like exploring a live workspace — representing my mindset as a product manager and builder.

---

## 🧠 About This Project

This portfolio demonstrates:

* How to blend **product thinking with front-end development**
* My preference for **simple, well-structured code** over frameworks that add complexity
* The ability to design and ship **interactive, lightweight web applications**

The project is fully static, optimized for performance, and deployable on free hosting such as **Vercel** or **Netlify**.

---

## 🛠️ Technical Overview

**Architecture**

* Object-oriented JavaScript with modular functions for content rendering
* Event-driven window management (drag, minimize, maximize, close)
* Efficient rendering and memory management for a smooth UI

**Visuals & Effects**

* Hardware-accelerated CSS animations
* Particle-based animated background
* Glassmorphism and subtle depth effects
* Adaptive design for desktop and mobile

**Audio System**

* Web Audio API used for procedural ambient music and sound control

---

## 📁 Main Sections

| Section      | Description                                                                    |
| ------------ | ------------------------------------------------------------------------------ |
| **About Me** | Overview of my journey, motivation, and product philosophy                     |
| **Resume**   | Experience with HireStudent, AstraSage, NTT, and Emporio Models                |
| **Projects** | Showcase of MVPs and tech projects demonstrating execution and learning        |
| **Skills**   | Technical and product skill set including Python, SQL, React, Product Strategy |
| **Contact**  | Email, LinkedIn, and GitHub links                                              |
| **Social**   | Additional online presence and collaborations                                  |

---

## 🚀 Getting Started

**Run locally**

1. Clone the repository
2. Open `index.html` in any modern browser
3. Click the **power button** to start the system
4. Explore using the desktop icons or keyboard shortcuts

**Deploy**

* **Vercel:** Connect your GitHub repo → Deploy → Add your Cloudflare domain
* **Netlify:** Drag and drop your project folder or connect GitHub
* **Traditional hosting:** Upload all files maintaining the same structure

---

## 🧩 Customization

Modify the following functions in `script.js` to update content:

```
getAboutContent()
getResumeContent()
getProjectsContent()
getSkillsContent()
getContactContent()
getSocialContent()
```

Edit `styles.css` to adjust:

* Theme colors and blur intensity
* Font families and typography scale
* Background particles or wallpaper image

Icons can be replaced in the `/icons` directory to personalize the desktop look.

---

## 📂 File Structure

```
portfolio/
│── index.html
│── styles.css
│── script.js
│── assets/
│   ├── Mohamed_Resume.pdf
│── icons/
│   ├── user.svg
│   ├── document.svg
│   ├── folder.svg
│   ├── code.svg
│   ├── mail.svg
│   └── network.svg
│── README.md
│── LICENSE
```

---

## ⚡ Performance & Compatibility

* Fully optimized DOM caching and throttled event handlers
* Works smoothly on **Chrome, Edge, Firefox, Safari**
* Requires modern browser support for:

  * ES6 JavaScript
  * CSS `backdrop-filter`
  * Web Audio API

---

## 🌐 My Story in Context

I’m **Mohamed Taha El Khoudimi**, a product-oriented engineer and founder who believes in building beautiful, functional, and socially meaningful products.
This website represents not just my work, but my values — consistency, quality, and creativity in everything I build.

Projects like **HireStudent** and **AstraSage** embody that vision — blending technology, business, and real-world problem solving.

---

## 📬 Contact

* **Email:** [mokhoudimi@gmail.com](mailto:mokhoudimi@gmail.com)
* **LinkedIn:** [linkedin.com/in/mtk1606](https://linkedin.com/in/mtk1606)
* **GitHub:** [github.com/mtk1606](https://github.com/mtk1606)

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to fork, remix, or use the template for your own portfolio with credit.

---

### Built with focus and persistence by **Mohamed Taha El Khoudimi**

> “Execution matters more than ideas — every great product starts small but consistent.”
