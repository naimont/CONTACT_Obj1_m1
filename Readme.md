# Chlorine inactivation of enteric pathogens in agricultural water

Citation to the manuscript (TBD)

This depository contains data and codes associated with the study on the Chlorine inactivation of enteric pathogens in agricultural water. It is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## 📂 Files Included
### Data
- `obj1_chl_NM.txt`: Contains data on chlorine dosages and chlorine demand, used to assess residual chlorine levels under varying treatment conditions.
- `obj1_m1_NM.txt`: Contains microbial inactivation data collected under different experimental conditions, and microbial response reported at log<sub>10</sub> microbial counts.
### Codes/Outputs
- `UF_CONTACT_Obj1_NM012025.pdf`: Rendered output with integrated text, code results, and figures.

## 📊 Data Structure

| Column Name        | Variable type        | Description |
|--------------------|-------------|-------------|
| assay      |  Categorical      |  The assays used for the quantification of each microbial group |
|  chl.added  | Numerical        |  Free chlorine (ppm) dosages added to samples  |
|  chl.measured  | Numerical      |  Free chlorine (ppm) residual measured in the samples  |
|  chl.measured.ave  | Numerical      | Average of free chlorine (ppm) residual measured in the samples  |
|  chl.measured.se  | Numerical      | Standard error of free chlorine (ppm) residual averages measured in the samples  |
|  CLD.ave    | Numerical        | Average of chlorine demand in ppm free chlorine  |
|  CLD.se    | Numerical        | Standard error of chlorine demand averages in ppm free chlorine  |
| microb    | Categorical       |  Microbial groups |
| rep        | Numerical    |  Number of each biological repliate |
| sample     |  Categorical      |  Microbe-suspended matrix to be studied |
| sanitizer  |  Categorical      |  Type of the sanitizer
|  survival  |Numerical    |    Microbial survival
|  temp  |  Categorical  |  Temperature in which the samples were incubated (set to 12ºC)  |
|  time  |  Categorical  |  Time (min) in which the samples were incubated |

## 🧾 Categorical Variables and Levels
|Category  | Levels        | Description        | Unit|
|----  |-----------|--------------------|-----|
|assay|plate|Total plate count| log<sub>10</sub> Colony-Forming Units (CFU)/ml|
||plaque|Plaque assay  | log<sub>10</sub> Plauque-Forming Units (PFFU)/ml|
|sample|ag1, ag2|Preharvest agricultural waters from site 1 and 2 |-|
||di|deionizedd water|-|
|microbe|ec|Enteric bacteria: _Escherichia coli_ TVS 353|-|
||tv|Enteric virus: Tulane virus (a surrogate for human norovirus)|-|

Last update: April 19, 2025
