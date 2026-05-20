<div align="center">
  <img src="https://github.com/user-attachments/assets/91dfa918-43d9-403f-b4ee-f5ef59518d3f" width="75%" alt="Lexicon Banner">

  <h1>Lexicon Architecture: Technical Taxonomy & Governance</h1>

  <p><i>"Standardizing architectural communication through bilingual technical governance"</i></p>
  
  <br>

  [![Data Governance](https://img.shields.io/badge/Data%20Governance-Standardized-28a745?style=flat&logo=readthedocs&logoColor=white)](https://en.wikipedia.org/wiki/Data_governance)
  [![Bilingual Lexicon](https://img.shields.io/badge/Bilingual-ENG%2FESP-0056b3?style=flat&logo=google-translate&logoColor=white)](https://github.com/jc-datarchitect/lexicon_arch)
  [![Onboarding Ready](https://img.shields.io/badge/Onboarding-Tool-FF9800?style=flat&logo=gitbook&logoColor=white)](https://github.com/jc-datarchitect/lexicon_arch)
  [![GitHub stars](https://img.shields.io/github/stars/jc-datarchitect/lexicon_arch?style=social)](https://github.com/jc-datarchitect/lexicon_arch/stargazers)
</div>

---

# lexicon_arch
A centralized, **bilingual (English-Spanish) technical taxonomy** designed to serve as a **Single Source of Truth (SSOT)** for architectural and engineering firms. 

This repository acts as a governance tool to ensure consistent terminology usage across international teams, streamline the onboarding process for new hires, and maintain high standards in BIM documentation, technical specifications, and project management.

---

## How to Contribute
We welcome contributions to keep our taxonomy current. Please follow these steps:
1. **Report a Change:** Open an [Issue](https://github.com/jc-datarchitect/lexicon_arch/issues) describing the term to add or modify.
2. **Review:** Our team will review the proposal against current code standards.
3. **Merge:** Once approved, we will update the master CSV files.

## Governance Policy
This repository follows strict data integrity standards:
* **SSOT:** The files in `/data` are the master source. Never modify them manually without prior approval.
* **Bilingual Consistency:** All terms must maintain the English/Spanish format defined in our style guide.
* **Validation:** All changes are audited to ensure compliance with our normative references in `/documents`.

---

## Project Structure

The repository is organized to facilitate rapid onboarding and ensure data integrity across project phases:

```text
lexicon_arch/
├── data/                               # Master CSV datasets (Single Source of Truth)
│   ├── lexicon_arch.csv                # Architecture, engineering, and regulatory terms
│   └── lexicon_vs.csv                  # Comparative matrix for technical nuances
├── documents/                          # Normative references and onboarding standards
│   ├── lexicon_onboarding_manual.md    # Technical guide for new hires
│   └── lexicon_normativas_codigos.md   # Normative and coding references
└── README.md                           # Documentation and governance guidelines
```
