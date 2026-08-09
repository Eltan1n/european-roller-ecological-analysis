# Spatial Ecology & Climate Exposure Modeling for the European Roller (Coracias garrulus)

## Overview
This repository contains the term project developed for the "Current Topics in Ecology" course at the Molecular Biology and Genetics Department. The project investigates how projected mid-century climate warming (2041–2060) under CMIP6 SSP scenarios may alter the climatic exposure of the European Roller (*Coracias garrulus*) in Turkey.

## Methodology & Tools
* **Language:** R
* **Key Packages:** `terra`, `geodata`
* **Data Sources:** 
  * **Occurrence Data:** 7,818 validated presence records compiled from the Global Biodiversity Information Facility (GBIF).
  * **Climate Data:** Present-day bioclimatic variables from WorldClim and mid-century projections from the CMIP6 global climate model (MIROC6) under SSP2-4.5 and SSP5-8.5 scenarios.
* **Analysis:** Processed large-scale raster matrices to evaluate annual mean temperature (BIO1) shifts and calculated spatial difference layers ($\Delta\text{BIO1} = \text{SSP5-8.5} - \text{current}$).

## Results & Visualizations
* **Occurrence Mapping & Seasonality:** Analyzed temporal histograms showing that observations concentrate between May and August, aligning with the species' breeding season in Turkey.
* **Climate Exposure:** Mapped widespread warming signals across Turkey by mid-century, with the strongest temperature increases concentrated in inland regions, potentially heightening thermal stress during the breeding period.
