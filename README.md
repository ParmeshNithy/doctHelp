This project is a single-page web application for doctHelp.ai, an AI-powered clinical decision support system for healthcare providers[search_files_v2:1]. The app transforms patient presentation details into actionable, evidence-based clinical recommendations through a user-friendly interface directly in the browser

Project Overview
doctHelp.ai lets clinicians enter a patient's clinical case and receive prioritized diagnostic and management recommendations supported by medical evidence. The platform simulates backend API logic directly in-browser, so no server setup is required for demonstration use

Features
Modern, responsive UI built with Tailwind CSS

Patient scenario input and demo UI for clinical analysis.

Real-time, evidence-based clinical recommendations with citations and success probabilities.

Additional helper tools like demo request form, contact sales, and testimonials.

Entire project is static and runs without external backend dependencies (all logic is mock-simulated in browser).

File Structure
index.html (or the main HTML file): Contains all markup, styles, and JavaScript needed for the app, including UI, data simulation, and logic

Installation
No formal installation is required. To run the app:

Download or clone the project files to a local folder.

Open the HTML file (e.g., index.html) in any modern web browser (Chrome, Edge, Firefox, Safari)

Requirements
A modern web browser (latest version recommended)

Internet connection for external CDN dependencies (Tailwind CSS, Font Awesome, Google Fonts)

No Python, Node.js, or additional installation steps are required for demonstration/learning purposes

How It Works
The app uses HTML, Tailwind CSS, and vanilla JavaScript, with some UI animation and event-handling extensions

Patient case analysis and recommendation logic are simulated in the browser JS (using local storage and timeouts for fake backend processing)

Forms like "Request Demo" and "Contact Sales" use local storage as a placeholder backend

Customization & Extension
To customize UI: Edit the HTML markup and Tailwind style classe

To extend logic: Modify/add case logic or recommendation templates under JavaScript sections handling analyzeQuery and related methods

For real production or EMR integration, actual backend APIs and clinical data infrastructure would be needed (not included in this demo)

Credits
UI components leverage Tailwind CSS, Font Awesome, and Google Fonts served via CDN.

Sample medical logic and recommendations are illustrative and for demonstration only; not for clinical use.

License
For demo and educational purposes. For commercial use, please consult the authors or maintainers.
