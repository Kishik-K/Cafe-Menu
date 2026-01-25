# ☕ Camper’s Café — Responsive Menu UI

Camper’s Café is a responsive, aesthetic café menu interface built with a strong focus on layout adaptability, UX correctness, and visual restraint.
The project explores how a single dataset can be presented through multiple layout paradigms while maintaining clarity, consistency, and smooth interaction.

This is not a static design — it is a view-adaptive UI.

Check out the live demo: [View Camper Cafe Menu](https://kishik-k.github.io/Cafe-Menu/
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/299e14fb-8b2b-4d15-b68a-f5898896275f" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/42c604ef-51d0-45ca-8006-c121d2fbe16a" />


)

✨ Key Features

List View & Card View Toggle
Users can switch between a clean, editorial list layout and a modern card-based layout.
The toggle is UX-safe: interactions are disabled mid-transition to prevent state conflicts.

Smooth Layout Transitions
Transitions are handled without layout snapping by isolating animation layers, ensuring symmetry when switching between views.

Mode-Aware Background System
The page background subtly adapts to the active view mode, reinforcing context without distracting from content.

Mobile-First Responsiveness
Menu items adapt intelligently across screen sizes:

Desktop: aligned name–price rows

Tablet: increased touch spacing

Mobile: stacked layout with improved readability

Sticky Section Headers (Mobile)
Category headers remain visible while scrolling on smaller screens, improving navigation and usability.

Clean, Icon-Free Visual Design
A warm, café-inspired color palette with restrained typography and elevation — focused on clarity rather than decoration.

🛠 Tech Stack

HTML5 — semantic structure

CSS3 — Grid, custom properties, responsive design

Vanilla JavaScript — view toggling, transition control

No frameworks or libraries

🎯 Design & Engineering Goals

Prioritize UX correctness over visual gimmicks

Avoid layout jank during complex transitions

Ensure accessibility-friendly spacing and readability

Keep the codebase understandable and extendable

📱 Responsive Behavior Summary
Device	Behavior
Desktop	Two-column card view / aligned list view
Tablet	Touch-friendly spacing, adaptive typography
Mobile	Sticky headers, stacked items, clean price separation
🚀 Why This Project

This project was built to practice real-world frontend decision making:
handling layout changes, animation timing, responsiveness, and user interaction states — not just styling.

*Built with ☕ and lots of CSS*
