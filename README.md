<div align="center">
  <h1>🥢 Discover Kunshan · 昆山美食文化互动地图</h1>
  <p><strong>Interactive Cultural Food Map · INFO301 Final Project</strong></p>

  <p>
    <a href="front.html" style="display:inline-block;margin:4px 6px;padding:10px 18px;border-radius:999px;background:#1f74ff;color:#ffffff;text-decoration:none;font-weight:600;">Live Demo</a>
    <a href="https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html" style="display:inline-block;margin:4px 6px;padding:10px 18px;border-radius:999px;background:#22b07d;color:#ffffff;text-decoration:none;font-weight:600;">GitHub Pages</a>
    <a href="app.py" style="display:inline-block;margin:4px 6px;padding:10px 18px;border-radius:999px;background:#f5a623;color:#ffffff;text-decoration:none;font-weight:600;">Python Script</a>
    <a href="https://github.com/jiaojiao-zhao/Info301-Final-Project" style="display:inline-block;margin:4px 6px;padding:10px 18px;border-radius:999px;background:#333333;color:#ffffff;text-decoration:none;font-weight:600;">Repository</a>
  </p>

  <p>
    <span style="display:inline-block;margin:4px 6px;padding:8px 14px;border-radius:999px;background:#e0f2ff;color:#0b4b8c;font-weight:600;">Python</span>
    <span style="display:inline-block;margin:4px 6px;padding:8px 14px;border-radius:999px;background:#ffeedd;color:#7a3f00;font-weight:600;">HTML</span>
    <span style="display:inline-block;margin:4px 6px;padding:8px 14px;border-radius:999px;background:#f0f0f0;color:#1a1a1a;font-weight:600;">CSS</span>
    <span style="display:inline-block;margin:4px 6px;padding:8px 14px;border-radius:999px;background:#e7f8ff;color:#007293;font-weight:600;">Folium</span>
    <span style="display:inline-block;margin:4px 6px;padding:8px 14px;border-radius:999px;background:#ffe5f0;color:#8b2c6a;font-weight:600;">Pandas</span>
  </p>
</div>

---

## Table of Contents

- [Project Overview](#project-overview)
- [Why It Matters](#why-it-matters)
- [Features](#features)
- [Technical Stack](#technical-stack)
- [Resources](#resources)
- [Deployment](#deployment)
- [SDGs contributed](#sdgs-contributed)
- [Reproducibility](#reproducibility)
- [Ethics & Transparency](#ethics--transparency)

---

## Project Overview

Discover Kunshan through a static, interactive cultural food map that blends geospatial storytelling with field-collected photography. This project highlights local eateries, community narratives, and neighborhood food walks across Kunshan, giving small vendors digital visibility without relying on third-party aggregator platforms.

**Authors:** Weisheng Zhang, Jiaojiao Zhao  
**Instructor:** Luyao Zhang

---

## Why It Matters

Kunshan's local food culture is rich, diverse, and often underrepresented in tourism and urban information systems. This map is designed to:

- amplify authentic neighborhood dining experiences
- preserve culinary memory through narrative location cards
- support independent businesses with shareable digital visibility
- invite visitors and residents to explore food, culture, and place together

---

## Features

- **Interactive location markers** with rich cultural storytelling
- **Bilingual descriptions** that preserve Chinese names and English context
- **Thematic micro food-walk routes** that highlight neighborhood discovery
- **Photo-rich popup cards** built from field-collected imagery
- **Standalone static output** requiring no backend or server
- **Open-source, reproducible workflow** with Python, Folium, and GitHub Pages

---

## Technical Stack

**Languages & Tools**
- Python
- HTML
- CSS
- Folium
- Pandas
- OpenStreetMap / Stadia Maps

**Data & processing**
- Field-collected geolocation and restaurant metadata
- Embedded image assets via Base64 conversion
- Static HTML generation for reliable GitHub Pages deployment

---

## Resources

- **Live Demo:** [front.html](front.html)  
- **GitHub Pages:** [https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html](https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html)  
- **Source Code:** [GitHub repository](https://github.com/jiaojiao-zhao/Info301-Final-Project)  
- **Primary libraries:** [Folium](https://python-visualization.github.io/folium/), [Pandas](https://pandas.pydata.org/)

---

## Deployment

This project is deployed as a static site via GitHub Pages. No server, no database, and no runtime dependencies are required to view the interactive map.

**To deploy your own fork:**
1. Fork the repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root directory
4. Visit `https://<your-username>.github.io/Info301-Final-Project/front.html`

---

## SDGs contributed

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(220px, 1fr)); gap:16px; margin-top:12px;">
  <figure style="margin:0;padding:0;">
    <img src="pictures/SDG4.jpg" alt="SDG 4" style="width:100%;border-radius:14px;box-shadow:0 12px 30px rgba(0,0,0,0.12);" />
    <figcaption style="font-size:0.92rem;margin-top:8px;text-align:center;color:#333;">SDG 4</figcaption>
  </figure>
  <figure style="margin:0;padding:0;">
    <img src="pictures/SDG8.jpg" alt="SDG 8" style="width:100%;border-radius:14px;box-shadow:0 12px 30px rgba(0,0,0,0.12);" />
    <figcaption style="font-size:0.92rem;margin-top:8px;text-align:center;color:#333;">SDG 8</figcaption>
  </figure>
  <figure style="margin:0;padding:0;">
    <img src="pictures/SDG11.jpg" alt="SDG 11" style="width:100%;border-radius:14px;box-shadow:0 12px 30px rgba(0,0,0,0.12);" />
    <figcaption style="font-size:0.92rem;margin-top:8px;text-align:center;color:#333;">SDG 11</figcaption>
  </figure>
  <figure style="margin:0;padding:0;">
    <img src="pictures/SDG17.jpg" alt="SDG 17" style="width:100%;border-radius:14px;box-shadow:0 12px 30px rgba(0,0,0,0.12);" />
    <figcaption style="font-size:0.92rem;margin-top:8px;text-align:center;color:#333;">SDG 17</figcaption>
  </figure>
</div>

---

## Reproducibility

### Dependencies

```bash
python >= 3.9
pip install folium pandas
```

### Repository Structure

```
Info301-Final-Project/
├── pictures/
├── app.py
├── front.html
├── index.html
├── suzhou_cultural_map.html
└── README.md
```

### Local Setup

1. Clone the repository
   ```bash
git clone https://github.com/jiaojiao-zhao/Info301-Final-Project.git
cd Info301-Final-Project
```
2. Install dependencies
   ```bash
pip install folium pandas
```
3. Regenerate the map (optional)
   ```bash
python app.py
```
4. Open `front.html` in a browser

---

## Ethics & Transparency

- Field photographs were collected with permission and respect for local vendors.
- No restaurant listings were purchased or sponsored.
- The map is based on a limited fieldwork sample and reflects the authors' observational viewpoint.
- The project is provided as an open educational resource for non-commercial use.
