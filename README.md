README for data associated with “Resource scarcity prevents cheating in a highly social bacterium”

## Overview
This project investigates the effect of the level of nutrient availability on subsequent proficiency of sporulation in a cooperatively sporulating soil bacterium. It comprises two experiments. The raw data from these experiments may be found in the files:
data_labstrains.csv
data_naturalisolates.csv
Data were collected by Pauline Manhes.

Data are analyzed in R, by the files rmd_labstrains.Rmd and rmd_naturalisolates.Rmd. This analysis is documented in the files doc_labstrains.html and doc_naturalisolates.html.

## Notes on data files
### data_labstrains.csv

Strains were cultured in liquid medium with either high or low nutrient concentration, then plated onto nutrient-free agar plates to instigate development. Spores were harvested after 5 days and dilution plated to count CFUs. All other strains were mixed with GJV1 to test for cheating.

Strains:
- GJV1
- GJV9 (Ch1)
- GVB206.3 (Ch2)
- DK5208 (csgA)

In replicate 2, GJV1 low/high:Ch1 high dilution plates with kanamycin were contaminated, so these data points are not considered in the analysis.

### data_naturalisolates.csv

Strains were cultured in liquid medium with either high or low nutrient concentration, then plated onto nutrient-free agar plates to instigate development. Spores were harvested after 5 days and dilution plated to count CFUs. All strains were mixed with each other to test for social exploitation.

Strains:
- D (DK801)
- D + kanamycin resistance
- G (Mxx41)
- G + novobiocin resistance
- I (Mxx144)

In replicate 4, the D high:I high dilution 3 plate without antibiotics was contaminated, so we use the dilution 4 plate.

G’s ancestor was never assayed at low nutrient conditions.
