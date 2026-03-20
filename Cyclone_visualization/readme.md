# India Storm Analytics & Simulation Hub 🌪️

An interactive data visualization and simulation project exploring historical cyclone data in India from 1952 to 2024. This project combines data science analysis with a web-based simulation to show the impact and characteristics of major storm events.

## 🚀 Live Demo
The interactive simulation is deployed and accessible here:
**[https://cyclone-simulation.netlify.app/](https://cyclone-simulation.netlify.app/)**

---

## 📊 Project Overview
This repository contains an end-to-end analysis of tropical cyclones affecting the Indian subcontinent. It includes:
* **Data Analysis:** A deep dive into storm variables like wind speed, pressure, and economic impact.
* **Interactive Simulation:** A Leaflet-based map that animates storm paths and provides detailed event statistics.
* **Historical Dataset:** A curated CSV containing over 70 years of storm records.

## 📁 File Structure
* `index.html`: The core web application featuring the Leaflet.js map and storm simulation logic.
* `India_Strom_Dataset.csv`: The primary dataset containing historical records (Name, Date, Wind Speed, Pressure, Fatalities, etc.).
* `Storm_Visualization_2.ipynb`: A Jupyter Notebook containing Python-based data cleaning and advanced visualizations using Pandas, Matplotlib, and Seaborn.

## 🛠️ Tech Stack
* **Web Front-end:** HTML5, CSS3 (Tailwind CSS), JavaScript.
* **Mapping:** [Leaflet.js](https://leafletjs.com/) for interactive geospatial rendering.
* **Data Science:** Python, Pandas, Seaborn, Matplotlib.
* **Deployment:** Netlify.

## 📈 Key Features
* **Animated Storm Tracks:** Watch the path of cyclones from origin to landfall.
* **Dynamic Statistics:** Real-time updates of wind speed and pressure during simulation.
* **Historical Insights:** Exploratory Data Analysis (EDA) showing the correlation between storm intensity and economic loss.
* **Responsive Design:** Optimized for viewing on both desktop and mobile browsers.

## 📖 How to Use
1. **View the Analysis:** Open `Storm_Visualization_2.ipynb` to see the statistical breakdown of the storm data.
2. **Run Locally:** - Clone the repository.
   - Open `index.html` in any modern web browser.
   - Select a storm from the dropdown menu to trigger the animation.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
