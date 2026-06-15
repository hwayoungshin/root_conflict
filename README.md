## Root Conflict Detection with Public Utility GIS
A proof-of-concept geospatial workflow for detecting potential conflicts between predicted tree root zones and underground infrastructure using public utility datasets.

# Problem
Urban tree roots can interfere with underground infrastructure such as sewage pipes, water mains, and utility networks. However, underground assets are often invisible during routine tree inspections.

This project explores whether publicly available GIS datasets can be combined with predicted root structures to automatically identify potential root-obstacle conflicts.

# What I did
- Collected public Hong Kong sewage utility GIS datasets from the CSDI Geoportal
- Built simplified tree root buffers around tree locations
- Performed spatial intersection analysis using GeoPandas
- Generated automated conflict alerts when roots overlapped underground assets

# Technologies
- Python
- GeoPandas
- Shapely
- Pandas
- Matplotlib
- Jupyter Notebook

# Future Work
Integrate D50/D95 root predictions
Add water, gas, and electrical utility datasets

Data source: Hong Kong CSDI Geoportal (public utility datasets).
This repository demonstrates a proof-of-concept and is intended for research and prototyping purposes.
