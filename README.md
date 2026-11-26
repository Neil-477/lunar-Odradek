# 🌙 Lunar Odradek AI
### Blue Ghost: Terrestrial GPS Technology Revolutionizing Lunar Navigation

**Scan the Unknown • Detect the Danger • Find Safe Ground**

Lunar Odradek AI is an AI-powered lunar terrain analysis and hazard detection system designed to identify boulders and potentially dangerous terrain in lunar surface images. It aims to assist researchers and mission planners in identifying safer landing zones for lunar landers and rovers.

## 🚀 Project Overview

Lunar surfaces contain boulders, uneven terrain and hazardous regions that can pose risks to spacecraft during landing and exploration.

Lunar Odradek AI addresses this challenge using computer vision and deep learning. It uses a trained YOLO model to detect boulders, estimate their approximate sizes when image-scale metadata is available, generate terrain hazard maps and rank potential landing zones.

The system also features an interactive Odradek-inspired scanning interface that visually reveals detected objects and terrain analysis results.

## ✨ Key Features

- **Interactive Odradek Scanner:** Animated scanning interface that reveals processed image regions and AI detections.
- **AI Boulder Detection:** Uses YOLO to identify boulders with bounding boxes and confidence scores.
- **Boulder Size Estimation:** Estimates approximate real-world dimensions using available image-scale metadata.
- **Terrain Hazard Mapping:** Classifies terrain into Safe, Caution and Unsafe categories.
- **Landing Zone Ranking:** Scores candidate regions and suggests alternative landing areas.
- **Focused Rescanning:** Allows users to select specific regions for detailed analysis.
- **Mission Dashboard:** Displays detections, hazard maps, confidence scores and scan reports.

## ⚙️ Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python, JavaScript |
| Frontend | React, HTML, CSS |
| Backend | FastAPI |
| AI Detection | YOLO, PyTorch |
| Image Processing | OpenCV, Pillow |
| Data Analysis | NumPy, Pandas |
| Visualization | Plotly, Canvas, SVG |
| Database | SQLite / PostgreSQL |
| Version Control | Git, GitHub |

## 🔄 Project Workflow

1. **Image Collection:** Collect lunar surface images from NASA LROC.
2. **Image Preprocessing:** Clean, resize and normalize images.
3. **Image Tiling:** Divide large lunar images into smaller patches.
4. **Start Scanning:** Initialize the interactive scanning interface.
5. **Boulder Detection:** Run the YOLO model to detect boulders.
6. **Size Estimation:** Estimate dimensions using available scale or GSD metadata.
7. **Terrain Analysis:** Analyze boulder size, density and distribution.
8. **Hazard Mapping:** Generate Safe, Caution and Unsafe terrain classifications.
9. **Landing Zone Ranking:** Compare candidate regions and identify alternatives.
10. **Human Review:** Present recommendations for review by a qualified operator.

## 🏗️ System Architecture

The proposed architecture consists of seven major layers:

1. **Data Sources:** NASA LROC imagery, labelled boulder examples and image-scale metadata.
2. **Image Processing:** OpenCV-based validation, normalization and image tiling.
3. **AI Detection:** YOLO-based boulder localization and confidence scoring.
4. **Terrain Analysis:** Pixel-to-metre estimation, boulder density and hazard classification.
5. **Zone Ranking:** Risk scoring and candidate-region comparison.
6. **Backend & Storage:** Python, FastAPI and SQLite/PostgreSQL.
7. **Frontend & Review:** React-based scanner, hazard visualization and human-reviewed recommendations.

## 🛰️ Data Sources

The project is designed to use publicly available lunar imagery and related resources:

- NASA Lunar Reconnaissance Orbiter: https://lunar.gsfc.nasa.gov/
- NASA LROC Camera: https://www.lroc.asu.edu/
- NASA Planetary Data System: https://pds.nasa.gov/

## 🎯 Project Objectives

- Automate boulder detection in lunar surface images.
- Reduce the effort required for manual terrain inspection.
- Visualize potentially hazardous lunar regions.
- Compare and rank candidate landing zones.
- Provide an interactive platform for lunar terrain analysis.

## 🔮 Future Scope

- Improve detection accuracy using expanded and annotated lunar image datasets.
- Support larger and higher-resolution lunar surface images.
- Improve terrain analysis and hazard classification.
- Add detailed 3D terrain visualization.
- Expand support for different lunar exploration missions.

## ⚠️ Important Note

Lunar Odradek AI is intended as a decision-support prototype. Its recommendations are dependent on image coverage, scale metadata, model performance and configurable thresholds.

It does not provide certified landing decisions or replace qualified human assessment.

## 👨‍🚀 Team Omega Core

**Project:** Lunar Odradek AI  
**Team:** Omega Core  
**Team Leader:** Neil Kalyani  
**Track:** Software  
**Problem Statement:** SW-1

---

*Exploring the Moon
