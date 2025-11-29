# UniTo-spatial-statistic-project-
Markdown project on variography and geostat data with Matteo Cucca **under supervison of Rosaria Ignaccolo, UniTo**
# Spatial Statistics Project — NO₂ Analysis in Piemonte  
### Educational university project (R Markdown)

## Description

This repository contains an **entirely educational and university-based project** developed for a course in **Spatial Statistics**.  
The objective was to perform an end-to-end spatial analysis of nitrogen dioxide (NO₂) concentrations across monitoring stations in the Piemonte region (Italy), using both **sf** and **sp** spatial frameworks in R.

The project includes:

- manipulation of spatial coordinates  
- thematic mapping (2D, 3D, bubble plots, logarithmic maps)  
- exploratory data analysis  
- spatial correlation study  
- variogram cloud and sample variogram  
- fitting theoretical variogram models (Spherical, Exponential)  
- comparison of fitted models using SSE  

### Educational Purpose

This work has **no research or publication purpose**.  
It was completed **exclusively for coursework** in Spatial Statistics, and all methods were implemented with a **didactic and learning-oriented goal**.

The analyses, code structure, and explanations were **inspired by the course notes and examples provided during the university lectures**, combined with personal exploration and implementation in R.

---

## Contents

This folder typically includes:

- `NO2_spatial_analysis.Rmd` — full annotated R Markdown analysis  
- `NO2_spatial_analysis.pdf` — rendered PDF version  
- `data/NO2.csv` — dataset of NO₂ concentrations  
- `data/confini_piemonte.txt` — boundary coordinates of Piemonte  
- supporting plots and outputs  

---

## Methods and Tools Used

- **R base**  
- **sp** — SpatialPoints / SpatialPointsDataFrame manipulation  
- **sf** — simple features, CRS handling, polygon creation  
- **ggplot2** — thematic maps  
- **scatterplot3d** — 3D dispersion visualization  
- **spplot**, **bubble** — log-scale maps & bubble charts  
- **gstat** — variogram analysis and model fitting  

---

## Notes

- The project uses **public datasets supplied by the professor**.  
- The structure of the analysis follows the **educational workflow taught in class**.  
- This repository exists to showcase competency in spatial data handling and geostatistical modeling with R.  

---

## License

This work is provided for **academic and demonstrative purposes only**.


