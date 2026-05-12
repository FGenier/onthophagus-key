# Multilingual interactive key to Henri d’Orbigny’s groups of *Onthophagus* (1913) — Version 1.3

## Overview

This project provides a multilingual interactive identification key to the species groups of *Onthophagus* Latreille, 1802 proposed by Henri d’Orbigny in his 1913 synopsis of the African fauna.

The interface currently supports:

- Français
- English
- Deutsch

The key reproduces, modernizes, and structures d’Orbigny’s original concepts while preserving the historical logic of the original dichotomous system.

This interactive implementation was developed to facilitate access to one of the most historically important classificatory frameworks for Afrotropical *Onthophagus*. More than a century after its publication, d’Orbigny’s species groups remain widely cited in diagnoses and taxonomic revisions dealing with the sub-Saharan fauna.

---

## Contents

### Main files

| File | Description |
|---|---|
| `onthophagus-groupes-1.3.html` | Main interactive interface |
| `cle_onthophagus_data_1.3.json` | Multilingual database containing couplets, groups, notes, and interface strings |
| `orbigny.ico` | Interface icon |
| `README.md` | Project documentation |

---

## Features

- Interactive dichotomous navigation
- Multilingual interface
- Modernized terminology
- Historical diagnoses preserved
- Expandable notes
- Responsive interface
- Local execution without external dependencies
- GitHub Pages compatible

---

## Languages

### Français

Version originale française basée sur les textes historiques de d’Orbigny, avec modernisation limitée de certains éléments typographiques et terminologiques.

### English

Faithful scientific translation intended for international users working on Afrotropical Scarabaeinae.

### Deutsch

Complete German translation of the interface, couplets, notes, and group diagnoses using modern entomological terminology.

---

## Installation

### Local execution using Python

Open a terminal in the project directory and run:

```bash
python -m http.server 8000
```

or:

```bash
py -m http.server 8000
```

Then open:

```text
http://localhost:8000/onthophagus-groupes-1.3.html
```

---

## GitHub Pages deployment

The project can be deployed directly using GitHub Pages.

Recommended repository structure:

```text
/
├── images/
├── onthophagus-groupes-1.3.html
├── cle_onthophagus_data_1.3.json
├── orbigny.ico
└── README.md
```

---

## Citation

If you use this tool in scientific work, please cite:

> Génier, F. 2026. Multilingual interactive key to Henri d’Orbigny’s groups of *Onthophagus* (1913), version 1.3.

DOI information should be added here once the Zenodo release is generated.

---

## Historical background

Henri d’Orbigny’s 1913 synopsis remains one of the few large-scale classificatory syntheses covering a major portion of the Afrotropical *Onthophagus* fauna.

Although many genera and species concepts have changed considerably since 1913, the species groups proposed by d’Orbigny continue to be referenced extensively in taxonomic literature.

This project aims to preserve and modernize access to these historical concepts through an interactive multilingual interface.

---

## Technical notes

The interface uses:

- HTML5
- CSS3
- Vanilla JavaScript
- External JSON data structure

No external libraries or frameworks are required.

---

## Version history

### Version 1.3

- Added complete German interface
- Added German translations of:
  - couplets
  - group diagnoses
  - notes
  - interface strings
- Improved multilingual support
- Updated JSON structure
- Improved interface stability
- Corrected JSON loading issues
- Added language-selection icons

---

## License

This project is distributed for scientific and educational purposes.

Recommended license:

CC BY-NC 4.0

---

## Acknowledgements

This project was inspired by the enduring scientific importance of Henri d’Orbigny’s work on Afrotropical *Onthophagus*.

Development of the interactive system and associated taxonomic resources was supported in part through work associated with the Mantis Database project.
