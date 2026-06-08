# autoMIC – Automated MIC Calculation from 96‑Well Plate Data

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20590057.svg)](https://doi.org/10.5281/zenodo.20590057)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ayw_8t-7G2TMLcJbUW457Sx2bHVFVraZ?usp=sharing)

<p align="center">
  <img src="https://raw.githubusercontent.com/Vidhusv/autoMIC/main/logo.png" alt="autoMIC mascot" width="250"/>
</p>

A **free, no‑install, browser‑based tool** for microbiology labs.  
Upload a 96‑well plate reader file and instantly obtain the **MIC value**, a **publication‑ready dose‑response curve**, a **growth heatmap**, and a **CLSI/EUCAST clinical interpretation** – all without leaving your browser.

---

## Quick Start

1. Click the **“Open in Colab”** badge above (or use [this link](https://colab.research.google.com/drive/1Ayw_8t-7G2TMLcJbUW457Sx2bHVFVraZ?usp=sharing)).
2. Run all cells (**Runtime → Run all**).
3. Upload your plate reader file (CSV or Excel).
4. Set your concentration range and threshold.
5. The MIC, dose‑response curve, heatmap, and interpretation appear instantly.

**No programming required.** All processing happens locally – your data never leaves your computer.

---

## Features

- **Instant MIC calculation** – from any 96‑well plate format.
- **Live dose‑response curve** – updates automatically when you change settings.
- **Growth heatmap** – colour‑coded view of the entire plate.
- **CLSI/EUCAST interpretation** – pre‑loaded with 4 organism groups and 40+ antibiotics.
- **Downloadable graphics** – save the dose‑response curve as a PNG for reports.
- **Customisable** – easily add your own breakpoints or modify thresholds.
- **Fully private** – no uploads to external servers; everything runs inside Colab.

---

## The Mascot

autoMIC’s mascot is **Limu**, an anime‑style horseshoe crab.  
Its blue blood is used in the most sensitive bacterial endotoxin tests – just as autoMIC sensitively detects growth inhibition. Limu carries a glowing 96‑well plate on its shell, symbolising precision and reliability.

---

## How to Cite

If you use autoMIC in your research, please cite:

> **Vidhu Smitha Vijay, Oudlin Mary Lenin.**  
> *autoMIC: a free, web‑based tool for automated MIC analysis.*  
> Zenodo, 2025. DOI: [10.5281/zenodo.20590057](https://doi.org/10.5281/zenodo.20590057)

A BibTeX entry is available on the Zenodo record.

---

## Repository Contents

| File | Description |
|------|-------------|
| `autoMIC.ipynb` | The complete Colab notebook. |
| `test_plate.csv` | Example plate reader output for testing. |
| `README.md` | This file. |
| `LICENSE` | MIT License. |
| `CITATION.cff` | Citation metadata (for GitHub/Zenodo). |
| `.zenodo.json` | Metadata for Zenodo auto‑filling. |
| `logo.png` | autoMIC mascot. |

---

## Customisation

You can tailor autoMIC to your lab’s needs without editing any core code:

- **Add new antibiotics/organisms** – edit the `breakpoints` dictionary in the notebook.
- **Change the threshold** – use absolute OD or percentage of the positive control.
- **Adjust triplicate columns** – tell the tool which wells contain your replicates.
- **Use different plate layouts** – map any concentration series to rows A–H.

Full instructions are included inside the notebook.

---

## Troubleshooting & Support

A detailed user guide is built into the notebook (see the **“ autoMIC User Guide”** section at the end).  
Common issues and solutions are covered there.

If you encounter a problem that isn’t listed:

- **Open an issue** on GitHub: [https://github.com/Vidhusv/autoMIC/issues](https://github.com/Vidhusv/autoMIC/issues)
- Include the **error message**, a **screenshot** of your configuration panel, and (if possible) the first rows of your data file (anonymised).

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
You are free to use, modify, and distribute this tool for any purpose, including commercial applications.

---

## Authors

**Vidhu Smitha Vijay**  
**Oudlin Mary Lenin**  

*For enquiries, please open a GitHub issue or contact us via the repository.*