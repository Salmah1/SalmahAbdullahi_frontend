# SCWonline - Register Page (HTML / CSS)

## Approach
- Built a static, semantic HTML layout that closely matches the provided Figma register page.
- Used a simple structure: 
	- Utility bar
	- Navigation bar
	- Hero section
- Styling is handled with plain CSS using reusable variables and flexbox for alignment.
- Added responsive breakpoints so the layout adapts cleanly from desktop to mobile.

## Assumptions
- This is a frontend prototype (no real routing, authentication, or form submission logic implemented).
- The “increase text size” and language toggle are UI only (buttons included for layout/accessibility, but no JS behaviour implemented.
- The goal is visual consistency with the prototype and clean responsiveness rather than building a full component framework.


## Tech choices 
- HTML5 and CSS only for a lightweight, easy to review implementation.
- CSS variables (:root) to centralise colours and keep the design consistent and easy to update. 
- Flexbox for used for utility/navigation alignment and the hero two column layout.
- Responsive media queries to reflow content, prevent overflow, and keep padding/layout consistent on smaller screens.
