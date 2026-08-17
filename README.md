# Groningen Peat CO₂ Dashboard

> An interactive **Python Dash** dashboard for exploring peatland CO₂ emissions across Groningen and simulating potential reductions from water-level and infiltration interventions.

## 🌱 Overview

Peat meadow areas release CO₂ when artificially lowered groundwater levels expose peat soils to oxygen, accelerating peat oxidation and soil subsidence. The Province of Groningen aims to reduce emissions from these areas by **60 kilotons of CO₂ per year by 2030**, while maintaining viable agricultural use.

This project provides an interactive way to explore how different water-management strategies could contribute to this goal.

Users can:

- 🗺️ Select individual or multiple parcels on an interactive map
- 💧 Simulate raising summer groundwater levels
- 🌱 Compare different infiltration measures
- 📊 View current and simulated CO₂ emissions
- 📉 See resulting CO₂ reductions for selected parcels and across the study area
- 💦 Toggle water-management units on the map

## 🛠️ Technologies

- **Python**
- **Dash**
- **Plotly**
- **GeoPandas**
- **Pandas**
- **NumPy**
- **GeoJSON**

## 📊 Data

The dashboard uses publicly available Dutch geospatial and peatland-emissions data, including data derived from **SOMERS (Subsurface Organic Matter Emission Registration System)**.

The underlying data considers factors such as:

- Peat and soil characteristics
- Groundwater levels
- Parcel characteristics
- Infiltration measures
- Water-management units

The underlying datasets are not included in this repository where redistribution is restricted or unnecessary.

## 👥 Project

This was developed as a **team project for the Province of Groningen**, involving the development of an interactive tool from the initial concept through to a working demonstration.

**My contribution: Data preparation and analysis, including processing geospatial data, developing the parcel-level CO₂ calculation logic, and integrating the resulting data into the dashboard.**

## 🎯 Context

The project was developed in response to the Province of Groningen's objective of reducing peatland CO₂ emissions by **60 kt annually by 2030**.

The broader project also investigated how this target could be achieved with minimal water-level increases and how water-management units could potentially be improved by considering soil composition and land use.

## 📁 Repository Structure

```text
Groningen-Peat-CO2/
├── app.py
├── prepare_data.py
├── README.md
└── .gitignore
```
