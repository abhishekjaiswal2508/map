# Indian Art Atlas · An Interactive Journey

An offline-first, interactive digital atlas exploring key locations, eras, artists, and traditions across Indian art history.

🌐 **Live Demo:** [https://abhishekjaiswal2508.github.io/map/](https://abhishekjaiswal2508.github.io/map/)

---

## 🗺️ Overview

The **Indian Art Atlas** connects significant centers of Indian artistic heritage into a single, interactive learning journey. Users can explore prehistoric rock shelters, classical rock-cut sanctuaries, medieval temple complexes, courtly miniature workshops, living folk art communities, and modern art institutions.

### ✨ Highlights

- **Interactive Vector Map of India:** Fully responsive SVG map with interactive coordinate pins, pan/zoom controls, and regional focus.
- **12 Curated Locations across 6 Regions:**
  1. *Bhimbetka* — Prehistoric Rock Art (Palaeolithic & Mesolithic)
  2. *Ajanta Caves* — Classical Buddhist Murals & Rock-cut Architecture (Gupta / Vakataka)
  3. *Ellora Caves* — Rock-cut Monolithic Temples (Rashtrakuta & Yadava)
  4. *Khajuraho* — Nagara Temple Sculpture & Architecture (Chandela)
  5. *Hampi (Vijayanagara)* — Dravidian Imperial Architecture & Sculpture
  6. *Konark Sun Temple* — Kalinga Architecture (Eastern Ganga)
  7. *Tanjore (Thanjavur)* — Chola Bronzes & Thanjavur Painting
  8. *Kangra & Pahari Centres* — Pahari Miniature Painting
  9. *Mughal Court Workshops (Delhi / Agra / Lahore)* — Imperial Miniature Painting
  10. *Madhubani (Mithila)* — Living Folk & Ritual Painting
  11. *Warli (Northern Maharashtra)* — Tribal Wall & Ritual Painting
  12. *Santiniketan (Kala Bhavana)* — Modern Indian Art & Institutional Renaissance
- **Filter & Search:** Filter by historic era (Ancient, Medieval, Courtly, Living, Modern) or search by keyword, artist, technique, or region.
- **Art Notes & Visuals:** Rich descriptions detailing medium, technique, historical context, and primary source links.
- **Offline Capable:** Single-page bundle with zero external runtime dependencies.
- **Academic Submission Mode:** Includes a modal to embed student credentials directly for educational submissions.

---

## 🚀 GitHub Pages Deployment

This repository is configured to deploy automatically via **GitHub Actions** (`.github/workflows/deploy.yml`) as well as direct branch hosting.

### Enabling GitHub Pages on this Repository

1. Navigate to the repository settings on GitHub:
   `https://github.com/abhishekjaiswal2508/map/settings/pages`
2. Under **Build and deployment**:
   - **Option A (GitHub Actions):** In the **Source** dropdown, select **GitHub Actions**. The workflow will automatically publish upon every push to `main`.
   - **Option B (Deploy from branch):** In the **Source** dropdown, select **Deploy from a branch**, choose `main` branch and `/ (root)` folder, then click **Save**.
3. Your live application will be available at:
   **[https://abhishekjaiswal2508.github.io/map/](https://abhishekjaiswal2508.github.io/map/)**

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── deploy.yml          # Automated GitHub Pages CI/CD workflow
├── .nojekyll                   # Disables Jekyll processing on GitHub Pages
├── index.html                  # Main application entrypoint (served by Pages)
├── Indian_Art_Map.html         # Project file copy for reference
└── README.md                   # Documentation and deployment guide
```

---

## 📜 Credits & Attributions

- **Geographic Data:** India geographic boundaries adapted from [DataMeet India community](https://github.com/datameet/maps), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Sources & Art References:** Individual art historical notes cite academic references, institutional archives, and museums as documented inside each atlas record.
