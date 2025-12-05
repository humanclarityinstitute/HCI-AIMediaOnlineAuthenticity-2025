# AI Media & Online Authenticity 2025 (Dataset n = 202)

Survey dataset examining how people judge authenticity online, their confidence in verification skills, and how AI-generated media influences trust, doubt, and everyday digital behaviour.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17744452.svg)](https://doi.org/10.5281/zenodo.17744452)

**Latest version:** v2.2 — 2025-12-05  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/ai-media-online-authenticity-2025-dataset/

**Data summary page:**  
https://humanclarityinstitute.com/data/ai-media-authenticity-data-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- Measures confidence in identifying AI-generated online content  
- Captures trust, doubt, verification behaviour, and judgement uncertainty  
- Includes a rich open-text reflection on authenticity concerns  
- Full demographic spine across six English-speaking countries  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|----------|-------------|
| **AIMediaOnlineAuthenticity_raw20251128.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **AIMediaOnlineAuthenticity_clean20251128.csv** | Clean, machine-readable dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **AIMediaOnlineAuthenticity_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

Data collected in **November 2025** via **Prolific** as part of HCI’s Human–AI Experience research programme.  
Participants provided **explicit consent** for anonymised publication.

### Sampling & Quality Controls

- **Final n:** 202  
- **Countries:** UK, US, Australia, New Zealand, Canada, Ireland  
- **Eligibility:** English-speaking adults, 18+, six English-speaking countries  
- **Compensation:** Average reward equivalent to **£9.59/hour**  
- **Approval-rate filter:** None  
- **Attention checks:** None  
- **AI-deception traps:** None  
- **Anonymisation:** Prolific IDs and timestamps removed before publication

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| **ai_media_confidence** | Likert 1–7 | Confidence judging whether online content is real or AI-generated |
| **trust_judgement** | Likert 1–7 | Trust in one’s ability to judge authenticity online |
| **uncertainty_effects** | Likert 1–7 | Behavioural and emotional effects of uncertainty |
| **open_text_authenticity_reflection** | Text | Reflection on a recent moment questioning online authenticity |
| **age_group** | Categorical | Self-reported age group |
| **gender** | Categorical | Self-identified gender |
| **country** | Categorical | Country of residence |
| **education_level** | Categorical | Highest level of education |
| **work** | Categorical | Employment status |
| **ai_tool_use_frequency** | Categorical | Frequency of using AI-powered tools |
| … | … | … |

**Multi-select formatting:**  
Stored as semicolon-delimited canonical tokens:  
`value_one;value_two;value_three`

**Open-text fields:**  
Minimal cleaning (trim + newline removal). Meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI |
|--------|------|
| Digital Life 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| Focus & Distraction 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086) |
| AI, Work & Human Identity 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17604671.svg)](https://doi.org/10.5281/zenodo.17604671) |
| Cognitive Load & Decision Offloading 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17636370.svg)](https://doi.org/10.5281/zenodo.17636370) |
| Digital Trust 2025 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |

---

## Related Reports

- **Digital Trust**  
  https://humanclarityinstitute.com/reports/digital-trust-full-report/

- **Digital Fatigue & Energy**  
  https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/

- **Why Can’t I Focus?**  
  https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose — including commercial use — provided appropriate credit is given.

---

## Recommended Citation

    @dataset{hci_ai_media_online_authenticity_2025,
      author       = {Human Clarity Institute},
      title        = {AI Media & Online Authenticity 2025},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {v2.2},
      doi          = {10.5281/zenodo.17744452},
      url          = {https://doi.org/10.5281/zenodo.17744452}
    }

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| **v2.2** | 2025-12-05 | Structural improvements to README layout; improved machine readability |
| **v1.1** | 2025-11-20 | Removed Prolific IDs; updated files and checksums |
| **v1.0** | 2025-11-20 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

**Website:** https://humanclarityinstitute.com  
**Email:** info@humanclarityinstitute.com

HCI is an independent research institute documenting the human experience of the AI era.
