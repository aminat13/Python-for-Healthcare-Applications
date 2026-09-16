# Python-for-Healthcare-Applications

## Overview

This repository contains three projects completed as part of the **Programming for Healthcare Applications** module of my MSc in Technologies and Analytics in Precision Medicine at RCSI.

The assignments progressively applied Python programming to healthcare and biomedical problems, moving from core Python data structures to object-oriented programming, biological sequence analysis, and exploratory analysis of clinical trial data.

The projects demonstrate the use of Python for organising, processing, analysing and visualising healthcare data.

---

## Project 1 — Patient Data Store

The first project developed a simple Python-based patient record system to explore how different data structures can be used to store, retrieve and modify electronic health record information.

Patient information including identifiers, age, medication and dosage was processed using strings, lists, tuples and nested dictionaries. The final structure enabled individual patient records to be retrieved and updated using patient identifiers.

### Workflow

```text
Patient data input
        ↓
String parsing and type conversion
        ↓
Lists and tuples
        ↓
Record modification
        ↓
Nested dictionary construction
        ↓
Patient record retrieval and summary statistics
```

### Key Skills

- Python syntax and variables
- String manipulation and parsing
- Lists, tuples and dictionaries
- Nested data structures
- Indexing and data retrieval
- Data type conversion
- Logical and comparison operators
- Basic descriptive statistics
- Patient record organisation

---

## Project 2 — Personal Health Record

The second project developed an object-oriented Personal Health Record system representing different types of patients within a hospital environment.

A hierarchy of `Person`, `Patient` and `InHospitalPatient` classes was created to demonstrate inheritance, encapsulation and polymorphism. Patient functionality included BMI calculation, medical-history management, hospital admission information and biological sequence analysis using Biopython.

Patient data stored in Excel was subsequently processed using pandas and used to generate patient objects programmatically.

### Workflow

```text
Person class
      ↓
Patient class
      ↓
InHospitalPatient class
      ↓
Patient dataset import with pandas
      ↓
BMI calculation and patient classification
      ↓
Patient object generation
      ↓
DNA sequence analysis with Biopython
```

### Key Skills

- Object-oriented programming
- Classes and object creation
- Inheritance
- Encapsulation
- Polymorphism
- Getter and setter methods
- Conditional logic and loops
- pandas DataFrames
- Excel and CSV file handling
- BMI calculation and derived variables
- Biopython
- DNA sequence processing
- GC-content calculation
- DNA transcription and translation

---

## Project 3 — Lung Cancer Clinical Trial Analysis

The final project applied Python to exploratory analysis of a synthetic lung cancer clinical trial dataset containing **300 patients and 17 clinical, demographic, genetic and treatment variables**.

The workflow covered data inspection, missing-value handling, duplicate detection, outlier management and feature engineering before exploring relationships between patient characteristics, genetic mutations, treatment variables and clinical outcomes.

Data visualisation was used to investigate patterns in tumour stage, BMI, treatment response, risk classification and other clinical variables.

### Workflow

```text
Clinical trial dataset
        ↓
Data inspection and quality assessment
        ↓
Missing-value and duplicate handling
        ↓
Outlier and inconsistency management
        ↓
Risk and severity feature engineering
        ↓
Exploratory data analysis
        ↓
Genetic and treatment subgroup analysis
        ↓
Statistical summaries and correlations
        ↓
Clinical data visualisation
```

### Key Skills

- Python
- pandas
- NumPy
- Data cleaning and preprocessing
- Missing-value imputation
- Duplicate detection
- Outlier handling
- Feature engineering
- Exploratory data analysis
- Grouped and aggregated analysis
- Cross-tabulation and pivot tables
- Correlation analysis
- Clinical and genetic data analysis
- Matplotlib
- Seaborn
- Data visualisation
- Interpretation of clinical data

---

## Technical Skills Demonstrated

**Programming:** Python, conditional statements, loops, functions, object-oriented programming

**Data Analysis:** pandas, NumPy, data cleaning, feature engineering, descriptive statistics, grouped analysis, correlation analysis

**Visualisation:** Matplotlib, Seaborn, bar plots, box plots, scatter plots, heatmaps, count plots and pair plots

**Biomedical Applications:** electronic health records, patient data management, clinical trial data analysis, genetic mutation analysis and biological sequence analysis with Biopython

**Data Handling:** CSV and Excel import/export, nested data structures, DataFrames and structured patient records

---

## Repository Structure

```text
.
├── README.md
├── 01_patient_data_store/
│   └── patient_data_store.ipynb
├── 02_personal_health_record/
│   └── personal_health_record.ipynb
└── 03_lung_cancer_clinical_trial/
    └── lung_cancer_analysis.ipynb
```

---

## Collaboration

The **Patient Data Store** project was completed independently.

The **Personal Health Record** and **Lung Cancer Clinical Trial Analysis** projects were completed collaboratively with [@dohertyA7551](https://github.com/dohertyA7551) and Robin Joseph. 
