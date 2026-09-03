# NitroCarsApp
NitroCars App is an app developed for the electric vehicle charging industrsy. It makes use of a chatbot named Sne who is a warm, professional and polite AI that responds to common proplems faced by driver. It uses tools such as direct calling, Google Maps, Weather App. 
Project Overview
NitroCars Support Console (Sné AI) is an interactive, responsive web-based support dashboard designed for EV (Electric Vehicle) drivers in South Africa (featuring locations like Rosebank, Sandton, Melrose Arch, and Fourways). The application acts as an in-car or companion console where users can interact with an AI assistant named Sné to troubleshoot charging issues, buy payment vouchers, manage routes, check real-time station loads based on weather and peak times, and contact emergency services.
2. Key Features
Dynamic Sundial & Network Status: Interactive SVG network status ring that recalculates and visualizes station load percentages dynamically based on selected times of day (Morning, Midday, Evening, Night) and weather conditions (Clear, Heavy Rain, Cold).

AI-Powered Troubleshooting Assistant ("Sné"): Context-aware chat tabs handling multiple support categories:

Charging Assistant: Diagnose slow charging speeds, power-sharing across stalls, and hardware failure reporting.

Payment & Vouchers: Manage prepaid balances and instantly purchase R150, R300, or R500 vouchers, or bypass card failures with verified account remote-charge triggering.

Route & Station Finder: Direct integration hooks with Google Maps for location guidance.

Vehicle & Adapter Support: Vehicle port and CCS2 / Type 2 compatibility management.

Emergency & SOS: 24/7 priority hotline and immediate dispatch support.

General Info & Pricing: Nationwide pricing tiers, standard AC/DC tariffs, and off-peak discount schedules.

Interactive Pills & Simulator: Instantly toggle environmental conditions (weather/time) to watch the live station loads update in real-time.

3. Technologies & Tools Used
HTML5 / CSS3: Modern layout styled with custom CSS variables, flexbox, grid, and a sleek dark-themed industrial aesthetic (Basalt, Verdigris, and Redclay palette).

JavaScript (Vanilla ES6+): Pure client-side application logic driving state management, dynamic SVG rendering, conditional rendering, and event-driven simulated chat responses.

Google Fonts: Custom typography integration (Fraunces for headings and Manrope for UI text).

SVG (Scalable Vector Graphics): Custom inline icons and dynamically generated responsive circular sundial graphics.

External Integrations: Google Maps Search API protocol ([https://www.google.com/maps/search/?api=1&query=](https://www.google.com/maps/search/?api=1&query=)...) for location routing.

4. Setup Instructions
Because this is a self-contained single-file web application, setting it up for local use or deployment requires no complex build tooling (like Node.js, Webpack, or npm).

Method 1: Direct Browser Execution (Quickest)
Save the provided HTML code snippet into a file on your local machine, naming it index.html (e.g., index.html).

Double-click the file or drag-and-drop it into any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

Method 2: Local Development Server (Recommended for testing features)
If you are running a local code editor like Visual Studio Code:

Open the file inside VS Code.

Install the Live Server extension by Ritwick Dey.

Right-click anywhere in the editor code window and select "Open with Live Server".

The application will automatically launch and host locally inside your default browser window.
