# CONTACT_Obj1_m1
This depository contains data associated with the study on the chlorine inactivation of enteric pathogens in preharvest agricultural water. It is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## 📂 Files Included

- `obj1_chl_NM.txt`: Chlorine dosage, residual chlorine, and chlorine demand data.
- `obj1_m1_NM.txt`: Microbial inactivation data following chlorine treatment.

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
