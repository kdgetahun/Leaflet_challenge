# 🌍 Leaflet Earthquake Visualization  

## Overview  
This project is designed to visualize earthquake data using **Leaflet.js**, sourced from the **United States Geological Survey (USGS)**. The visualization allows users to explore real-time earthquake activity worldwide, with markers representing the magnitude, depth, and location of each event.  

## Project Features  
✅ **Interactive Map:** Displays earthquake locations using Leaflet.  
✅ **Magnitude Representation:** Larger markers indicate stronger earthquakes.  
✅ **Depth Representation:** Color-coded markers show earthquake depth.  
✅ **Popups:** Clickable markers provide additional earthquake details.  
✅ **Legend:** Explains marker colors and magnitude ranges.  
✅ **(Optional) Tectonic Plate Data:** Additional overlay showing tectonic plates.  
✅ **(Optional) Layer Controls:** Users can toggle datasets and base maps.  

---

## Part 1: Earthquake Visualization  
In this section, we:  
- Retrieved real-time earthquake data from the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).  
- Plotted earthquake locations based on **latitude** and **longitude**.  
- Adjusted **marker size** based on earthquake magnitude.  
- Colored markers based on earthquake **depth**.  
- Added popups displaying earthquake details.  
- Implemented a **legend** to clarify data visualization.  

---

## Part 2: Advanced Features (Optional)  
- Integrated **tectonic plate data** from [Fraxen’s Tectonic Plates Repository](https://github.com/fraxen/tectonicplates).  
- Allowed users to switch between different **base maps** (e.g., satellite, terrain, etc.).  
- Separated earthquakes and tectonic plates into **toggleable overlays**.  
- Added **layer controls** for customization.  

---

## Technologies Used  
- 🗺️ **Leaflet.js** – For interactive map rendering  
- 📊 **D3.js** – Fetching and processing JSON data  
- 🌎 **USGS API** – Real-time earthquake data  
- 🗂️ **GeoJSON** – Data format for mapping  
- 💻 **HTML, CSS, JavaScript** – Core web technologies

---

## Credits  
- 🔹 **Data Source:** [USGS Earthquake API](https://earthquake.usgs.gov/)  
- 🔹 **Tectonic Plate Data:** [Fraxen’s Repository](https://github.com/fraxen/tectonicplates)  
- 🔹 **Map Library:** [Leaflet.js](https://leafletjs.com/)  
