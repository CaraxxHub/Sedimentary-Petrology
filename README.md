# Mineral Data Sheets for Sandstone Petrography

Interactive, bilingual (EN/DE) reference sheets for optical microscopy identification of minerals in sandstones.

**🔗 Live Site:** `https://[your-username].github.io/mineral-datasheets/`

---

## Overview

This collection provides 13 mineral data sheets designed for undergraduate-level sandstone petrography courses. Each sheet covers:

- **Optical Properties** — PPL and XPL characteristics with diagnostic features
- **Occurrence & Provenance** — Source rocks and tectonic significance  
- **Stability & Diagenesis** — Weathering resistance and burial modifications
- **Recognition** — Comparison tables and best practices for identification

All sheets feature a **bilingual toggle** (English/German) that persists across pages.

---

## Minerals Included

### Framework Grains (QFL)
| Mineral | Key Diagnostic Features |
|---------|------------------------|
| **Quartz** | Low birefringence, no cleavage, undulose extinction types |
| **K-Feldspar** | Tartan twinning (microcline), Carlsbad twins, cloudy alteration |
| **Plagioclase** | Polysynthetic "zebra stripe" twinning, albite to anorthite series |

### Phyllosilicates
| Mineral | Key Diagnostic Features |
|---------|------------------------|
| **Biotite** | Brown color, strong pleochroism, "birds-eye" extinction |
| **Muscovite** | Colorless, bright 2nd-3rd order XPL colors |
| **Chlorite** | Green PPL, anomalous "Berlin blue" XPL |

### ZTR Suite (Ultra-Stable Heavy Minerals)
| Mineral | Key Diagnostic Features |
|---------|------------------------|
| **Zircon** | Very high relief, euhedral prismatic, U-Pb geochronology |
| **Tourmaline** | Rounded triangular section, no cleavage, strong pleochroism |
| **Rutile** | Extreme relief, deep red-brown, geniculate twins |

### Other Accessory Minerals
| Mineral | Key Diagnostic Features |
|---------|------------------------|
| **Apatite** | Hexagonal habit, very low birefringence, fission-track dating |
| **Epidote** | "Pistachio green" color, high relief, strong pleochroism |

### Ferromagnesian Chain Silicates
| Mineral | Key Diagnostic Features |
|---------|------------------------|
| **Pyroxene (Augite)** | ~90° cleavage angle, 8-sided basal section |
| **Amphibole (Hornblende)** | 56°/124° cleavage angle, diamond-shaped section |

---

## Deployment to GitHub Pages

### Option 1: Direct Upload
1. Create a new GitHub repository (e.g., `mineral-datasheets`)
2. Upload all `.html` files to the repository root
3. Go to **Settings → Pages**
4. Set Source to **Deploy from a branch** → `main` → `/ (root)`
5. Save and wait ~1 minute for deployment

### Option 2: Git Command Line
```bash
git init
git add .
git commit -m "Initial commit: Mineral data sheets"
git branch -M main
git remote add origin https://github.com/[your-username]/mineral-datasheets.git
git push -u origin main
```
Then enable GitHub Pages in repository settings.

---

## Local Development

Simply open `index.html` in any modern browser. No build tools or server required — all files are static HTML with embedded CSS/JavaScript.

---

## File Structure

```
mineral-datasheets/
├── index.html                 # Landing page with mineral cards
├── quartz-datasheet.html
├── kfeldspar-datasheet.html
├── plagioclase-datasheet.html
├── biotite-datasheet.html
├── muscovite-datasheet.html
├── chlorite-datasheet.html
├── zircon-datasheet.html
├── tourmaline-datasheet.html
├── rutile-datasheet.html
├── apatite-datasheet.html
├── epidote-datasheet.html
├── pyroxene-datasheet.html
├── amphibole-datasheet.html
└── README.md
```

---

## Adding Photomicrographs

Each datasheet includes placeholder boxes with AAPG Atlas references. To add your own images:

1. Replace the `<div class="image-placeholder">...</div>` blocks with:
```html
<img src="images/quartz-ppl.jpg" alt="Quartz in PPL" style="width: 100%; border-radius: 8px;">
```

2. Create an `images/` folder and add your photomicrographs

---

## Key References

- Caracciolo, L. (2020). Sediment generation and sediment routing systems from a quantitative provenance analysis perspective. *Earth-Science Reviews*, 209, 103226.
- Garzanti, E. (2016). From static to dynamic provenance analysis. *Sedimentary Geology*, 336, 3–13.
- von Eynatten, H., & Dunkl, I. (2012). Assessing the sediment factory: The role of single grain analysis. *Earth-Science Reviews*, 115, 97–120.
- Goldich, S.S. (1938). A study in rock-weathering. *Journal of Geology*, 46, 17–58.

---

## License

These materials are provided for educational use at GeoZentrum Nordbayern, FAU Erlangen-Nürnberg.

---

## Contact

**GeoZentrum Nordbayern**  
Friedrich-Alexander-Universität Erlangen-Nürnberg  
Sandstone Petrography Course
