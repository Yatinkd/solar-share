SolarShare
A simple two-page web app that calculates rooftop solar potential using only HTML + CSS + JavaScript.
No backend. No database. Everything runs in the browser.
📌 What It Does
User enters rooftop details
App instantly calculates:
Solar capacity (kW)
Annual energy (kWh)
CO₂ savings (tonnes/year)
Money saved per year
Suitability score
Opens a beautiful results page
No data stored anywhere (client-only)
🗂 Files
index.html     → Form page
results.html   → Results page
README.md      → Project info
🛠 How It Works
Calculations done using simple JavaScript formulas
Data passed between pages using sessionStorage
Leaflet used for map display
Fully mobile-responsive (Bootstrap)
🚀 Deploy on GitHub Pages
Upload all files to the repository root
Go to Settings → Pages
Enable Pages on the main branch
Site will be live at:
https://your-username.github.io/your-repo/
🧪 Local Testing
Just open index.html in any browser
OR run:
python3 -m http.server 8000
🧩 Tech Used
HTML
CSS (Bootstrap)
JavaScript
Leaflet.js
sessionStorage
