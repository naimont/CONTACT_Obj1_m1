# Chlorine Inactivation of Enteric Pathogens in Agricultural Water

**Citation to the manuscript:** _TBD_

This depository contains data and codes associated with the study on the Chlorine inactivation of enteric pathogens in agricultural water. It is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

## 📂 Files Included

### 📊 Data
- `obj1_chl_NM.txt`: Contains chlorine dosage and chlorine demand data used to evaluate residual chlorine levels under varying treatment conditions.
- `obj1_m1_NM.txt`: Contains microbial inactivation data under different experimental conditions, with microbial response reported as log<sub>10</sub> microbial. counts.

### 📁 Code and Output
- `UF_CONTACT_Obj1_NM012025.pdf`: Rendered Quarto report including integrated code, results, and figures.

---

## :file_cabinet: Data Structure

| Column Name         |  Description |
|---------------------|------------|
| assay               |  Assay method used for microbial quantification |
| chl.added           |  Free chlorine dose added (ppm) |
| chl.measured        |  Free chlorine residual measured (ppm) |
| chl.measured.ave    |  Average free chlorine residual (ppm) |
| chl.measured.se     | Standard error of chlorine residuals (ppm) |
| CLD.ave             | Average chlorine demand (ppm) |
| CLD.se              | Standard error of chlorine demand (ppm) |
| microb              | Microbial group |
| rep                 | Biological replicate number |
| sample              | Suspension matrix |
| sanitizer           | Sanitizer used |
| survival            | Microbial survival |
| temp                | Incubation temperature (ºC) |
| time                | Incubation/contact time (min) |

---

## 🧾 Categorical Variables and Levels

| Category   | Levels       | Description                                                  | Unit |
|------------|--------------|--------------------------------------------------------------|------|
| assay      | `plate`      | Total plate count                                            | log<sub>10</sub> CFU/mL |
|            | `plaque`     | Plaque assay                                                 | log<sub>10</sub> PFU/mL |
| microb     | `ec`         | Enteric bacterium: _Escherichia coli_ TVS 353               | — |
|            | `tv`         | Enteric virus: Tulane virus (surrogate for human norovirus) | — |
| sample     | `ag1`, `ag2` | Preharvest agricultural water samples (site 1 and 2)         | — |
|            | `di`         | Deionized water                                              | — |
| time       | `5`, `10`    | Incubation/contact time                                      | minutes |

---

_Last updated: April 19, 2025_
