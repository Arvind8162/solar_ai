# SolarScope – AI Powered Rooftop Solar Potential Analyzer ☀️

SolarScope is an intelligent web-based application that analyzes the solar potential of building rooftops using satellite imagery. It automatically detects roof shapes, simulates solar panel placement, estimates solar energy generation, and provides financial analysis to help users decide whether installing solar panels is beneficial.

The system works similar to Google Solar Potential / Project Sunroof but uses open-source technologies and APIs.

---

# 🚀 Features

### 1. Rooftop Detection

Automatically detects building roof areas from satellite maps.

### 2. Dynamic Roof Overlay

The detected roof polygon dynamically matches the actual roof shape.

### 3. Solar Panel Placement

Simulates optimal solar panel placement inside the detected roof area.

### 4. Manual Panel Control

Users can adjust the number of solar panels using a slider from **1 panel to maximum rooftop capacity**.

### 5. Solar Heatmap

Displays solar radiation intensity using a heatmap overlay.

### 6. Solar Energy Estimation

Calculates expected yearly solar energy production.

### 7. Cost & Savings Analysis

Provides financial insights including:

* Installation cost
* Yearly savings
* Break-even period

### 8. 20-Year Cost Comparison

Compares electricity costs **with solar vs without solar** using interactive charts.

### 9. Monthly Energy Production

Displays estimated solar energy generation for each month.

### 10. Location Search

Users can search any location directly on the map.

---

# 🧠 Advanced Features

* Shadow simulation from nearby trees and buildings
* AI-based solar panel orientation optimization
* Polygon-based panel placement inside roof boundaries
* Real-time financial analysis updates

---

# 🛠 Technology Stack

### Frontend

* SvelteKit
* Vite
* TailwindCSS
* JavaScript

### Mapping & Visualization

* Leaflet.js
* Leaflet Heatmap
* Satellite Map Tiles

### Data APIs

* NASA POWER API (Solar Radiation Data)
* OpenStreetMap Nominatim (Location Search)

### Data Visualization

* Chart.js

### Geometry Processing

* Turf.js

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/solarscope.git
cd solarscope
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open in browser:

```
http://localhost:5173
```

---

# 📊 How It Works

1. User searches or selects a location on the map.
2. The system detects the rooftop using satellite imagery.
3. A roof polygon overlay is generated.
4. Solar panels are automatically placed inside the roof area.
5. Solar heatmap shows sunlight intensity.
6. Solar energy generation is calculated.
7. Financial analysis and charts are displayed.

---

# 📈 Solar Calculations

Solar energy estimation is based on:

```
Yearly Energy =
Solar Radiation × Roof Area × Panel Efficiency × 365
```

Panel assumptions:

```
Panel Power ≈ 400W
Panel Area ≈ 1.7 m²
Efficiency ≈ 20%
```

---

# 💰 Financial Analysis

The system calculates:

* Installation Cost
* Yearly Electricity Savings
* Break-even Period
* 20-Year Cost Comparison

Electricity cost is estimated using user-defined monthly usage.

---

# 📷 Example Output

The application shows:

* Roof overlay on satellite map
* Solar panel placement preview
* Solar heatmap
* Cost comparison graph
* Monthly solar production chart

---

# 🔮 Future Improvements

* AI tree detection for accurate shadow analysis
* 3D roof slope detection
* City-scale solar potential analysis
* Mobile application support
* Government subsidy calculation   

---

# 👨‍💻 Author

Developed as a solar energy analysis project.

Student Name: **Arvind Hadiyal**
Project: **SolarScope – AI Powered Rooftop Solar Potential Analyzer**

---

# 📜 License

This project is developed for educational and research purposes.

