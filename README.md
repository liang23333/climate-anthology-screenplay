# Climate Change Anthology Screenplay

> *A collaborative, science-grounded screenwriting project exploring the human reality of a rapidly warming planet through three interconnected lenses: Rising Seas, Wildfires, and Drought.*

---

## 📖 Project Overview

This repository houses the collaborative screenplay for our class anthology feature film. Climate fiction ("Cli-Fi") works best when grounded in rigorous scientific reality and granular human experience. Rather than treating climate change as a distant dystopian backdrop, our anthology treats the biosphere as an active, visceral antagonist and catalyst for human drama.

The anthology is structured into three continuous or intertwined narrative segments:
1. **Segment 1: Rising Seas** – Coastal inundation, saltwater intrusion, and climate migration.
2. **Segment 2: Wildfires** – Wildland-urban interface collapse, extreme vapor pressure deficits, and atmospheric smoke transport.
3. **Segment 3: Drought** – Hydrological failure, depleted aquifers, "Day Zero" municipal stress, and agricultural tipping points.

---

## 🌍 Real-World Environmental Reference: Dhaka Case Study

To give our writing authentic sensory depth, we anchor the environmental texture in verified scientific and atmospheric data. Below is real-time meteorological and air-quality data recorded for **Dhaka, Bangladesh**—one of the world's ground-zero cities for climate displacement:

| Metric | Recorded Value | Screenwriting & Sensory Implications |
| :--- | :--- | :--- |
| **Coordinates** | 23.72° N, 90.41° E | Low-elevation delta basin, Ganges-Brahmaputra confluence. |
| **Ambient Temperature** | **32.0°C (89.7°F)** | Oppressive tropical warmth under dense overcast sky. |
| **Heat Index / Feels Like** | **37.1°C (98.8°F)** | Thermal stress; sweat doesn't evaporate quickly, physical labor becomes dangerous. |
| **Wet Bulb Temperature** | **25.4°C (77.8°F)** | Approaching dangerous human physiological thresholds for outdoor work. |
| **Humidity & Cloud** | **59% Humidity**, **98% Cloud Cover** | Heavy, suffocating canopy of low clouds trapping heat and pollutants. |
| **Atmospheric Pressure** | **1004.0 mb** | Depressed monsoonal trough pressure; unsettled weather. |
| **Precipitation** | **0.29 mm** (Light rain shower) | Sporadic drizzle turning dusty city streets into slick, oily sludge. |
| **Air Quality Index** | **US-EPA: 2 (Moderate)** | Hazy skyline; visible particulate suspension. |
| **Particulate (PM2.5 / PM10)** | **21.0 µg/m³ / 22.7 µg/m³** | Fine combustion particulates irritating respiratory systems. |
| **Ground Ozone ($O_3$)** | **138.0 µg/m³** (Elevated) | Photochemical smog causing throat tightness and eye stinging. |

### The Human Reality Behind the Numbers:
* **The Sinking Coast:** Over two-thirds of Bangladesh lies under 5 meters (15 feet) above sea level. A 50 cm sea-level rise threatens to displace over 18 million people.
* **Urban Influx:** Approximately **2,000 climate migrants enter Dhaka daily**, having lost family farms to coastal embankment breaches, riverbank erosion (river collapse), and saline soil poisoned by storm surges.
* **Urban Heat Trap:** In informal settlements (such as Korail slum), corrugated tin roofing acts as an oven, raising interior temperatures 4–6°C above outdoor ambient levels.

---

## 🗂 Repository Structure

```text
├── README.md                           # Project brief, data reference, and contribution guide
├── research/
│   └── environmental_reference_dhaka.md # Authentic atmospheric, weather & AQI baseline data
├── templates/
│   └── screenplay_template.fountain    # Industry standard Fountain screenwriting template
└── screenplay/
    ├── 00_anthology_bible.md           # Character arcs, tonal guidelines, and overarching motifs
    ├── segment_1_rising_seas.fountain  # Starter screenplay file for Rising Seas
    ├── segment_2_wildfires.fountain    # Starter screenplay file for Wildfires
    └── segment_3_drought.fountain      # Starter screenplay file for Drought
```

---

## ✍️ Writing Format: Fountain

All screenplay files are formatted using [Fountain](https://fountain.io/), an open-source plain-text markup syntax for screenwriters. It is directly editable in GitHub/VS Code and seamlessly imports into:
* **Final Draft**
* **Highland 2**
* **Fade In**
* **Slugline**
* **Scrivener**

### Quick Syntax Guide:
* **Scene Headings:** Start with `INT.` or `EXT.` in UPPERCASE (e.g., `EXT. DHAKA EMBANKMENT - DAY`).
* **Character Names:** Centered/Uppercase above dialogue (e.g., `FATIMA`).
* **Parentheticals:** In parentheses directly below character name `(whispering)`.
* **Transitions:** In uppercase ending with `TO:` (e.g., `CUT TO:` or `SMASH CUT TO:`).
* **Notes/Comments:** Wrap in double brackets `[[Research note: check tidal surge timing]]`.

---

## 🤝 Collaboration Workflow for Classmates

1. **Check the Issues Tab:** Each story segment has a dedicated Issue detailing recent scientific studies, news reports, and specific scene prompts.
2. **Assign a Segment:** Claim a scene or segment by commenting on the corresponding issue.
3. **Branching Strategy:**
   - Create a feature branch: `git checkout -b segment-1-scene-draft`
   - Commit changes with descriptive messages: `git commit -m "Draft opening sequence for coastal displacement"`
4. **Pull Requests (PRs):** Submit a PR to `main` referencing the issue number (e.g., `Closes #1`). Request peer reviews from at least one classmate before merging.
