# Cat Breed Classification with CNN Transfer Learning

This repository contains an AI image classification project for the **Principle of Artificial Intelligence** course.

The project focuses on **animal subspecies classification** by training CNN transfer learning models to classify five cat breeds from the Oxford-IIIT Pet Dataset.

## Overview

Cat breed classification can be challenging because some breeds have visually similar features. This project compares three CNN architectures to identify which model performs best for this classification task:

- ResNet50
- DenseNet121
- MobileNetV3Small

The models are compared using:

- Accuracy
- Mean average precision, mAP
- Training time
- Number of parameters
- Accuracy and loss graphs
- Confusion matrices

## Dataset

Dataset: Oxford-IIIT Pet Dataset  
Source: https://www.robots.ox.ac.uk/~vgg/data/pets/

Selected cat breed classes:

1. Abyssinian
2. Bengal
3. Birman
4. Bombay
5. British Shorthair

The notebook downloads the dataset automatically, filters the selected cat breeds, and creates training, validation, and testing splits.

## Repository Contents

```text
notebooks/
  00_full_cat_breed_project_colab.ipynb

results/
  README.md

README.md
```

## Main Notebook

Open the full project notebook in Google Colab:

[Open in Colab](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/00_full_cat_breed_project_colab.ipynb)

Before running the notebook, enable GPU:

```text
Runtime > Change runtime type > Hardware accelerator > GPU
```

The notebook includes:

1. Dataset download
2. Dataset filtering for five cat breeds
3. Train, validation, and test split creation
4. Dataset visualization
5. ResNet50 training and evaluation
6. DenseNet121 training and evaluation
7. MobileNetV3Small training and evaluation
8. Model comparison table
9. Final conclusion draft
10. Graph results preview for GitHub

## Expected Results Files

After running the notebook, the `results` folder should contain:

- `model_comparison.csv`
- `final_conclusion.txt`
- accuracy and loss graphs
- confusion matrices
- classification reports

## Model Performance Comparison

| Model | Accuracy | mAP | Training Time | Parameters |
|---|---:|---:|---:|---:|
| ResNet50 | TBD | TBD | TBD | TBD |
| DenseNet121 | TBD | TBD | TBD | TBD |
| MobileNetV3Small | TBD | TBD | TBD | TBD |

The final values will be filled in after running the Colab notebook.

## Showing Graphs On GitHub

To make the notebook preview show graphs on GitHub:

1. Open the notebook in Google Colab.
2. Enable GPU runtime.
3. Run the notebook from top to bottom.
4. Make sure the final section, **Graph Results Preview For GitHub**, displays the graphs.
5. In Colab, save the executed notebook back to GitHub:

```text
File > Save a copy in GitHub
```

After the saved notebook is pushed to GitHub, the notebook preview will show the graph outputs, confusion matrices, and comparison table.

## Project By

Add group member names here.
