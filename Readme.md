# Chlorine Inactivation of Enteric Pathogens in Agricultural Water

**Citation to the manuscript:** _TBD_

This repository contains data and code associated with the study on chlorine inactivation of enteric pathogens in preharvest agricultural water. It includes microbial survival data, chlorine demand measurements, and a rendered analysis report created using Quarto.

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

## 📂 Files Included

### 📊 Data
- `obj1_chl_NM.txt`: Contains chlorine dosage and chlorine demand data used to evaluate residual chlorine levels under varying treatment conditions.
- `obj1_m1_NM.txt`: Contains microbial inactivation data under different experimental conditions, with microbial response reported as log₁₀ microbial counts.

### 📁 Code and Output
- `UF CONTACT Obj1_NM041925.pdf`: Rendered Quarto report including integrated code, results, and figures.

---

## 🗃️ Data Structure

| Column Name         | Description |
|---------------------|-------------|
| assay               | Assay method used for microbial quantification |
| chl.added           | Free chlorine dose added (ppm) |
| chl.measured        | Free chlorine residual measured (ppm) |
| chl.measured.ave    | Average free chlorine residual (ppm) |
| chl.measured.se     | Standard error of chlorine residuals (ppm) |
| CLD.ave             | Average chlorine demand (ppm) |
| CLD.se              | Standard error of chlorine demand (ppm) |
| microb              | Microbial group |
| rep                 | Biological replicate number |
| sample              | Suspension matrix |
| sanitizer           | Sanitizer used |
| survival            | Microbial titer |
| temp                | Incubation temperature (ºC) |
| time                | Incubation/contact time (min) |

---

## 🧾 Categorical Variables and Levels

| Variable   | Levels        | Description                                                  | Unit               |
|------------|----------------|--------------------------------------------------------------|--------------------|
| assay      | `plate`        | Total plate count                                      | log₁₀ CFU/mL       |
|            | `plaque`       | Plaque assay                                                 | log₁₀ PFU/mL       |
| microb     | `ec`           | Enteric bacterium: *Escherichia coli* TVS 353               | —                  |
|            | `tv`           | Enteric virus: Tulane virus (HuNoV surrogate)               | —                  |
| sample     | `ag1`, `ag2`   | Agricultural water samples from site 1 and 2                | —                  |
|            | `di`           | Deionized water                                              | —                  |
| time       | `5`, `10`      | Incubation/contact time                                      | minutes            |

---

_Last updated: April 19, 2025_
