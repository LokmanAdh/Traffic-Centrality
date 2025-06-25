# Centrality Map NYC

A web-based visualization tool that maps and analyzes centrality data and traffic volume across New York City using Leaflet.js.

## 🌐 Overview

This project displays spatial data for NYC intersections with centrality metrics and traffic volume. It's useful for urban planning, logistics, and transport analysis.

## ✨ Features

- Interactive map visualization
- Centrality analysis from geocoded CSV data
- Traffic volume overlays
- Responsive UI with real-time filtering
- Clean design using HTML, CSS, and JavaScript

## 📁 Project Structure

```
CentralityMap-main/
│
├── index.html                     # Main HTML file
├── script.js                      # JS logic for map and data rendering
├── data.json                      # GeoJSON or processed data
├── centrality_geocoded_nyc_cleaned.csv   # Cleaned centrality dataset
├── Traffic_Volume_Counts_20240221.csv    # Raw traffic volume data
├── assets/
│   ├── css/                       # Styling files
│   └── img/                       # Icons, images, and logos
└── README.md                      # This documentation
```

## 🚀 Getting Started

### Prerequisites

Just a modern web browser. No installation required.

### Running Locally

1. Download or clone this repository:
   ```bash
   git clone https://github.com/your-username/CentralityMap.git
   cd CentralityMap
   ```

2. Open `index.html` in any web browser.

> No build steps, servers, or packages are needed — it's a pure frontend project.

## 📊 Data Sources

- **centrality_geocoded_nyc_cleaned.csv**: Centrality metrics by intersection.
- **Traffic_Volume_Counts_20240221.csv**: NYC traffic volume data.

Data has been cleaned and geocoded for rendering on the map.

---

Made with ❤️ for urban data exploration.
