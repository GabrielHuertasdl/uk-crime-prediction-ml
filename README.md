# UK Crime Prediction Project — Gabriel Pierre Huertas de Las Puertas  
Coventry University

This repository contains the full submission for the 6001CMD Machine Learning coursework.  
It includes the academic report, the Jupyter Notebook used for data processing and modelling,  
and the required presentation video.

---

##  Project Structure
├── 6001CMD_Coursework Template_25-26s1(1).docx
├── ASSESMENT.IA.ipynb
├── README.md
└── simplescreenrecorder54-2025-12-01_12.24.25.mp4

### **File Descriptions**

- **6001CMD_Coursework Template_25-26s1(1).docx**  
  Complete academic coursework report including methodology, data sources, modelling, results, and conclusions.

- **ASSESMENT.IA.ipynb**  
  Jupyter Notebook containing all code for data cleaning, feature engineering, exploratory analysis, model training, evaluation, and visualisation.

- **simplescreenrecorder54-2025-12-01_12.24.25.mp4**  
  Presentation video summarising the project workflow, modelling techniques, and final findings.

---

##  Dataset Availability

The original datasets used in this project **cannot be uploaded** due to storage limitations and licensing restrictions.  
However, the official dataset sources are listed below.

### **Dataset Links**  
(Insert your links here)

- UK Police Crime Data (API & Monthly CSV):  
  *[Insert link]*

- UK Census 2021 (ONS / Nomis):  
  *[Insert link]*

- LSOA Boundary Shapefiles:  
  *[Insert link]*

---

##  Project Summary

This project focuses on predicting monthly crime counts in UK LSOAs (Lower Layer Super Output Areas) from **2022 to 2025**.  
The analysis integrates:

- UK Police crime event data  
- Socio-economic indicators from Census 2021  
- Geospatial LSOA boundaries  

Multiple regression models were evaluated, including:

- **Ordinary Least Squares (OLS)**  
- **Random Forest Regressor**  
- **XGBoost Regressor**

Chronologically consistent train/validation/test splits were implemented, including the optimal split ratio proposed by **Joseph (2022)**.

---

##  Requirements & Execution

To run the notebook, install the following Python libraries:

pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn


Optional for high-performance processing:

modin
ray 


It provides an overview of the methodology, system design, modelling steps, and key outcomes.

---

##  Author

**Gabriel Pierre Huertas de Las Puertas**  
Coventry University  
6001CMD — Machine Learning Coursework

---

##  License

This project is submitted exclusively for academic purposes under Coventry University regulations.  
External datasets must be accessed and used according to the legal terms of their providers.


