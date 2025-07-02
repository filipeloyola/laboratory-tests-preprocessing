# laboratory-tests-preprocessing-

[![DOI](https://zenodo.org/badge/475143794.svg)](https://zenodo.org/badge/latestdoi/475143794)

Preprocessing laboratory tests results data by COVID-19 patients from Hospital Sirio Libanes. This repository contains one Jupyter notebook and one .csv file.

## Original data
This work used original data from COVID-19 Data Sharing/BR FAPESP, available at https://repositoriodatasharingfapesp.uspdigital.usp.br/, referent to Sirio Libanes hospital from Sao Paulo, Brazil. 

## Jupyter Notebook
File containing filters steps to preprocessing. Patients were labeled according to the origin of laboraty tests, as shown below:

- GROUP_0 - patients with exams coming only from the emergency room (NO_SEVERE);

- GROUP_1 - patients with exams from the emergency room and hospitalization (NO_SEVERE);

- GROUP_2 - patients with exams from the emergency room and ICU (SEVERE);

- GROUP_3 - patients with exams from the emergency room, hospitalization and ICU (SEVERE).

## .csv file
Contains the data resulted from preprocessing described in the notebook. Next are the main characteristics of the output dataset:
- File name: sirio_aprendizado_v3.csv
- Missing rate: 13.2%
- Instances: 4320
- Classes: 2 (SEVERE and NO_SEVERE)
- Features categorical: 2
- Features continous: 2
