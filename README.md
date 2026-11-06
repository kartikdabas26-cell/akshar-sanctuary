# अक्षर (Akshar) — 3D Indic Literary Sanctuary & Hero Experience

> **"क्षरः सर्वाणि भूतानि कूटस्थोऽक्षर उच्यते"**  
> *That which transforms is mortal; the imperishable (Akshar) remains eternal.*

**Akshar** is a single-screen, immersive 3D hero showcase celebrating classical Indic literature, philosophy, and aesthetic heritage to the modern world. It is built as a self-contained web experience featuring 32 physical 3D hardcover volumes set upon an ancient crinkled and weathered manuscript parchment background.

---

## 🌟 Key Features

### 1. Ancient Crinkled & Weathered Manuscript Background (Bhojpatra Folio)
- **Multi-layered Paper Physics:** Hand-crafted procedural generation of aged birch bark (*Bhojpatra*), complete with organic tea/walnut washes, tannin water spill rings, high-frequency cellulose fiber grain, and charred burnt edges.
- **3D Crumbled Paper Creases:** Realistic polygonal fold ridges, fracture lines, and dual-tone highlight/shadow embossings simulating a parchment that has been folded, carried in a scholar's satchel, and smoothed across centuries.
- **Palimpsest Calligraphy Watermark:** Faded ancient Sanskrit verses from the *Nasadiya Sukta*, *Rigveda*, *Bhagavad Gita*, and *Upanishads* etched into the parchment grain.
- **Monumental Devanagari Wordmark:** Colossal background ligature **"अक्षर"** in royal gold lacquer, dynamically shifting as books are inspected.

### 2. 32-Volume Curated Indic Literary Canon (Sanskrit & Hindi)
- Spanning classical Sanskrit Kavya (*Meghadūtam*, *Kumarasambhava*, *Ritusamhara*), foundational Darshana (*Mandukya Karika*, *Yoga Vasistha*, *Ashtavakra Gita*, *Katha Upanishad*), classical Nataka (*Abhijnanashakuntalam*, *Mudrarakshasa*), Bhakti & Tantra (*Gita Govinda*, *Saundarya Lahari*, *Spanda Karika*), Ayurveda (*Charaka Samhita*), and modern Hindi classics (*Raag Darbari*, *Kamayani*, *Rashmirathi*, *Madhushala*, *Godaan*, *Gunahon Ka Devta*, *Tamas*, *Yama*, *Nirmala*, *Andha Yug*, *Shekhar: Ek Jivani*, *Maila Anchal*, *Urvashi*, *Kitne Pakistan*, *Sara Akash*, *Anandamath*).
- Each book features its authentic opening Shloka/verse in Devanagari, Roman IAST transliteration, poetic English translation, and critical historical commentary.

### 3. Procedural 3D Hardcover Book Generation
- **Zero External Image Dependencies:** All 32 book covers, spine ribs, and gilded page edges are programmatically synthesized via 2D Canvas to 3D `MeshStandardMaterial` textures.
- **Indic Textile & Gold Foil:** Raw Khadi cotton weaves, raised embossed spine ribs, intricate temple arch/mandala medallions, and specular gold foil reflections.
- **Font Re-Baking:** Dynamic listener that re-bakes textures once Google Fonts (`Rozha One`, `Noto Serif Devanagari`, `Cinzel`) finish downloading.

### 4. 4× Sub-Stepped Wave Spring Physics
- Mathematical Gaussian wave spring engine running at **4 sub-steps per frame** for zero-jitter, frame-rate independent fluid motion across 60Hz, 120Hz, and 144Hz displays.
- Hovered books elevate toward the reader, step forward into the light, and turn their gilded faces toward the camera in a harmonic wave.

### 5. Procedural Indic Web Audio Engine
- **Synthesized Tanpura Drone:** Meditative Pancham-Sa drone (138.59 Hz root + 207.65 Hz fifth) synthesized in real-time with microtonal detuning and warm low-pass filtering.
- **Sitar Harp Pluck:** Cursor motion across the 32 books triggers plucked resonant notes tuned to classical Raag Yaman/Bhairav scales, transforming the shelf into an interactive musical harp.
- **Temple Bell / Singing Bowl Chime:** Deep harmonic bronze bell chime when inspecting scriptures.

### 6. Editorial Glassmorphism Drawer & Manuscript Folio
- Smooth cinematic camera zoom that elevates the selected book center-screen in a gentle levitating rotation.
- Slide-out editorial drawer with Bhojpatra card, Devanagari calligraphy, transliteration, and commentary.
- Full-screen Manuscript Folio reader for in-depth contemplation.

---

## 🚀 How to Run

Because `index.html` is completely self-contained with CDN libraries (Three.js r160, Google Fonts), you can launch it in multiple ways:

### Option 1: Direct Double-Click
Simply double-click `index.html` to open it in Google Chrome, Microsoft Edge, Brave, or Firefox.

### Option 2: Local HTTP Server (Recommended)
Using Python or Node:

```bash
# Using Python 3
python -m http.server 8080

# Using Node.js (npx)
npx serve .
```
Then navigate to `http://localhost:8080` in your browser.

---

## ⌨️ Controls & Shortcuts

| Action | Control |
|---|---|
| **Awaken Wave** | Glide cursor across the row of 32 books |
| **Inspect Scripture** | Click any volume |
| **Close Drawer / Return** | Press `Escape` or click `✕` / backdrop |
| **Keyboard Step** | `ArrowLeft` / `ArrowRight` |
| **Open Active Volume** | `Enter` or `Space` |
| **Toggle Ambient Drone** | Click "Sound On / Muted" button in top bar |
| **Random Scripture** | Click "Random Shloka" button in top bar |
| **Parallax Panning** | Move mouse across the sanctuary |

---

*Designed with veneration for Indic literary aesthetics, Vedic philosophy, and modern creative technology.*
