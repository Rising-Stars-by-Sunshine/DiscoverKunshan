# 🥢 Discover Kunshan · 昆山美食文化互动地图 

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20577097-1abc9c)](https://doi.org/10.5281/zenodo.20577097)

Interactive Cultural Food Map · INFO301 Final Project

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open-blue?style=for-the-badge)](front.html) [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-View-green?style=for-the-badge)](https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html) [![Python Script](https://img.shields.io/badge/Python%20Script-Open-yellow?style=for-the-badge&logo=python&logoColor=white)](app.py) [![Repository](https://img.shields.io/badge/Repository-GitHub-black?style=for-the-badge&logo=github)](https://github.com/jiaojiao-zhao/Info301-Final-Project)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![HTML](https://img.shields.io/badge/HTML5-orange) ![CSS](https://img.shields.io/badge/CSS3-blue) ![Folium](https://img.shields.io/badge/Folium-Map-brightgreen) ![Pandas](https://img.shields.io/badge/Pandas-Data-lightgrey)


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



## Project Overview

Discover Kunshan through a static, interactive cultural food map that blends geospatial storytelling with field-collected photography. This project highlights local eateries, community narratives, and neighborhood food walks across Kunshan, giving small vendors digital visibility without relying on third-party aggregator platforms.

**Authors:** Weisheng Zhang, Jiaojiao Zhao  
**Instructor:** Luyao Zhang
 
<!-- SDG and poster table inserted below -->

| SDGs contributed | Poster |
| --- | --- |
| <table><tr><td align="center"><img src="pictures/SDG4.jpg" width="64" alt="SDG4" /><br>**🎓 SDG 4**<br>Quality Education</td><td align="center"><img src="pictures/SDG8.jpg" width="64" alt="SDG8" /><br>**💼 SDG 8**<br>Decent Work</td></tr><tr><td align="center"><img src="pictures/SDG11.jpg" width="64" alt="SDG11" /><br>**🏙️ SDG 11**<br>Sustainable Cities</td><td align="center"><img src="pictures/SDG17.jpg" width="64" alt="SDG17" /><br>**🤝 SDG 17**<br>Partnerships</td></tr></table> | <a href="posters/DiscoverKunshanPoster.pdf"><img src="posters/DiscoverKunshanPoster.png" width="220" alt="Discover Kunshan Poster" /></a><br>[Download full PDF](posters/DiscoverKunshanPoster.pdf) |

---

## Why It Matters

Kunshan's local food culture is rich, diverse, and often underrepresented in tourism and urban information systems. This map is designed to surface neighborhood stories, strengthen community visibility, and create an inviting cultural entry point for both visitors and locals.

Key points:

- **🍜 Community Culture:** Amplify authentic neighborhood dining experiences with narrative-rich map points.
- **📍 Inclusive Discovery:** Support independent eateries and create a culturally grounded walking experience.
- **🌍 Sustainable Visibility:** Provide small businesses with digital presence without relying on corporate platforms.
- **📖 Cultural Storytelling:** Translate local food memory into accessible spatial narratives for wider audiences.

---

## Features

- Interactive map experience
- Bilingual storytelling
- Neighborhood food walks
- Photo-rich popups
- Static HTML deployment
- Open-source workflow

Highlights:

- **Interactive location markers:** Each pin is a narrative entry point, with popups that surface flavor, history, and local meaning.
- **Static site reliability:** Built as a stand-alone HTML experience so the map loads instantly without backend dependencies.

---

## Technical Stack

Core tools:

- Python
- HTML
- CSS
- Folium
- Pandas

Data process:

- Field-collected geolocation and metadata
- Base64 image embedding for stable load
- Static HTML generation for GitHub Pages

---

## Resources

Use the quick access links below to explore the project, view the deployed map, or inspect the source code and library references.

[![Open Live Demo](https://img.shields.io/badge/Open%20Live%20Demo-blue?style=for-the-badge)](front.html) [![View GitHub Pages](https://img.shields.io/badge/View%20GitHub%20Pages-green?style=for-the-badge)](https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html) [![Read Source](https://img.shields.io/badge/Read%20Source-black?style=for-the-badge&logo=github)](https://github.com/jiaojiao-zhao/Info301-Final-Project) [![Folium Docs](https://img.shields.io/badge/Folium-Docs-blue?style=for-the-badge)](https://python-visualization.github.io/folium/) [![Pandas Docs](https://img.shields.io/badge/Pandas-Docs-lightgrey?style=for-the-badge)](https://pandas.pydata.org/)

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

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file in the repository root for details.

