# Charan Teja Pentakota – Portfolio

A personal portfolio showcasing my work, skills, and background as a Full Stack Web Developer and Engineering student.

##  Live Preview

Check out the website here: [portfolio-tb4d.vercel.app](--------------------)  



##  Table of Contents

- [About Me](#about-me)  
- [Technologies & Tools](#technologies--tools)  
- [Features](#features)  
- [Structure & File Overview](#structure--file-overview)  
- [Installation & Local Setup](#installation--local-setup)  
- [Customization Tips](#customization-tips)  
- [Contact](#contact)  
- [License](#license)

---

##  About Me

- Name: **Charan teja Petakota**  
- Title: *Full Stack Web Developer* and an undergraduate engineering student at **SRKR Engineering College**, Bhimavaram.  
- Passionate, growth-oriented, and enthusiastic about building impactful solutions.

---

##  Technologies & Tools

- **Frontend**: HTML, CSS, JavaScript  
- **Core Themes from Site**:
  - Responsive navigation menu  
  - Interactive skill accordion  
  - Services modals  
  - Portfolio slider (using Swiper.js)  
  - Scroll-based active section highlighting  
  - Sticky header and scroll-up button  
  - Dark/light theme toggle with `localStorage`

---

##  Features

- **Responsive Navigation Menu**: Toggleable mobile menu with open/close buttons and auto-close on link click.  
- **Skills Accordion**: Clickable sections that expand/collapse to show or hide details.  
- **Modals for Services**: Pop-up overlays that open when service buttons are clicked and close when the close icon is clicked.  
- **Portfolio Swiper Slider**: Interactive carousel displaying projects with looping, pagination, and navigation controls.  
- **Scroll-Activated Nav Links**: Dynamic highlighting of the active section in the nav menu.  
- **Header Styling on Scroll**: Adds styling to the header after scrolling past a certain point.  
- **Scroll-to-Top Button**: Appears when scrolling down to assist easy navigation back to the top.  
- **Dark/Light Theme Toggle**: Allows users to toggle site theme and persists preference via `localStorage`.

---

##  Structure & File Overview


portfolio/
├── index.html
├── css/
│ └── styles.css
├── js/
│ └── main.js
├── assets/
│ ├── images/
│ └── icons/
└── README.md




- **index.html**: Core layout including sections like Home, About, Skills, Qualification, Projects, Contact  
- **css/styles.css**: Handles all visual styles and responsive design  
- **js/main.js**: Contains JavaScript for interactivity: nav handling, accordion, modals, scroll effects, theme toggle  
- **assets/**: Directory for images, icons, fonts, and other static assets

---

##  Installation & Local Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/portfolio.git
    cd portfolio
    ```

2. Serve locally:
   - **Option 1**: Open `index.html` directly via your browser  
   - **Option 2 (recommended)**: Use Live Server if you have VS Code  
     ```bash
     npm install -g live-server
     live-server
     ```

3. Confirm:
   - Navigate the site  
   - Test menu toggles, skill accordion, modals, theme switch, scroll behavior, and the slider

---

##  Customization Tips

- **Add or Remove Sections**: Modify existing `<section>` tags and adjust nav links accordingly.  
- **Update Skills or Experiments**: Use the skills accordion structure for new items.  
- **Add Projects**: Add new slides to Swiper by replicating HTML structure and preview links.  
- **Change Theme Icons**: Update icon classes or swap SVG files as needed.  
- **Adjust Scroll Thresholds**: Modify `scrollY` thresholds (like 80px for header, 560px for scroll-up) in `main.js` for different behaviors.

---

##  Contact

- **Email**: charantejapentakota@gmail.com  

Connect with me via LinkedIn or GitHub using the links on the website.

---**linkedin**: https://www.linkedin.com/in/charantejapentakota/

##  License

This project is licensed under the **MIT License** – feel free to reuse, modify, and distribute.

---

*Build with passion and code that evolves—happy coding!*
::contentReference[oaicite:0]{index=0}

