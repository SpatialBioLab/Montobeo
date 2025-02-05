# Montobeo

### Scripts used in GEE

Habitat trends in the Special Area of Conservation of Montesinho/Nogueira are calculated with three scripts:
- The main one implements MaxEnt modeling and calculates the Sen SLope of the trends;
- **predictors.js** is called by the main script to obtain the predictor variables
- **kendallPValue.js** is called to calculate the p-value of the trends
- To obtain the predictor variables, call the secondary script predictors.js and to obtain the p-value of the trends, call kendallPValue.js

Programming language is javascript, used to interact with the GEE platform.

### HS Trend Analysis - R script
R script used to analyze the results of habitat suitability trends found in the Montobeo project
