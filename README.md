# ML For Imaging CW

Coursework for ML for Imaging 2022-2023 

The report can be found [here](MLI_CW_Report.pdf)

# Contributors
Khayle Torres: khayle.torres19@imperial.ac.uk

Nelson Da Silva: nelson.da-silva19@imperial.ac.uk

# Summary

The aim of this coursework is in order to use different machine learning models in order to perform age prediction. The dataset contains MRI data and age from 652 healthy subjects.

The split for each section are as follows:
- 52 for training/validation of segmentation method in part A
- 500 for training of age regression in part A & B
- 100 for final testing of age regression in part A & B

# Aims

The goal of each section are as follows:

### Part A
- MAE < 8 years

### Part B
- MAE < part A

# File Directory Structure

```
.
├── Logs/
│   └── *
├── Models/
│   ├── Part A/
│   │   └── *
│   └── Part B/
│       └── *
├── Notebooks/
│   ├── MLI_CW_Part_B_$.ipynb
│   └── MLI_CW_Part_A.ipynb
├── Plots/
│   ├── Part A/
│   │   └── *
│   └── Part B/
│       └── *
├── MLI_CW_Report.pdf
└── README.md
```