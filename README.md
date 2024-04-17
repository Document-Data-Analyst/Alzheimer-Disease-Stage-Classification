# Alzheimer-Disease-Stage-Classification

## Introduction

This repository contains the implementation of a classification
framework for Alzheimer\'s disease stages using Vision Transformers
(ViTs) applied to brain MRI scans. The project aims to facilitate early
diagnosis and descriptive caption of brain scan.

## Features

-   Classification of Alzheimer\'s disease stages: Alzheimer\'s disease,
    Cognitive Normal (CN), Early Mild Cognitive Impairment (EMCI), Late
    Mild Cognitive Impairment (LMCI), and Mild Cognitive Impairment
    (MCI).
-   Utilizes Vision Transformer architecture for image classification.
-   Generation of descriptive PDF reports for each class to aid
    interpretation of results.

## Dataset

The MRI images utilized in this study were gathered from the Alzheimer's
Disease Neuroimaging Initiative (ADNI) dataset, including both ADNI and
ADNI-Axial datasets. The dataset includes structural MRI scans of
Alzheimer\'s disease patients at different stages.
![image](https://github.com/Document-Data-Analyst/Alzheimer-Disease-Stage-Classification/assets/22766772/75c34b79-181c-4bd3-bd6d-9fe0452e1ac0)


## Methodology

-   Preprocessing: The original MRI data were preprocessed to extract
    brain scans and remove irrelevant information.
-   Vision Transformer Architecture: Implemented the Vision Transformer
    architecture, which transforms 2D images into a series of flattened
    patches and utilizes self-attention mechanisms.
-   Model Training: The model was trained on the preprocessed MRI images
    using PyTorch and Google Colab.
-   Evaluation: Performance evaluation metrics include accuracy,
    precision score, F1 score, AUC curve, and Confusion Matrix.
![image](https://github.com/Document-Data-Analyst/Alzheimer-Disease-Stage-Classification/assets/22766772/95fa823e-239c-4b19-9721-ed4da7068402)

## Results

-   Achieved an accuracy of 88% and an AUC score of 0.92 on the ADNI
    dataset.
-   Comparative analysis with existing literature shows competitive
    performance of the proposed method.
![image](https://github.com/Document-Data-Analyst/Alzheimer-Disease-Stage-Classification/assets/22766772/6c76cd66-1948-45be-9f46-8d23179e18eb)

## Conclusion

The project demonstrates the effectiveness of Vision Transformers in
classifying Alzheimer\'s disease stages from brain MRI scans. The
findings highlight the potential for automated diagnosis and contribute
to advancing computer-aided diagnosis for Alzheimer\'s disease.

## Usage

1.  Clone the repository:

        git clone https://github.com/username/alzheimers-disease-classification.git

2.  Install dependencies:

        pip install -r requirements.txt

3.  Run the main script:

        python main.py

## Acknowledgments

We acknowledge the Alzheimer's Disease Neuroimaging Initiative (ADNI)
for providing the dataset used in this project.

