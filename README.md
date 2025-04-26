# Non-Contact Thickness Estimation of High-Temperature Oxide Layers on AISI 1045 Steel Using Infrared Thermography and Tree-Based Machine Learning

Antony Morales-Cervantes [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3669--2638-green)](https://orcid.org/0000-0003-3669-2638);  
Gerardo Marx Chávez-Campos [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3945--9903-green)](https://orcid.org/0000-0003-3945-9903);  
Héctor Javier Vergara-Hernández [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--6224--1027-green)](https://orcid.org/0000-0001-6224-1027);  
Maritza Fabiola León-Bejarano [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0981--3262-green)](https://orcid.org/0000-0003-0981-3262);
Jorge Sergio Téllez-Martínez [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0587--0059-green)](https://orcid.org/0000-0003-0587-0059)

This repository contains the datasets generated for the study **"Non-Contact Thickness Estimation of High-Temperature Oxide Layers on AISI 1045 Steel Using Infrared Thermography and Tree-Based Machine Learning."** The study focuses on predicting total specimen thickness variations — encompassing thermal expansion, oxide growth, and mechanical deformation — using thermographic imaging and supervised regression models.

---

##  Contents

- **Thermal Images**:  
  Time-series thermograms captured during high-temperature oxidation of AISI 1045 steel using an Optris PI 1M infrared camera.

- **Micrometer Data**:  
  Thickness measurements acquired using a micrometer, reflecting total changes throughout the experiments.

- **Folder Structure**:
  - `Thermograms/`: Contains zipped folders for each experiment with thermal images in CSV.
  - `Micrometer/`: Contains xlsx files with thickness measurements that match thermal image timestamps.
 
Across all experiments, a total of 3386 synchronized thermal frames and thickness measurements were collected.

---

##  Methodology

Steel specimens were subjected to Joule-heating experiments under controlled conditions. Thermal images were recorded. Micrometer readings were taken periodically during heating and cooling stages.  
The goal was to train machine learning regressors capable of estimating specimen thickness variations purely from thermal imaging data.
Each experiment yielded approximately 700 paired measurements of temperature fields and corresponding specimen thickness values. This dense temporal sampling enabled precise tracking of thickness evolution throughout the oxidation process.

---

## Purpose

This dataset supports the advancement of non-invasive monitoring methods in metallurgy, high-temperature material characterization, and industrial quality control using infrared thermography combined with machine learning.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/morales-cervantes/Thickness_Estimation_Dataset.git
Explore the Dataset:

Thermal images are organized per experiment in Thermograms/.

Thickness measurements corresponding to each thermal sequence are in Micrometer/.

Link the Data: Time-aligned for supervised regression model training.

📄 Data Availability Statement
The datasets are available through this GitHub repository and will be permanently archived with a DOI via Zenodo upon publication.

## Citation
If you use this dataset, please cite:

Morales-Cervantes, A., Chávez-Campos, G. M., Vergara-Hernández, H. J., León-Bejarano, M. F., Téllez-Martínez, J. S. (2025). Non-Contact Thickness Estimation of High-Temperature Oxide Layers on AISI 1045 Steel Using Infrared Thermography and Tree-Based Machine Learning.

## Authors' Contributions
Antony Morales-Cervantes led the data acquisition and analysis. All authors contributed to data interpretation, experimental setup, and manuscript preparation. All authors reviewed and approved the final version of the work.

## License
This dataset is distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
