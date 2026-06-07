<div align="center" style="padding:0 12px;">
  <h1>🥢 Discover Kunshan · 昆山美食文化互动地图</h1>
  <p style="max-width:760px;margin:0 auto;font-size:1.1rem;color:#444;">Interactive Cultural Food Map · INFO301 Final Project</p>

  <p align="center">
    [![Live Demo](https://img.shields.io/badge/Live%20Demo-Open-blue?style=for-the-badge)](front.html)
    [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-View-green?style=for-the-badge)](https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html)
    [![Python Script](https://img.shields.io/badge/Python%20Script-Open-yellow?style=for-the-badge&logo=python&logoColor=white)](app.py)
    [![Repository](https://img.shields.io/badge/Repository-GitHub-black?style=for-the-badge&logo=github)](https://github.com/jiaojiao-zhao/Info301-Final-Project)
  </p>

  <p align="center">
    ![Python](https://img.shields.io/badge/Python-3.10-blue)
    ![HTML](https://img.shields.io/badge/HTML5-orange)
    ![CSS](https://img.shields.io/badge/CSS3-blue)
    ![Folium](https://img.shields.io/badge/Folium-Map-brightgreen)
    ![Pandas](https://img.shields.io/badge/Pandas-Data-lightgrey)
  </p>
</div>

<div style="display:flex;flex-wrap:wrap;gap:24px;justify-content:center;align-items:flex-start;margin:0 auto 32px;max-width:1000px;">
  <div style="flex:1 1 320px;min-width:280px;max-width:520px;background:#f9fbff;border:1px solid #e5ecf7;border-radius:18px;padding:24px;box-shadow:0 12px 30px rgba(15,23,42,0.06);">
    <h2 style="margin-top:0;font-size:1.5rem;color:#152242;">Table of Contents</h2>
    <ul style="padding-left:20px;line-height:1.8;color:#2f3f5b;font-size:1rem;">
      <li><a href="#project-overview" style="color:#1f74ff;text-decoration:none;font-weight:600;">Project Overview</a></li>
      <li><a href="#why-it-matters" style="color:#1f74ff;text-decoration:none;font-weight:600;">Why It Matters</a></li>
      <li><a href="#features" style="color:#1f74ff;text-decoration:none;font-weight:600;">Features</a></li>
      <li><a href="#technical-stack" style="color:#1f74ff;text-decoration:none;font-weight:600;">Technical Stack</a></li>
      <li><a href="#resources" style="color:#1f74ff;text-decoration:none;font-weight:600;">Resources</a></li>
      <li><a href="#deployment" style="color:#1f74ff;text-decoration:none;font-weight:600;">Deployment</a></li>
      <li><a href="#sdgs-contributed" style="color:#1f74ff;text-decoration:none;font-weight:600;">SDGs contributed</a></li>
      <li><a href="#reproducibility" style="color:#1f74ff;text-decoration:none;font-weight:600;">Reproducibility</a></li>
      <li><a href="#ethics--transparency" style="color:#1f74ff;text-decoration:none;font-weight:600;">Ethics & Transparency</a></li>
    </ul>
    <div style="margin-top:22px;">
      <a id="sdgs-contributed"></a>
      <h3 style="margin-bottom:14px;font-size:1.2rem;color:#152242;">SDGs contributed</h3>
      <div>

| SDG 4 | SDG 8 |
| --- | --- |
| ![SDG4](pictures/SDG4.jpg) <br> SDG 4 | ![SDG8](pictures/SDG8.jpg) <br> SDG 8 |
| ![SDG11](pictures/SDG11.jpg) <br> SDG 11 | ![SDG17](pictures/SDG17.jpg) <br> SDG 17 |

      </div>
    </div>
  </div>

  <div>

[![Discover Kunshan Poster](posters/DiscoverKunshanPoster.png)](posters/DiscoverKunshanPoster.pdf)

Poster preview — [Download full PDF](posters/DiscoverKunshanPoster.pdf)

  </div>
</div>

## Project Overview

Discover Kunshan through a static, interactive cultural food map that blends geospatial storytelling with field-collected photography. This project highlights local eateries, community narratives, and neighborhood food walks across Kunshan, giving small vendors digital visibility without relying on third-party aggregator platforms.

**Authors:** Weisheng Zhang, Jiaojiao Zhao  
**Instructor:** Luyao Zhang

---

## Why It Matters

<div style="display:grid;gap:16px;margin:18px 0 28px;">
  <p style="max-width:860px;color:#3a3f55;line-height:1.9;">
    Kunshan's local food culture is rich, diverse, and often underrepresented in tourism and urban information systems. This map is designed to surface neighborhood stories, strengthen community visibility, and create an inviting cultural entry point for both visitors and locals.
  </p>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:16px;">
    <div style="padding:18px;border-radius:20px;background:#fff8ec;border:1px solid #f6e4c9;box-shadow:0 14px 28px rgba(131,99,40,0.08);">
      <div style="font-size:1.1rem;font-weight:700;color:#d97706;">🍜 Community Culture</div>
      <p style="margin:12px 0 0;color:#4a4a4a;">Amplify authentic neighborhood dining experiences with narrative-rich map points.</p>
    </div>
    <div style="padding:18px;border-radius:20px;background:#e8f7ff;border:1px solid #d2e8f9;box-shadow:0 14px 28px rgba(28,103,177,0.08);">
      <div style="font-size:1.1rem;font-weight:700;color:#0c6cbd;">📍 Inclusive Discovery</div>
      <p style="margin:12px 0 0;color:#4a4a4a;">Support independent eateries and create a culturally grounded walking experience.</p>
    </div>
    <div style="padding:18px;border-radius:20px;background:#e9fdf2;border:1px solid #c8f0dc;box-shadow:0 14px 28px rgba(23,116,82,0.08);">
      <div style="font-size:1.1rem;font-weight:700;color:#0f766e;">🌍 Sustainable Visibility</div>
      <p style="margin:12px 0 0;color:#4a4a4a;">Provide small businesses with digital presence without relying on corporate platforms.</p>
    </div>
    <div style="padding:18px;border-radius:20px;background:#f0f5ff;border:1px solid #d9e4fc;box-shadow:0 14px 28px rgba(61,85,171,0.08);">
      <div style="font-size:1.1rem;font-weight:700;color:#3730a3;">📖 Cultural Storytelling</div>
      <p style="margin:12px 0 0;color:#4a4a4a;">Translate local food memory into accessible spatial narratives for wider audiences.</p>
    </div>
  </div>
</div>

---

## Features

<div style="display:grid;gap:14px;margin:16px 0 28px;">
  <div style="display:flex;flex-wrap:wrap;gap:10px;">
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#fbf1ff;color:#7c3aed;font-weight:700;">Interactive map experience</span>
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#eff6ff;color:#2563eb;font-weight:700;">Bilingual storytelling</span>
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#ecfdf5;color:#15803d;font-weight:700;">Neighborhood food walks</span>
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#ffedd5;color:#c2410c;font-weight:700;">Photo-rich popups</span>
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#f8fafc;color:#0f172a;font-weight:700;">Static HTML deployment</span>
    <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#fff7ed;color:#b45309;font-weight:700;">Open-source workflow</span>
  </div>
  <div style="display:grid;grid-template-columns:1fr;gap:12px;">
    <div style="padding:18px;border-radius:18px;background:#ffffff;border:1px solid #e5e7eb;box-shadow:0 12px 24px rgba(15,23,42,0.06);">
      <div style="font-weight:700;color:#111827;">Interactive location markers</div>
      <p style="margin:10px 0 0;color:#4b5563;">Each pin is a narrative entry point, with popups that surface flavor, history, and local meaning.</p>
    </div>
    <div style="padding:18px;border-radius:18px;background:#ffffff;border:1px solid #e5e7eb;box-shadow:0 12px 24px rgba(15,23,42,0.06);">
      <div style="font-weight:700;color:#111827;">Static site reliability</div>
      <p style="margin:10px 0 0;color:#4b5563;">Built as a stand-alone HTML experience so the map loads instantly without backend dependencies.</p>
    </div>
  </div>
</div>

---

## Technical Stack

<div style="display:flex;flex-wrap:wrap;gap:16px;margin:18px 0 24px;">
  <div style="flex:1 1 240px;min-width:220px;padding:20px;border-radius:20px;background:#f8fafc;border:1px solid #e2e8f0;">
    <div style="font-size:1.1rem;font-weight:700;color:#0f172a;">Core tools</div>
    <div style="margin-top:12px;display:grid;gap:10px;">
      <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#2563eb;color:#fff;font-weight:700;">Python</span>
      <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#f97316;color:#fff;font-weight:700;">HTML</span>
      <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#0ea5e9;color:#fff;font-weight:700;">CSS</span>
      <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#14b8a6;color:#fff;font-weight:700;">Folium</span>
      <span style="display:inline-flex;align-items:center;padding:10px 14px;border-radius:999px;background:#22c55e;color:#fff;font-weight:700;">Pandas</span>
    </div>
  </div>
  <div style="flex:1 1 280px;min-width:240px;padding:20px;border-radius:20px;background:#fff7ed;border:1px solid #fde2c4;">
    <div style="font-size:1.1rem;font-weight:700;color:#92400e;">Data process</div>
    <ul style="margin:14px 0 0;padding-left:20px;color:#475569;line-height:1.8;">
      <li>Field-collected geolocation and metadata</li>
      <li>Base64 image embedding for stable load</li>
      <li>Static HTML generation for GitHub Pages</li>
    </ul>
  </div>
</div>

---

## Resources

<div style="display:grid;gap:16px;margin:18px 0 28px;">
  <p style="color:#334155;line-height:1.8;">Use the quick access buttons below to explore the project, view the deployed map, or inspect the source code and library references.</p>
  <p align="center">
    [![Open Live Demo](https://img.shields.io/badge/Open%20Live%20Demo-blue?style=for-the-badge)](front.html)
    [![View GitHub Pages](https://img.shields.io/badge/View%20GitHub%20Pages-green?style=for-the-badge)](https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html)
    [![Read Source](https://img.shields.io/badge/Read%20Source-black?style=for-the-badge&logo=github)](https://github.com/jiaojiao-zhao/Info301-Final-Project)
    [![Folium Docs](https://img.shields.io/badge/Folium-Docs-blue?style=for-the-badge)](https://python-visualization.github.io/folium/)
    [![Pandas Docs](https://img.shields.io/badge/Pandas-Docs-lightgrey?style=for-the-badge)](https://pandas.pydata.org/)
  </p>
</div>

---

## Deployment

This project is deployed as a static site via GitHub Pages. No server, no database, and no runtime dependencies are required to view the interactive map.

**To deploy your own fork:**
1. Fork the repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root directory
4. Visit `https://<your-username>.github.io/Info301-Final-Project/front.html`

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
├── app.py
├── front.html
├── index.html
├── posters/
│   ├── DiscoverKunshanPoster.pdf
│   └── DiscoverKunshanPoster.png
├── pictures/
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
