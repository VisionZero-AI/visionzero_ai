# 🌐 VisionZero AI  
**Predictive Crash-Risk Mapping & Road Safety Intelligence**  
Built by **Anuar Aubakirov** — Founder of VisionZero AI & SmartCity AI  

---

## 🚦 Overview  
**VisionZero AI** is a geospatial + machine learning approach for predicting high-risk road segments, identifying crash patterns, and generating safety-intelligence layers for cities.

This repository includes **public map outputs only**, created for:
- Civic transparency  
- City planning  
- Safety analysis  
- San José Innovation Hub submissions  
- Public use during evaluations  

The **SmartCity-AI Engine** powering these outputs is **private**, proprietary, and not part of this repository.

---

## 📂 Repository Contents  
visionzero_ai/
├── deployedmapSJNetlify/
│ ├── index.html # Public landing page for Netlify deployment
│ ├── sj_pred_top5pct_ranked.csv # Ranked top 5% highest-risk segments
│ ├── sj_pred_top_segments.geojson # Predicted high-risk road segments
│ ├── sj_truth_ksi_heat.geojson # Ground-truth historical KSI heatmap
│ └── visionzero_san_jose_map.html # Interactive folium map (large HTML)
├── docs/
│ ├── README.md
│ ├── overview.md
│ └── methodology_high_level.md # High-level explanation for officials
├── .gitignore
└── README.md

---

## 🌟 Public Assets Included  
These files are **safe for public release** and contain **no source code**:

### ✔ **Predicted Top 5% Crash-Risk Segments**  
- Ranked CSV  
- GeoJSON map visualization

### ✔ **Ground-Truth KSI Heatmap**  
Historical severe crashes mapped for comparison.

### ✔ **Public Interactive Map**  
`visionzero_san_jose_map.html`  
Static Folium output used for:
- San José Innovation Hub presentation  
- Public transparency  
- Demonstration of predictive capability

### ✔ **Static Landing Page**  
`index.html` for simple deployment on Netlify or GitHub Pages.

---

## 🔐 What Is *Not* Included  
This repo does **NOT** include:
- ML training pipeline  
- SmartCity-AI Engine code  
- Feature engineering  
- EB smoothing logic  
- Road segmentation algorithm  
- PostGIS / PostgreSQL schema  
- XGBoost training  
- Model parameters  
- Full city datasets  

These components are **private**, protected, and stored in `smartcity-ai-engine` (private repo).

---

## 🧭 Intended Use  
This repository is provided for:
- City innovation evaluations  
- Research and civic review  
- Demonstrations of predictive mapping  
- Public transparency during pilot discussions  

Commercial or derivative use is **not permitted** without written permission.

---

## 👤 Author  
**Anuar Aubakirov**  
Founder — VisionZero AI & SmartCity AI  
AI Engineer • Civic Tech Innovator • Geospatial Analyst  

📧 anuar.aubakirov@gmail.com

---

## 🛡️ License  
This project is proprietary.  
See **LICENSE** file for full terms.

