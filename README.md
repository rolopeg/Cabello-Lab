# Cabello-Lab
## Supplementary Material for: "The C. elegans Integrator interactome reveals its architecture and novel roles in mitochondrial homeostasis"

This repository contains the supplementary data, interactive network models, and visualizations associated with part our study on the *Caenorhabditis elegans* Integrator complex.

> **[Cabello, J., et al. (2026). "The C. elegans Integrator interactome reveals its architecture and novel roles in mitochondrial homeostasis". Journal Name. Status: In review.]**

---

## 👥 Authors

Ángela Metola*(1), Eva Gómez-Orte*(1), Rosario López(2), Begoña Ezcurra(1), Michal Razew(3),
Angelina Zheleva(1), Gonzalo Jiménez-Osés(4), María de Toro(1), Wojciech P. Galej(3), Peter
Askjaer(5), Marta Artal-Sanz(5), Ricardo García-Muñoz(1), Antonio Miranda-Vizuete(6), Juan
Cabello(1)#.

1 Center for Biomedical Research of La Rioja (CIBIR), Logroño, Spain.

2 Scientific Computation Research Institute (SCRIUR). University of La Rioja, Spain.

3 European Molecular Biology Laboratory, EMBL Grenoble, France.

4 Center for Cooperative Research in Biosciences (CIC bioGUNE), Basque Research and
Technology Alliance (BRTA), Derio, Spain.

5 Andalusian Centre for Developmental Biology, Consejo Superior de Investigaciones
Científicas (CSIC), Universidad Pablo de Olavide, Sevilla, Spain.

6 Redox Homeostasis Group, Instituto de Biomedicina de Sevilla, Hospital Universitario
Virgen del Rocío/CSIC/Universidad de Sevilla, Seville, Spain.

* Both authors contributed equally.
\# Corresponding author.

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
* Explore the C. elegans Integrator Complex Interactome: https://rolopeg.github.io/Cabello-Lab/Integrator%20complex%20interactome%20website/C_elegans_IC_interactome.html
* Explore the C. elegans Integrator Subunit Interaction Map: https://rolopeg.github.io/Cabello-Lab/Integrator%20complex%20structure%20website/C_elegans_IC_subunit_interaction_map.html

### UpSet Intersection Plot
To explore the intersecting sets of interacting proteins (IP-MS data):
* Visit the UpSet Web Application: : <a href="https://vcg.github.io/upset/" target="_blank" rel="noopener noreferrer">https://vcg.github.io/upset/</a>
* Click "Load Data".
* Paste this URL into the JSON field and click "Submit": https://raw.githubusercontent.com/rolopeg/Cabello-Lab/refs/heads/main/UpSet/interactome.json

(See the UpSet/README.md file for more detailed instructions).


