Deciphering Land Use–Carbon Emissions–Economy Nexus: Decoupling Dynamics and Sustainable Planning Pathways

This repository contains the original codes used in the study Deciphering Land Use–Carbon Emissions–Economy Nexus: Decoupling Dynamics and Sustainable Planning Pathways. The project integrates land use, socioeconomic, and meteorological data to construct regression-based models, optimize them, and interpret the results for sustainable planning research.
https://www.cell.com/nexus/fulltext/S2950-1601(25)00035-X

📂 Code Overview

Data integration
This code merges land use data from GIS with panel data from statistical yearbooks.

Optimal base model selection
This part of the code identifies and selects the base models required for regression analysis.

Hyperparameter optimization
This section performs hyperparameter tuning on the selected base models.

Model interpretability
This section enhances model interpretability by applying the SHAP method.

📊 Data Availability

Land use data: [DOI: 10.12078/2018070201]

Statistical yearbooks and panel data: National Bureau of Statistics of China

Meteorological data: [DOI: 10.12078/2022082501]

All other materials, algorithms, and models are detailed in Supplemental Information, Section S.2 Materials and Methods.

⚙️ Requirements

Python ≥ 3.9

Key packages: pandas, numpy, scikit-learn, shap, matplotlib

Install dependencies:

pip install -r requirements.txt

▶️ Usage

Data preparation

Place land use, statistical, and meteorological data in the data/ folder.

Run base model selection

python model_selection.py


Perform hyperparameter optimization

python hyperparameter_optimization.py


Model interpretability with SHAP

python model_interpretability.py
