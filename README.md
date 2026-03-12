# 🥢 Discover Kunshan · 昆山美食文化互动地图
### Interactive Cultural Food Map · INFO301 Final Project

**Authors:** Weisheng Zhang, Jiaojiao Zhao

**Instructor** Luyao Zhang

**Live Demo:** https://jiaojiao-zhao.github.io/Info301-Final-Project/front.html

---

## 📌 Purpose

### Community Problem
Kunshan's vibrant street-level food culture is largely invisible in mainstream tourism and urban data platforms. Small independent eateries, often run by local families for decades, lack digital visibility and risk being overlooked as the city modernizes. There is no accessible, culturally rich resource that tells the *stories* behind these places.

### Who This Serves
- **Residents and visitors** seeking authentic local dining experiences
- **Small business owners** whose eateries gain visibility through the map
- **Researchers and educators** studying food culture, urban identity, and digital humanities
- **Community organizations** interested in neighborhood-level cultural documentation

### UN Sustainable Development Goal Contributions

| SDG | Contribution |
|-----|--------------|
| **SDG 4 – Quality Education** | Cultural learning through food stories and spatial narratives |
| **SDG 8 – Decent Work & Economic Growth** | Digital visibility for small independent eateries |
| **SDG 11 – Sustainable Cities & Communities** | Community-rooted, accessible urban storytelling |
| **SDG 17 – Partnerships for the Goals** | Open-source documentation and collaborative fieldwork |

---

## 🤖 AI Components

### Tools & Models Used
- **Claude (Anthropic)** — Used for iterative feedback on narrative framing, popup card copy editing, and accessibility language review
- **ChatGPT (OpenAI)** — Assisted with initial Python scaffolding for the Folium map construction pipeline

### Techniques
- **Prompt-guided copywriting:** AI tools were used to refine the cultural description text in popup story cards, ensuring consistent tone and appropriate cultural sensitivity
- **Code generation assistance:** Boilerplate Folium HTML/CSS popup templates were drafted with AI assistance, then manually reviewed and customized
- **Content review:** AI was used to flag potentially reductive or stereotyping language in neighborhood descriptions before publication

### Human Oversight
All AI-generated or AI-assisted content was reviewed, edited, and approved by the authors before inclusion. AI tools were not used for data collection, geospatial analysis, or photography.

---

## 🤝 Stakeholder Integration

### Museum & Cultural Institution Influence
During the design process, we consulted framing principles from **museum studies and exhibition design** — specifically how physical food museums and cultural heritage exhibits contextualize everyday objects as artifacts of identity.

### Design Changes Resulting from Stakeholder Input
- **Shifted from "restaurant directory" to "story node" framing:** Early prototypes listed restaurants with ratings. After reviewing museum exhibit design principles and gathering informal feedback from local community members, we reframed each location as a *cultural story node* with a narrative card rather than a transactional listing.
- **Removed price rankings:** Initial designs included star-based affordability tiers, which stakeholder review identified as potentially stigmatizing for lower-income neighborhoods. These were replaced with descriptive affordability language (e.g., "neighborhood staple, ~¥15/meal").
- **Added micro food-walk routes:** Suggested by community members who noted that locals experience food culture as a neighborhood walk, not a point-by-point search — leading to the thematic routing feature.
- **Bilingual labels:** Community feedback emphasized the importance of including Chinese characters alongside English translations to avoid erasing the linguistic identity of the locations.

---

## 🔍 Transparency

### Data Sources
- **Primary:** Field-collected data (in-person visits, interviews with restaurant staff, field photography) conducted by the authors in Kunshan, China
- **Geospatial base:** OpenStreetMap (OSM) via Folium/Stadia Maps tiles
- **No third-party restaurant databases were used** (e.g., Dianping, Google Maps)

### Limitations
- Coverage is limited to locations visited by the two authors during a defined fieldwork period — this is not a comprehensive directory
- The map reflects a snapshot in time; restaurants may have closed, moved, or changed since data collection
- English-language narrative cards are translations/adaptations and may not fully capture nuances of the original Chinese cultural context

### Known Biases
- **Geographic sampling bias:** Fieldwork was concentrated in neighborhoods accessible to the authors; some districts are underrepresented
- **Selection bias:** Locations were selected partly based on author interest and accessibility, which may skew toward certain cuisine types or price ranges
- **Perspective bias:** Narrative descriptions are written from an outside-looking-in perspective for some locations, despite efforts at community-centered framing

### Ethics Statement
- All photographs were taken in public spaces or with explicit permission from establishment owners
- No personally identifiable information about restaurant staff or customers was collected or published
- The project does not accept advertising and no eateries paid for inclusion or favorable representation
- Data is made available open-source for non-commercial educational use

---

## 🔁 Reproducibility

### Dependencies

**Python (data processing & map generation)**
```
python >= 3.9
folium
pandas
base64
```

Install via pip:
```bash
pip install folium pandas
```

**No Node.js or backend server required.** The final output is a fully static HTML file.

### Repository Structure

```
Info301-Final-Project/
│
├── pictures/                   # Source field photographs (used for Base64 embedding)
├── app.py                      # Main script: processes data and generates the Folium map
├── front.html                  # Landing page / main entry point for the interactive map
├── index.html                  # GitHub Pages showcase format
├── suzhou_cultural_map.html    # Map output generated by app.py (linked from front.html)
└── README.md                   # This file
```

### Setup & Running Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/jiaojiao-zhao/Info301-Final-Project.git
   cd Info301-Final-Project
   ```

2. **Install dependencies**
   ```bash
   pip install folium pandas
   ```

3. **Regenerate the map** (optional — pre-built HTML is included)
   ```bash
   python app.py
   ```
   This will overwrite `suzhou_cultural_map.html` with a fresh build.

4. **View locally**
   Open `front.html` in any modern browser. No server needed — all assets are embedded.

### Deployment (GitHub Pages)

The project is deployed as a static site via GitHub Pages:
- Push changes to the `main` branch
- GitHub Pages serves `front.html` as the entry point
- No build step, CI/CD pipeline, or backend configuration required

To deploy your own fork:
1. Fork the repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root directory
4. Your map will be live at `https://<your-username>.github.io/Info301-Final-Project/front.html`

---

## ✨ Key Features

- 📍 **Interactive food map** with zoom, hover preview, and full cultural story cards
- 🍜 **Cuisine category filters** and descriptive affordability indicators
- 🖼️ **Base64-embedded photos** for stable cross-browser loading without a CDN
- 🗺️ **Narrative geospatial design** — each location is a "story node," not just a pin
- 🚶 **Micro food-walk routes** showing thematic sequences across neighborhoods
- 🌐 **Fully static deployment** — no backend, no database, no authentication required

---

## 🛠️ Technical Workflow

1. **Data Processing (Python):** Clean and validate field-collected geospatial data; standardize cuisine types, price descriptions, and metadata; convert photos to Base64 for embedding
2. **Prototyping (Plotly):** Visual layout exploration, color encoding experiments, narrative density evaluation
3. **Map Construction (Folium):** Basemap rendering via Stadia Maps + OSM; marker placement; custom HTML/CSS popup card generation; filter-based interaction
4. **Deployment:** Export standalone HTML; deploy via GitHub Pages

---

## 📚 Interdisciplinary Foundations

This project draws from Information Visualization (narrative design patterns, annotations, audience framing), Digital Humanities (interpreting everyday food culture through spatial stories), Anthropology and Museum Studies (restaurants as cultural artifacts), and Data Ethics (transparency, inclusivity, careful contextual representation).