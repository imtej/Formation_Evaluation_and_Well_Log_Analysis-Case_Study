# Well Log Analysis & Formation Evaluation Case-Study

This repository contains a comprehensive analysis of well log data and formation evaluation aimed at solving key geological problems. The project is divided into two primary sections: **Well Log Analysis (Case Study)** and **Formation Evaluation (Case Study)**, with data drawn from real-world well logs to provide detailed insights into subsurface characteristics.

## Objectives

### Well Log Analysis (Case Study)
The well log analysis focuses on addressing the following key problems:
1. **Gamma Ray Tool Design**: Propose necessary instrumentation requirements for designing a gamma ray tool if the department intends to build one.
2. **Quality Control**: Perform quality control of wireline logs and identify outliers in the basic well logs.
3. **Total Porosity Calculation**: Calculate total porosity from the combination of density and neutron logs, and identify zones with the highest porosity.
4. **Velocity-Depth Profile**: Plot velocity-depth profiles (compressional and shear), color-coded with volume of shale.
5. **Water Saturation (Sw) Calculation**: Use Archie’s method to calculate water saturation (Sw) and flag reservoir zones where volume of shale (Vsh) ≤ 0.4 and Sw ≤ 0.7.
6. **Reservoir Zone Reporting**: Report total porosity, water saturation, and Vsh along with their standard deviations for the reservoir zone.

### Formation Evaluation (Case Study)
This section involves the interpretation of well data for the **Gorgonichthys-1 well**, located in the NWS, Western Australia. The formation evaluation is focused on the **Brewster Member**, and involves the following steps:
1. **Optimize Porosity Calculation**: Calibrate neutron and density log-derived porosity with core data to optimize total porosity calculation.
2. **Water Saturation Comparison**: Calculate water saturation using both Archie and Simandoux methods, then compare the results.
3. **Net-to-Gross (NTG) Estimation**: Estimate the NTG ratio with cutoffs: Vsh < 50%, φ > 5%, and Sw < 50%.
4. **Porosity-Permeability Relationship**: Build an empirical porosity-permeability relationship from core data, discard anomalous data points during regression analysis, and compute a continuous permeability profile from the porosity log.

## Data Sources
- Digital log datasets, formation tops, porosity-permeability database, and well completion reports for **Gorgonichthys-1 well** located in Western Australia.

Links to download the well data:
- [Gorgonichthys-1 Well Information](https://wapims.dmp.wa.gov.au/WAPIMS/)
- [Additional Formation Data](https://nopims.dmp.wa.gov.au/nopims)

## Key Technologies
- **Python**
- **NumPy**, **Pandas** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for machine learning algorithms used in lithofacies classification
- **Petrophysics tools** for well log interpretation and formation evaluation

## Results
The project provides insights into:
- Total porosity and water saturation estimation using advanced methods.
- Continuous permeability profile derived from porosity logs, improving the understanding of subsurface characteristics.
- Best-performing machine learning models for lithofacies classification using well log data.
  
## License
This project is licensed under the MIT License.
