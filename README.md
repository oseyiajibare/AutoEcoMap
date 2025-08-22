# AutoEcoMap - AI-Powered QGIS Plugin

**Description:**  
AutoEcoMap is a QGIS plugin that automatically detects, generates, and dynamically updates natural features using AI and real-time environmental data. It leverages computer vision models, generative mapping, and live API data integration to enhance mapping workflows for terrain, vegetation, water bodies, and other natural features.

---

## **Features**

- **Smart Feature Recognition:** Automatically detect rivers, lakes, forests, and wetlands from satellite imagery.  
- **Generative Mapping AI:** Generate realistic terrain and ecological features using DEM and climate data.  
- **Real-Time Data Sync:** Dynamically update layers with live environmental data like rainfall, vegetation, and disaster alerts.  
- **Intuitive UI:** Simple dockable panel with three tabs: Detect, Generate, and Sync.

---

## **Installation**

1. Download the latest release `.zip` from [Releases](https://github.com/oseyiajibare/AutoEcoMap/releases).  
2. Open QGIS → Plugins → Manage and Install Plugins → Install from ZIP.  
3. Activate the plugin from the Plugin Manager.

---

## **Requirements**

- QGIS 3.16 or higher  
- Python packages: `torch`, `torchvision`, `geopandas`, `rasterio`, `numpy`, `requests`, `Pillow`  

Install dependencies using:

```bash
pip install -r requirements.txt
