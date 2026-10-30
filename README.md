# Eloi Cañigueral – Personal Portfolio

Single-page static website that presents my CV, skills and a selection of my projects.

- **GitHub Page:** https://eloicanigueral.github.io/personal-website/
- **Figma:** [CV Mockup](https://www.figma.com/design/cpEnaDFfGamlEgZdWQICbH/CV-mockup?node-id=0-1&t=7qE7qvnVhCM8Zvxb-1)



## 1. User Profile
The design of this website is primarily aimed at tech recruiters, who are actively looking to hire junior profiles or students for tech teams. 

This type of user typically has limited time and needs to quickly and efficiently evaluate whether a candidate has the required technical skills. Therefore, they look for a clean website without unnecessary distractions, where they can immediately find:
- Current academic background as a Computer Engineering student.
- A clear and organized summary of technical skills (programming languages, tools, web environments).
- Direct access to real projects through code repositories or demos to verify work quality.
- Fast and direct contact methods (email, LinkedIn) along with the option to download an extended resume in PDF format with a single click.




## 2. Information Architecture
 The website is a **single page** where all the information is one click away through smooth scrolling.

1. **Top Navigation Bar:** It stays fixed at the top of the screen (through `position: sticky`) so the user can instantly jump between sections (`About`, `Projects`, `Contact`) at any point without long scrolling.
2. **Main Section:** Acts as an immediate visual introduction with a large headline defining my profile ("Computer Engineering student who likes to understand how things work") alongside quick contact links.
3. **About Section:** A short presentation, one sentence about my previous jobs (which show soft skills such as being organized and a good teammate) and my technical skills grouped in four categories (Programming, Web, Tools and Apps), displayed as pill-shaped tags.
4. **Projects Section:** Acts as the professional portfolio. It presents highlighted projects vertically with brief descriptions and languages used, incorporating a hover animation effect.
5. **Contact Section and Footer:** Closes the page by centralizing all communication channels and includes a prominent button to open the PDF resume directly, successfully wrapping up the recruiter's visit.


I deliberately did not create separate Experience or Education sections. My previous job positions were not related to IT, so they are summarized in a single line, reserving full details for the downloadable PDF CV. This keeps the page short and focused on what is relevant for the recruiter.


## 3. Visual Design

Visual design decisions focus on delivering a clean, modern, and technological profile, putting all the focus on readability and content hierarchy.

- **Inspiration:** The visual direction is inspired mainly by two portfolios I found while researching: [Pablo Sánchez](https://pavlosanchez.com/) (for the dark background and the minimal look) and [Onur Çoban](https://www.onur.design/) (for large typography and the thin separator lines). I was also inspired by other websites for the pill-shaped skill tags and the hover effect in the projects list.
- **Color Palette:** Dark theme with a very limited palette defined as CSS variables. It features a black background (`#101010`) combined with white text (`#f4f4f4`), grey for the secondary information (`#9a9a9a`), and a darker grey for the separator lines (`#2e2e2e`). A single red color (`#e64b4b`) is used strictly for interactive elements (such as the project hover state and contact link underlines) to make clickable items instantly recognizable.
- **Typography:** The design uses one single font family: **Verdana**. The hierarchy is created with size and weight: a very large headline in the hero (whose second half is grey), bold text for the key sentences, and small grey text for secondary information. The section titles (`/about`, `/projects`, `/contact`) are written in italic with tight letter spacing, which gives the page a more personal touch.
- **Layout:** The layout is built with CSS Grid and Flexbox. Every section uses the same three-column grid: the title sits in the left column and the content in the central one, leaving empty margins on both sides. This makes the page predictable and easy to scan. Each section takes up most of the height of the screen, with its content vertically centered, so the visitor focuses on one idea at a time. Thin horizontal lines separate the sections and the projects.
- **Adaptability:** The page is designed for desktop screens and looks as intended on a 1920x1080 laptop. On a larger monitor (2560x1440) it also works, but there is more empty space around the content. A mobile version is planned as a future improvement.
 
---
