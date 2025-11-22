🧠 VisionZero AI — High-Level Methodology
How the Crash-Risk Prediction System Works (Public Summary)

This document provides a safe, high-level description of how VisionZero AI identifies crash-risk patterns.
It is designed for innovation hubs, city planners, public agencies, and reviewers, without revealing proprietary code.

1. 📌 Data Inputs (Public-Level)

VisionZero AI uses public and city-provided datasets such as:

Historical crash records

Roadway geometry and centerlines

Functional class (local, arterial, expressway)

Speed limits

Temporal patterns (time of day, weekday/weekend, seasons)

Surrounding land use / special zones (schools, transit stops, commercial corridors)

All sensitive datasets remain private.

2. 📌 Feature Engineering (High-Level)

VisionZero AI transforms geospatial data into useful features:

▪ Road Geometry Features

Segment length

Curvature / straightness

Number of lanes

Intersection density

Road grade (slope)

▪ Temporal Features

Hourly, daily, seasonal crash trends

Night/day patterns

Weekday vs weekend differences

▪ Severity Features

Weighted scoring for fatal/severe crashes

Severity index per segment

▪ Contextual Features

Schools / parks proximity

Transit stops

Pedestrian activity zones

⚠️ Proprietary SQL queries, preprocessing pipelines, and feature engineering code are not included.

3. 📌 Predictive Modeling (Public Summary)

VisionZero AI uses a combination of machine-learning and statistical techniques to predict risk:

Gradient Boosted Trees (GBM/XGBoost style methods)

Random Forests

Logistic Regression (baseline)

Empirical Bayes smoothing for hotspot consistency

This document describes the concept, not the real training code or model weights.

4. 📌 Corridor-Level Aggregation

Instead of point-based mapping, VisionZero AI produces risk corridors:

Crash points → road segments → functional corridors

Risk scores smoothed across adjacent segments

Severity and exposure considered

Corridors ranked by historical + predicted risk

This is what cities like San José value the most.

5. 📌 Public Output Layers

The public version includes:

Crash heatmaps

Severity-weighted risk locations

Risk corridors (concept version)

Behavioral risk filters (speeding, DUI, nighttime, etc.)

These layers help cities:

Prioritize engineering upgrades

Justify grants (SS4A, HSIP)

Direct enforcement more efficiently

Improve Vision Zero action plans

6. 🔐 Proprietary Components (Not Public)

The following remain private in the SmartCity AI Engine:

SQL/PostGIS pipelines

Real model training scripts

Data ingestion & cleaning workflows

Real-time flood/crash integration

Feature generation logic

Predictive hazard routing engine

Private datasets or city-owned data

Model weights

These protect both your IP and operational security.

7. 🎯 Purpose of This Document

Give cities transparency

Show technical maturity to innovation hubs

Provide evidence for federal grants

Support future pilots (San José, Pittsburgh, etc.) without exposing IP
