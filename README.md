research_project

Ancestry-Aware Deep Learning for Down Syndrome Facial Phenotyping in African Populations

Overview

This repository contains the complete pipeline used for the development, training, evaluation, and interpretation of deep learning models for facial phenotyping of Down syndrome across diverse populations, with a particular focus on African cohorts.

The project explores the use of artificial intelligence and computer vision techniques to improve equitable and inclusive genetic syndrome recognition in underrepresented populations. The study evaluates multiple convolutional neural networks (CNNs) and transformer-based architectures while incorporating explainable AI approaches to identify clinically relevant facial regions associated with Down syndrome.

Research Objectives

The primary objectives of this project are:

Develop deep learning models for automated Down syndrome facial phenotyping
Evaluate model performance across diverse ancestry-specific cohorts
Investigate cohort-aware and ancestry-aware classification performance
Compare CNN and transformer architectures
Interpret model predictions using explainable AI techniques such as Grad-CAM
Assess fairness and generalizability across African and non-African populations
Methodology
Data Processing

The pipeline includes:

Image preprocessing and normalization
Facial image quality control
Dataset balancing
Cohort-specific organization
Train/validation/test splitting
Cross-validation setup
Deep Learning Models

The study evaluates multiple architectures including:

CNN Architectures
MobileNetV2
DenseNet121
ResNet50
ConvNeXt-Tiny
VGG16
Transformer Architectures
Vision Transformer (ViT)
Swin Transformer
Evaluation Metrics

Models are evaluated using:

Accuracy
Precision
Recall
F1-score
AUROC
Confusion matrices
Cohort-level performance analysis
Cross-cohort generalization analysis
Explainable AI

The project uses Grad-CAM visualizations to:

Identify clinically relevant facial regions
Interpret model attention mechanisms
Compare attention patterns across cohorts
Validate biological and clinical relevance
Key Features
Multi-model deep learning benchmarking
Cohort-aware facial phenotyping
African population-focused analysis
Explainable AI integration
Cross-validation evaluation framework
Automated reporting and visualization
Comparative model analysis
Cohort-level confusion matrices
PCA-based feature clustering
Grad-CAM interpretability analysis
Repository Structure
research_project/
│
├── DS_Pipeline_Script_Python.ipynb   # Main experimental pipeline
├── README.md                         # Project documentation
│
├── data/                             # Dataset directories
├── models/                           # Saved trained models
├── reports/                          # Experimental outputs and metrics
├── figures/                          # Graphs and visualizations
├── gradcam/                          # Explainability outputs
├── confusion_matrices/               # Confusion matrix results
├── pca_analysis/                     # PCA and clustering outputs
└── logs/                             # Training and execution logs
Experimental Outputs

The pipeline automatically generates:

Classification reports
ROC curves
Precision-recall curves
Training history plots
Confusion matrices
Cohort-specific evaluation summaries
Grad-CAM visualizations
PCA clustering analyses
Cross-cohort comparison reports
Main Findings
ConvNeXt-Tiny achieved the strongest overall performance with high diagnostic accuracy and AUROC
Deep learning models consistently identified clinically relevant craniofacial regions associated with Down syndrome
No major systematic ancestry-related performance bias was observed
Cohort-aware training improved generalizability across diverse African populations
Grad-CAM analyses highlighted strong attention around the periocular region and nasal bridge
Technologies Used
Programming Languages
Python
Deep Learning Frameworks
TensorFlow
Keras
PyTorch
Libraries
OpenCV
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Grad-CAM utilities
Development Environment
Google Colab
Jupyter Notebook
Installation

Clone the repository:

git clone https://github.com/your-username/research_project.git
cd research_project

Install dependencies:

pip install -r requirements.txt
Usage

Open the notebook and run the pipeline:

jupyter notebook DS_Pipeline_Script_Python.ipynb

Or execute within Google Colab.

Ethical Considerations

This research focuses on equitable AI development for genetic diagnostics in underrepresented populations. All analyses were conducted with attention to:

Privacy preservation
Ethical AI practices
Fairness across ancestries
Responsible use of facial data
Bias assessment and mitigation
Research Significance

This work contributes to:

AI-driven precision medicine
Computational phenotyping
Rare disease diagnostics
African genomic and phenotypic representation
Inclusive artificial intelligence in healthcare
Future Work

Future extensions of this project include:

Expansion to additional genetic syndromes
Integration of 3D facial imaging
Federated learning approaches
Multi-modal phenotyping
Larger pan-African cohort studies
Advanced explainable AI methods
Authors
Japhet Dienda
Nicola Mulder
Christian D. Bope
Hocine Bendou
Aimé Lumaka

Affiliations:

University of Cape Town
University of Kinshasa
African Rare Disease Initiative
Citation

If you use this repository or methodology in your work, please cite:

@article{research_project_2026,
  title={Ancestry-Aware Deep Learning for Down Syndrome Facial Phenotyping in African Populations},
  author={Dienda, Japhet and Mulder, Nicola and Bope, Christian D. and Bendou, Hocine and Lumaka, Aimé},
  year={2026}
}
License

This project is intended for academic and research purposes only.
