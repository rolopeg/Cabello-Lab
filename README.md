# Cabello-Lab
## Supplementary Material for: "The C. elegans Integrator interactome reveals its architecture and novel roles in homeostasis."

This repository contains the supplementary data, interactive network models, and visualizations associated with our study on the *Caenorhabditis elegans* Integrator complex.

> **[Cabello, J., et al. (2026). "The C. elegans Integrator interactome reveals its architecture and novel roles in homeostasis". Journal Name. Status: In review.]**

---

## 👥 Authors

* **Cabello, J.** - *Centro de Investigación Biomédica de La Rioja, CIBIR.*
* **Metola, A.** - *Centro de Investigación Biomédica de La Rioja, CIBIR.*
* **[Author Name 3]** - *[Author 3 Affiliation]*

*(Corresponding author: [your_email@institution.edu])*

---

## 📂 Repository Structure

The repository is organized into three main directories, each containing specific supplementary files and interactive visualizations:

```text
Cabello-Lab/
├── Integrator complex interactome website/      # Interactive interactome models
│   ├── C_elegans_IC_interactome.html            # Interactive web visualization (Whole Interactome)
│   ├── C_elegans_IC_interactome.png             # Static image of the interactome
│   ├── C_elegans_IC_subunit_interaction_map.html# Interactive web visualization (Subunit Map)
│   └── README.md                                # Specific details for this section
│
├── Integrator complex structure website/        # Structural data and mapping
│   ├── C_elegans_IC_structure.png               # AlphaFold predicted structure image
│   ├── C_elegans_IC_subunit_interaction_map.html# Interactive web visualization (Structural mapping)
│   └── README.md                                # Specific details for this section
│
├── UpSet/                                       # Intersection analysis data
│   ├── interactome.csv                          # Dataset for UpSet web application
│   ├── interactome.json                         # Alternative dataset format
│   ├── example_upset.png                        # Expected visualization output
│   └── README.md                                # Step-by-step instructions to load data
│
└── README.md                                    # This main file
```
---

## 🌐 Quick Links to Interactive Visualizations

For a better reviewing experience, we have hosted the interactive network models using GitHub Pages. You can explore them directly in your web browser without downloading any files:
* Explore the C. elegans Integrator Complex Interactome
* Explore the C. elegans Integrator Subunit Interaction Map

### UpSet Intersection Plot
To explore the intersecting sets of interacting proteins (IP-MS data):
* Visit the UpSet Web Application
* Click "Load Data".
* Paste this URL into the JSON/CSV field and click "Submit": https://raw.githubusercontent.com/rolopeg/Cabello-Lab/refs/heads/main/UpSet/interactome.csv

(See the UpSet/README.md file for more detailed instructions).


