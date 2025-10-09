# **Vijesh — Portfolio Website**

A fast, responsive personal portfolio built with **HTML**, **CSS**, and **JavaScript**.  
Skills and Projects are rendered dynamically from `skills.json` and `projects.json`.

---

## **Features**

- **Responsive sections:** Home, About, Skills, Education, Projects, Footer  
- **Dynamic data:** Skills from `skills.json`, projects from `projects.json`  
- **UI effects:** Typed.js, VanillaTilt, ScrollReveal, particles.js  
- **404 page:** Friendly not-found page for static hosting  

---

## **Tech Stack**

- **Frontend:** HTML, CSS, JavaScript (no framework)  
- **Libraries/CDNs:** jQuery, Typed.js, VanillaTilt, ScrollReveal, particles.js  

---

## **Project Structure**

```
PortfolioSite/
├─ README.md
├─ index.html
├─ projects.json            # Source of truth for Projects section
├─ skills.json              # Source of truth for Skills section
└─ assets/
   ├─ css/
   │  └─ style.css
   ├─ images/
   │  ├─ educat/
   │  ├─ projects/         # Project thumbnails (e.g., RPS.png)
   │  └─ ...
   └─ js/
      ├─ app.js            # particles.js configuration
      ├─ particles.min.js
      └─ script.js         # main site logic
```

---

##  **How It Works**

- `index.html` includes all UI sections and loads `./assets/js/script.js`.
- `assets/js/script.js`:
  - Fetches skills from `skills.json` and renders them inside `#skillsContainer`.
  - Fetches projects from `projects.json` and renders cards inside `#work .box-container` (first 10).
  - Initializes **Typed.js**, **VanillaTilt**, and **ScrollReveal** animations.
  - Handles **navbar toggle**, **smooth scrolling**, and **scroll spy** behavior.

---

##  **Data Files**

### skills.json
```json
{
  "name": "ReactJS",
  "icon": "https://img.icons8.com/external-tal-revivo-color-tal-revivo/48/000000/external-react-a-javascript-library-for-building-user-interfaces-logo-color-tal-revivo.png"
}
```

### projects.json
```json
{
  "name": "RPS GAME",
  "desc": "Rock Paper Scissor game developed using HTML, CSS, and JavaScript, and hosted using Netlify.",
  "image": "RPS",
  "links": {
    "view": "https://rpscenter.netlify.app/",
    "code": "https://github.com/vijesharumugam/RPS-Game"
  }
}
```


---


##  **Contact**

- **LinkedIn:** [linkedin.com/in/vijesh-arumugam](https://www.linkedin.com/in/vijesh-arumugam/)  
- **GitHub:** [github.com/vijesharumugam](https://github.com/vijesharumugam)  
- **Email:** [vijesharumugam26@gmail.com](mailto:vijesharumugam26@gmail.com)

---

## MIT License

Copyright (c) 2025 Vijesh A