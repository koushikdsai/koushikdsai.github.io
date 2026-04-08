Hey! This is my portfolio website built to showcase my work, skills, and journey as a B.Tech student in Artificial Intelligence & Data Science.
This repository contains a personal portfolio website built using pure HTML and CSS.
No frameworks or libraries were used — the goal was to understand layout, responsiveness, and UI design from the ground up.
The HTML file is divided into clear sections using semantic structure and IDs for navigation.


Website Live Demo:
https://koushikdsai.github.io/


HTML Structure
1. For Navigation Bar Fixed at the top using CSS,Contains anchor links etc,Enables smooth scrolling between sections.
2. For Hero Section,Intro section with name, role, and buttons,Uses a flexbox layout to split. Left - Text content Right - Profile image, Includes stats and call-to-action buttons.
3. For About Section,Two-column layout Left - Description text + tags, Right - Interest cards,Implemented using CSS Grid.
4. For Education Section, Structured as rows, Each row contains - Index number,Institution + details,Year,Uses grid for alignment.
5. For Projects Section, Grid-based layout, Each project is a card with-Title, Description, Tech stack tags, GitHub link, One featured project spans full width.
6. For Skills Section, Multiple cards grouped by category, Each skill uses - Progress bar Organized using CSS Grid.
7. For Certifications & Hackathons, Card-based layout, Uses grid for responsiveness.
8. For Contact Section, Displays contact info and social links, Structured using flex/grid layout
9. For Footer, Simple navigation and credits

CSS Structure
1. Root Variables:
:root {--bg, --cyan, --purple, etc.}
Defines theme colors and Makes design consistent and easy to update.
2. Global Styles Resets margins and paddings, Set font family, Enable smooth scrolling.
3. The Layout Systems Used Flexbox Navbar, Hero section, Buttons and small layouts and The CSS Grid Used for About section, Projects grid, Skills grid, Certifications, Hackathons.
4. Components like Reusable styles include-.proj-card means Project cards,.sk-card means Skill cards,.cert-card means Certification cards, .hack-card means Hackathon cards.
Each component has: Hover effects, Border transitions, Shadows and animations
5. Responsive Design, Media queries are used to adapt layout- Tablet (max-width: 900px), Grid becomes single column, Navbar links hidden,
and Hero section stacks vertically, Mobile (max-width: 600px), Further spacing adjustments, Smaller grids and it has Better readability.
