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

| Column Name        | Type        | Description |
|--------------------|-------------|-------------|
|day|numeric|Sampling intervals in days
| assay      | Categorical     | The assays used for the quantification of each microbial group |
| matrix     | Categorical        | Microbe-suspended matrix to be studied |
| microbe          | Categorical | Microbial groups |
|pH|Numerical|pH of water samples
| replicate   | Numerical     | Number of each biological repliate |
|survival|Numerical|Microbial survival
|temp |Categorical| Temperature in which the water samples were incubated (set to 12ºC) |
|week|Numerical|Sampling intervals in weeks |
|week_fac|Categorical|Sampling intervals in weeks |


## 🧾 Categorical Variables and Levels
|Category  | Levels        | Description        | Unit|
|----  |-----------|--------------------|-----|
|assay|plate|Total plate count| log<sub>10</sub> Colony-Forming Units (CFU)/ml|
||tcid50|50% Tissue Culture Infectious Dose (TCID<sub>50</sub>)| log<sub>10</sub> TCID<sub>50</sub>/ml|
||pcr|quantitative reverse transcription polymerase chain reaction (RT-qPCR)| log<sub>10</sub> Genome Copies (GC)/ml|
|matrix|ag3|Preharvest agricultural water, served as treatment|-|
||pbdw|Phosphate Buffer Dilution Water (PBDW), served as control group|-|
|microbe|ec|Enteric bacteria: _Escherichia coli_ TVS 353|-|
||nv|Enteric virus: Human norovirus GII (HuNoV GII)|-|
||tv|Enteric virus: Tulane virus (a surrogate for human norovirus)|-|

Last update: March 29, 2025
