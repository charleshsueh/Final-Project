# EEG Eye State Classification Using Machine Learning Techniques

The project explores machine learning models for classifying eye states (open or closed) using EEG data.

## Paper(Manuscript)
The full report can be found in [`paper.pdf`](./paper.pdf).

## Presentation slides
[`Slides for data description`](https://charleshsueh.github.io/Final-Project/)

## Project Structure
```text
FinalProject/
├── paper/              # Final paper and source file
│   ├── paper.Rmd       # R Markdown source of the report
│   └── paper.pdf       # Compiled PDF of the final report
│
├── slides/             # Presentation slides
│   ├── index.Rmd       # R Markdown source of the slides
│   └── index.html      # Rendered HTML slides (e.g., xaringan or revealjs)
│
├── code/               # Scripts for data processing and modeling
├── data/               # Raw or preprocessed EEG data
├── figures/            # Visualizations and exported plots
└── README.md           # Project overview and instructions
```


## Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Multi-layer Perceptron (MLP)
- k-Nearest Neighbors (kNN)

## Feature Engineering
- Oversampling (to handle imbalance)
- LASSO and Random Forest feature selection
- Domain-specific interaction terms

## Results
- **SVM** achieved the best performance:
  - Accuracy: 94.6%
  - AUC: 0.982
- McNemar's test showed SVM, MLP, and kNN performed similarly (p > 0.05), while logistic regression performed significantly worse (p < 0.001).

## Dataset
Data: [UCI EEG Eye State Dataset](https://archive.ics.uci.edu/dataset/264/eeg+eye+state)

---

For more information, please see the full report.


