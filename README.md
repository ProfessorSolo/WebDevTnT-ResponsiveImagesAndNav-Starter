# A03 — Responsive Images & Navigation

A hands-on starter project for building a fully responsive page that adapts gracefully across devices. You’ll work with modern image techniques, mobile-first navigation patterns, and clean layout refactoring.

🚀 What You’ll Build

This project guides you through transforming a static page into a responsive, performant experience using:
	•	Proper image containment
	•	srcset and sizes for adaptive image loading
	•	The <picture> element for art direction
	•	Breakpoint-controlled background images
	•	A mobile-first navigation system
	•	A custom animated hamburger menu
	•	A smooth switch from mobile nav → desktop nav

By the end, you’ll have a standalone responsive layout showcasing modern best practices.

⸻

📂 What’s Inside

This starter pack ships with:
	•	HTML skeleton – Structure for banner, gallery, feature image, and navigation
	•	CSS base styles – Layout, typography, mobile-first setup
	•	JavaScript stub – Hook for your hamburger toggle
	•	Image variants – Multiple sizes and crops for testing responsive image loading

⸻

🛠 Your Tasks

1. Image Containment

Ensure all images respect their layout and never overflow their containers.

2. Add Responsive Images

Upgrade the banner and gallery images using:
	•	srcset
	•	sizes
	•	width-based switching

3. Art Direction with <picture>

Convert the featured image to a <picture> element and serve a different crop at a chosen breakpoint.

4. Background Image Performance

Load a decorative background image only at wider screen sizes using media queries.

5. Build the Mobile Navigation

Create:
	•	A custom animated hamburger icon
	•	A mobile-first menu (slide-in, dropdown, or overlay—your call)
	•	JavaScript to open/close the menu
	•	An overlay that disables scrolling when the menu is active

6. Desktop Navigation

At a desktop breakpoint, swap the hamburger menu for a clean, traditional nav layout.

⸻

🔍 How to Test Responsiveness
	•	Use browser dev tools for device emulation
	•	Hard-refresh after resizing to confirm which image variant actually loaded
	•	Throttle network speeds to test loading behavior
	•	Inspect the chosen image URL in DevTools > Network

⸻

💡 Tips
	•	Build mobile first, then scale up.
	•	Keep animations subtle and performant.
	•	Choose breakpoints based on layout, not device models.
	•	Comment your code — future you will thank you.

⸻

📜 License

WebDevTnT Learner License 1.0 (WebDevTnT-LEARN-1.0)

Copyright © 2025 Professor Solo

This project is released under the WebDevTnT Learner License, which allows you to learn from, modify, and experiment with the code for personal skill-building, demos, and portfolios.
Commercial reuse or redistribution of the template as-is is not permitted.

See the included WebDevTnT Learner License file for full details.
