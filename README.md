# Introduction to Machine Learning in Chemistry

This repository contains two lectures and a 3 session workshop on introducing machine learning concepts in the advanced physical chemistry module at UoE. 

## Author
Dr Antonia Mey -- antonia.mey@ed.ac.uk

## Workshop Notebooks

| Units                | Materials |
|-----------|-------------------------|
|Unit_01: Dimensionality Reduction|[![MDA Part 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_01/1_DR_part1.ipynb)|
|Unit_02: Clustering|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_02/01_clustering.ipynb) |
|Unit_02: Classification|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_02/02_classification.ipynb) |
|Unit_03: Neural Networks and PyTorch|[![Part3](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_03/01_Intro_to_pytorch.ipynb)|
|Unit_03:  Deep Learning for Solubility Classification|[![Part3](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_03/02_Solubility_classification.ipynb)|

## Local installation

1. Install [anaconda](https://www.anaconda.com/products/distribution).
2. Create a new environment:

   `conda create -n ml_chem`
   
3. Activate the environment:

   `conda activate ml_chem`
   
4. Install [mamba](https://anaconda.org/conda-forge/mamba) to make the installation of packages faster.

   `conda install -c conda-forge mamba`
   
5. Install all the required packages with mamba:

   `mamba install -c conda-forge mdanalysis mdanalysistests mdanalysisdata nglview scikit-learn ipywidgets=7.6.0`

## Project

Release: 13/02/2023  
Report Deadline: 10/03/2023  
Weight: 20%

## Summary of Lectures
### Lecture 1:
- What is machine learning?
- Examples of machine learning (in Chemistry)
- Introduction to unsupervised learning:
   - Clustering (k-means and others)
   - How does actual input data look like?
- Molecular fingerprints and nomenclature
Introduction to supervised learning:
- What is a classification problem?

### Lecture 2:
- Unsupervised learning continued:
   - Dimensionality reduction (PCA)
   - t-SNE
- Regressions
- Classifications in practice:
   - Random Forests
   - Multilayer perceptrons 

### Accompanying Notebooks:

| Session                 | Materials |
|-----------|-------------------------|
|Dimensionality Reduction|[![MDA Part 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_01/1_DR_part1.ipynb)|
|Clustering and Regressions|[![Part2](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Edinburgh-Chemistry-Teaching/ML-for-Chemistry/blob/main/Unit_02/02_clustering.ipynb) |

## Learning Outcomes
- Understand the main pillars of machine learning
- Know about different clustering techniques as part of unsupervised learning
- Be able to use common nomenclature used in machine learning
- Use Principle component analysis to reduce the dimensions of a data set
- Understand how a regression problem can be cast as a machine learning problem 
- Be aware of how random forests and multilayer perceptrons can be used in a classification problem



## Additional Resources
A handout with additional resources can be found [here.](https://github.com/meyresearch/ML_for_chemistry/blob/main/Handout.pdf)
