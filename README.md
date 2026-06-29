# AI Foundation for Engineers (AIFE) — Course Projects Portfolio

This repository contains the projects completed for the **AI Foundation for Engineers** course at **REVA University, Bengaluru**.

---

## 🚀 Live Deployments

You can view the active live websites hosted via GitHub Pages below:

*   **Project 3 (Portfolio Homepage):** [https://arunkoli2102-collab.github.io/R25EJ014_AIFE_Project/](https://arunkoli2102-collab.github.io/R25EJ014_AIFE_Project/)
*   **Project 4 (The Daily Pulse News Website):** [https://arunkoli2102-collab.github.io/R25EJ014_AIFE_Project/project4_news_website.html](https://arunkoli2102-collab.github.io/R25EJ014_AIFE_Project/project4_news_website.html)

---

## 📂 Project Completion Status

| Project | File / Path | Tech Stack | Status | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Project 1** | [Project1_Hello.py](./Project1_Hello.py) | Python, Git | **Completed** (Smooth) | A simple script demonstrating setup, variables, formatted print statements, and initial GitHub commits. |
| **Project 2** | [Project2_Modelcard_googleGemma-4-12B-it.md](./Project2_Modelcard_googleGemma-4-12B-it.md) | Markdown, LLMs | **Completed** (Smooth) | A comprehensive model documentation card outlining specifications, capabilities, and system requirements for Google's Gemma 4 12B Instruct model. |
| **Project 3** | [index.html](./index.html) | HTML5, CSS3, Google Fonts | **Completed** (Fixed) | An interactive, single-page professional developer portfolio. Updated to showcase real projects with custom typography and hover micro-animations. |
| **Project 4** | [project4_news_website.html](./project4_news_website.html) | HTML5, CSS3, JavaScript | **Completed** (Fixed) | An elegant, fully responsive news portal featuring a scrolling marquee ticker, responsive grids (Technology grid columns fixed for mobile), and a functional newsletter script. |

---

## 🛠️ Fixes Implemented

### Project 3: `index.html` (formerly `Index.html`)
1. **GitHub Pages 404 Error Fix:** Renamed the filename from `Index.html` to `index.html` (lowercase). Linux-based web servers like GitHub Pages are case-sensitive; renaming it resolves the default route 404 error when navigating to your page URL.
2. **Typography & Styling:** Integrated the premium **Inter** and **Fira Code** Google Fonts in `<head>` and defined custom dashed underline transitions under project cards for enhanced aesthetic hover feedback.
3. **Replaced Placeholders:** Replaced all the generic `"Edit me"` texts in the **Skills** and **Projects** cards with your actual accomplishments (Project 1, 2, and 4) and linked them directly.

### Project 4: `project4_news_website.html`
1. **Mobile Grid Layout Bug:** The Technology section had inline styles (`grid-template-columns: repeat(2, 1fr)`) that overrode responsive media queries, causing columns to overflow on small phone screen resolutions (<560px). I refactored this inline style into a new stylesheet class `.tech-grid` with a mobile media query to stack items into a single column.
2. **CSS Selector Syntax:** Resolved a missing closing bracket `}` in the `footer .flogo` ruleset to prevent CSS cascading issues.

---

## 👤 Developer Profile
*   **Name:** Arun Koli
*   **Affiliation:** REVA University, Bengaluru
*   **Program:** B.Tech (Computer & Information Technology)
