# Air Quality Monitoring Dashboard

A fully responsive, browser-based dashboard for real-time air quality monitoring. This dashboard visualizes key environmental indicators such as PM2.5, PM10, CO₂, temperature, humidity, and AQI. It uses simulated data but can be extended to connect with real sensor feeds or backend APIs.

---

## Project Overview

Air quality monitoring is essential for assessing environmental pollution and its impact on human health. This dashboard demonstrates how to monitor and visualize air pollutants and environmental conditions dynamically through an easy-to-open HTML file that runs entirely in the browser.

The project simulates sensor readings to provide real-time data visualizations and health advisories based on US EPA AQI standards. It is ideal for educational, hobbyist, or prototype use.

---

## Features

- **Live Metrics:** Displays six critical air quality metrics (PM2.5, PM10, CO₂, Temperature, Humidity, AQI) with dynamic color-coded cards reflecting risk categories.
- **Realtime Charts:** Animated line charts for partial and historical data trends.
- **Health Advisory:** Contextual messages based on AQI to guide users' exposure and safety.
- **Recent Readings Modal:** Displays the last 15 sensor readings with options to refresh or export data as CSV.
- **Control Buttons:** Allows pausing/resuming updates and manual refresh.
- **Fully Responsive:** Works on desktop, tablets, and mobile devices.
- **Self-Contained:** Requires only an internet connection to load Chart.js. No backend required for simulations.

---

## Understanding Key Metrics

- **PM2.5 and PM10 (µg/m³):** Fine and coarse particulate matter; high levels damage respiratory and cardiovascular health.
- **CO₂ (ppm):** Carbon dioxide concentration indicates air freshness and ventilation level.
- **Temperature (°C) and Humidity (%):** Meteorological indicators influencing air quality and comfort.
- **AQI (Air Quality Index):** A composite index calculated primarily based on PM2.5 levels using EPA guidelines to provide a risk level from Good to Hazardous.

---

## Usage Instructions

### Running the Dashboard

1. Download or copy `air-quality.html` to your computer.
2. Open the file by double-clicking or right-clicking → Open With → your preferred modern browser (Chrome, Firefox, Edge, Safari).
3. The dashboard will start simulating real-time data immediately.

### Interacting with the Dashboard

- **Refresh:** Click to fetch an immediate new sensor reading.
- **Pause/Resume:** Toggle live data updates.
- **View Recent Readings:** Opens a modal with a table of the last 15 readings, which you can manually refresh or export as CSV.

---

## Extending This Project

For real-world applications or advanced prototypes, you can:

- Replace simulated data in the JavaScript with real sensor data by calling your REST API endpoints.
- Add support for more pollutants like ozone (O₃), nitrogen dioxide (NO₂), or sulfur dioxide (SO₂).
- Introduce alerts and notifications based on threshold exceedances.
- Incorporate map-based visualization highlighting sensor geographic locations.

---

## Project Structure

# airquality-dashboard
