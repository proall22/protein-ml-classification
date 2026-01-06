# Protein Function Classification Using Machine Learning

This project applies supervised machine learning techniques to classify proteins into functional categories using numerical features derived from amino acid sequences. It demonstrates how computational methods can support biological research by accelerating protein function prediction.

---

## Overview

Protein function identification is a fundamental problem in bioinformatics. Experimental approaches are accurate but time-consuming and costly. This project explores a data-driven alternative using machine learning to learn patterns from known proteins and predict the function of unseen ones.

The work follows a complete scientific machine learning pipeline, from data loading and preprocessing to model training, evaluation, and interpretation.

---

## Objectives

- Apply machine learning to a real biological problem  
- Build a complete, reproducible ML pipeline  
- Evaluate model performance using standard metrics  
- Demonstrate interdisciplinary skills in biology and data science  

---

## Dataset

- Type: Tabular protein feature dataset  
- Each row represents one protein  
- Features include numerical descriptors derived from amino acid composition and physicochemical properties  
- Target variable: protein functional class  

The dataset format is compatible with common bioinformatics and ML benchmarks and can be replaced with UniProt or disease-specific protein data.

---

## Methodology

1. Data loading and inspection  
2. Feature-target separation  
3. Train–test split with stratification  
4. Model training using Random Forest classifier  
5. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix  

Random Forest was selected due to its robustness and ability to capture nonlinear relationships common in biological data.

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

All tools used are free and open source.

---

## Results

The trained model achieves strong classification performance across protein classes, indicating that numerical protein features contain meaningful biological signals. The confusion matrix highlights where misclassifications occur and provides insight into model behavior.

---

## Original Contribution

This project goes beyond basic tutorials by:

- Emphasizing biological interpretation, not just accuracy  
- Structuring the work like a scientific study  
- Designing the pipeline to be easily extended to:
  - Disease-related proteins (e.g., malaria, tuberculosis)
  - Drug–protein interaction prediction
  - Comparative analysis with other ML models  

---

## Limitations and Future Work

**Limitations**
- Feature-based approach does not capture full protein structure  
- Performance depends on dataset quality and size  

**Future Work**
- Deep learning on raw protein sequences  
- Integration with structural and genomic data  
- Application to African-specific disease research  

---

## Repository Structure
```
protein-ml-classification/
│
├── notebook/
│   └── protein_classification.ipynb
├── data/
│   └── protein_data.csv
├── figures/
│   └── confusion_matrix.png
├── report/
│   └── protein_ml_report.pdf
├── README.md
└── requirements.txt
````
---

## How to Run

1. Open the notebook in Google Colab  
2. Upload the dataset to the `data/` directory  
3. Run all cells sequentially  

No paid software or local setup is required.

---

## Author

Misgana(proall2)
