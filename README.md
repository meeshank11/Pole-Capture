# Pole Capture App 

![Pole Capture App Icon](icon-192x192.png) <!-- Optional: Add if you have an icon -->

A Progressive Web App (PWA) for capturing pole locations on a map, including details like pole number, connected DT, and officer information. Built with Leaflet for mapping and SheetJS for exporting data to Excel.

## Features
- **Add Pole**: Place a draggable marker on the map, confirm its location, and enter pole details.
- **Locate Me**: Center the map on your current location using geolocation.
- **Generate Report**: Export all pole data to an Excel file (`Pole_Report.xlsx`).
- **PWA Support**: Installable on mobile devices via Chrome's "Add to Home Screen" feature.
- **Fixed Officers**: TSUISL Officer (Rahul Kumar) and GIS Officer (Meeshank Lal Jaiwardhan) are hardcoded and non-editable.

## Demo
This app is hosted on GitHub Pages: [https://your-username.github.io/pole-capture-app/](https://your-username.github.io/pole-capture-app/)  
*(Replace `your-username` with your actual GitHub username after enabling GitHub Pages.)*

## How to Use
1. **Open the App**:
   - Visit the GitHub Pages URL in a browser (preferably Chrome on Android).
2. **Install as PWA**:
   - On mobile, tap the three-dot menu in Chrome and select "Add to Home Screen" to install.
3. **Add a Pole**:
   - Click "Add Pole", drag the marker to the desired location, and click "Confirm Location".
   - Fill in the pole number and connected DT, then click "Confirm".
4. **Locate Yourself**:
   - Click "Locate Me" to center the map on your current position.
5. **Export Data**:
   - Click "Generate Report" to download an Excel file with all pole data.

## Files
- `index.html`: Main app file with HTML, CSS, and JavaScript.
- `manifest.json`: PWA manifest for app metadata and installability.
- `sw.js`: Service worker for PWA features (e.g., offline support).
- `icon-192x192.png` & `icon-512x512.png`: App icons (optional, add your own).

## Setup Instructions
1. **Clone or Download**:
   ```bash
   git clone https://github.com/your-username/pole-capture-app.git
   cd pole-capture-app
