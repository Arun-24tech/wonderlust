Wanderlust - Travel Website
A travel website frontend built with HTML, CSS and vanilla JavaScript for a frontend development assignment. The page introduces the Wanderlust travel brand and displays a selection of travel destinations.
Technologies used
- HTML5 - page structure and content
- CSS3 - styling, layout and responsive design
- JavaScript - mobile navigation and active navigation link behaviour
Project structure
Wanderlust-Student/
├── index.html
├── README.md
├── css/
│   ├── reset.css
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── icons/
│   └── images/
└── design/
    ├── figma-mobile.png
    └── figma-tablet.png
Website sections
- Header and navigation menu
- Hero section with a booking call to action
- Featured destinations: Maldives, Swiss Alps, Safari Adventure and Tokyo City
- About Us section
- Footer with navigation and back-to-top link
JavaScript features
- Mobile menu opens and closes using the menu button.
- The menu closes when a navigation link is selected, when the user clicks outside it, or when Escape is pressed.
- The active navigation link updates as the user moves between page sections.
How to run locally
1. Download or clone this repository.
2. Open the Wanderlust-Student folder in Visual Studio Code.
3. Open index.html.
4. Right-click in the editor and select Open with Live Server. You can also open index.html directly in a browser.
5. No npm installation, framework, build tool, backend or database is required.
Figma reference and layout testing
The design/ folder contains the supplied mobile and tablet reference screenshots. Use Chrome DevTools responsive mode to compare the page at the same viewport widths as the references:
- Mobile reference: 394 px wide
- Tablet reference: 772 px wide
Keep the supplied image proportions and existing responsive layout when making changes. Compare screenshots at the same viewport size before adjusting CSS.
Customization
- Edit page text and destination details in index.html.
- Change colors, spacing, typography and responsive rules in css/style.css.
- Change browser reset styles in css/reset.css only when needed.
- Update menu and active-link behaviour in js/main.js.
- Replace photos and icons in assets/, keeping the paths in index.html correct.
Author
Arun Yadav
