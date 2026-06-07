# Cat Breed Classification Using CNN Transfer Learning

Course: ISB46703 Principle of Artificial Intelligence  
Assessment: Project, 20%

## Project Overview

This project classifies cat breeds using transfer learning with convolutional neural networks. The selected assessment domain is **Animal subspecies**, represented by visually similar domestic cat breeds.

The project compares three convolutional neural network models:

- ResNet50
- DenseNet121
- MobileNetV3

The models will be trained using transfer learning for 50 epochs each. Their performance will be compared using accuracy, mean average precision, training time, model size/parameters, loss and accuracy curves, and confusion matrices.

## Selected Dataset

Dataset source: Oxford-IIIT Pet Dataset  
Official dataset page: https://www.robots.ox.ac.uk/~vgg/data/pets/

The original dataset contains 37 pet breed categories. This project will use a focused subset of 5 cat breeds so the task remains manageable and fits the assessment requirement of 3 to 10 classes.

Selected classes:

- Abyssinian
- Bengal
- Birman
- Bombay
- British Shorthair

These classes are suitable because they are all animal breed/subspecies categories and have enough images for transfer learning experiments.

## Assessment Requirements

The project must include:

- Selected domain: Animal subspecies.
- At least 3 image classes, up to 10 classes.
- Training, validation, and testing dataset splits.
- Three CNN models trained for 50 epochs each.
- Evaluation using accuracy and mAP.
- Training time recorded for each model.
- Graphs for model loss and accuracy.
- Confusion matrix for each model.
- Final comparison and conclusion.

## Suggested Folder Structure

```text
dataset/
  train/
    Abyssinian/
    Bengal/
    Birman/
    Bombay/
    British_Shorthair/
  validation/
    Abyssinian/
    Bengal/
    Birman/
    Bombay/
    British_Shorthair/
  test/
    Abyssinian/
    Bengal/
    Birman/
    Bombay/
    British_Shorthair/

notebooks/
  01_data_preparation.ipynb
  02_resnet50_training.ipynb
  03_densenet121_training.ipynb
  04_mobilenetv3_training.ipynb
  05_model_comparison.ipynb

results/
  graphs/
  confusion_matrices/

models/
docs/
```

## Current Notebooks

These notebooks are designed to run in Google Colab.

Before training the CNN models in Colab, use:

```text
Runtime > Change runtime type > Hardware accelerator > GPU
```

Recommended option:

| Notebook | Open In Colab | Purpose | Status |
|---|---|---|---|
| `notebooks/00_full_cat_breed_project_colab.ipynb` | [Open](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/00_full_cat_breed_project_colab.ipynb) | Complete project in one Colab notebook: data preparation, all three model trainings, evaluation, comparison, and conclusion | Ready |

Separate backup notebooks:

| Notebook | Open In Colab | Purpose | Status |
|---|---|---|---|
| `notebooks/01_data_preparation.ipynb` | [Open](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/01_data_preparation.ipynb) | Download/filter the Oxford-IIIT Pet Dataset, create train/validation/test splits, and visualize the selected cat breeds | Ready |
| `notebooks/02_resnet50_training.ipynb` | [Open](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/02_resnet50_training.ipynb) | Train and evaluate ResNet50 | Ready |
| `notebooks/03_densenet121_training.ipynb` | [Open](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/03_densenet121_training.ipynb) | Train and evaluate DenseNet121 | Ready |
| `notebooks/04_mobilenetv3_training.ipynb` | [Open](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/04_mobilenetv3_training.ipynb) | Train and evaluate MobileNetV3 | Ready |
| `notebooks/05_model_comparison.ipynb` | To be added | Compare all model results and write final conclusion | To do |

See [docs/colab_guide.md](docs/colab_guide.md) for step-by-step Colab instructions.

## Team Roles

| Role | Responsibility |
|---|---|
| Data Engineer | Collect images, standardize data, create dataset splits |
| Data Scientist | Build CNN models, train models, tune hyperparameters |
| Data Analyst | Visualize dataset, evaluate models, compare results |

## Model Comparison Table

| Model | Test Accuracy | mAP | Training Time | Parameters | Notes |
|---|---:|---:|---:|---:|---|
| ResNet50 | TBD | TBD | TBD | TBD | TBD |
| DenseNet121 | TBD | TBD | TBD | TBD | TBD |
| MobileNetV3 | TBD | TBD | TBD | TBD | TBD |

## Final Conclusion

The final conclusion will choose the best model for the classification task by considering:

- Accuracy
- mAP
- Training time
- Number of parameters
- Confusion matrix performance
- Overall suitability for the selected dataset

## Presentation Focus

The 5-minute presentation should explain:

1. Why cat breed classification fits the Animal subspecies domain.
2. How the dataset was prepared and split.
3. How transfer learning was used with ResNet50, DenseNet121, and MobileNetV3.
4. The accuracy, mAP, training time, and confusion matrix results.
5. Which model is the best choice and why.
