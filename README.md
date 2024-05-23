# Breast Cancer Classification Project

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to build a machine learning model to classify breast cancer tumors as benign or malignant using the Breast Cancer Wisconsin dataset. We use various features such as mean, standard error, and worst values of tumor characteristics to train our models. The goal is to help in early detection and diagnosis of breast cancer, potentially aiding in better treatment outcomes.

## Dataset
The dataset used for this project is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). It includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. 

### Features
- **Radius**: Mean, standard error, and worst of distances from center to points on the perimeter.
- **Texture**: Mean, standard error, and worst of gray-scale values.
- **Perimeter, Area, Smoothness, Compactness, Concavity, Concave Points, Symmetry, Fractal Dimension**: Mean, standard error, and worst values.

### Target
- **Diagnosis**: B (benign) or M (malignant).

## Installation
To get started, clone the repository and install the required dependencies.
```bash
git clone https://github.com/esimonds09/breast-cancer-data-analysis.git
cd breast-cancer-classification
pip install -r requirements.txt
