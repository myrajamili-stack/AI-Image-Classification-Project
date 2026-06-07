# Project Plan

## 1. Choose Domain

Selected domain from the assessment brief:

- Animal subspecies

Project topic:

- Cat breed classification using CNN transfer learning

Selected dataset:

- Oxford-IIIT Pet Dataset
- Official source: https://www.robots.ox.ac.uk/~vgg/data/pets/

Selected classes:

- Abyssinian
- Bengal
- Birman
- Bombay
- British Shorthair

## 2. Prepare Dataset

- Download or access the Oxford-IIIT Pet Dataset.
- Filter the dataset to the selected 5 cat breeds.
- Standardize image format and size.
- Remove corrupted or duplicate images.
- Split into training, validation, and testing folders.
- Visualize class distribution.

Recommended split:

- 70% training
- 15% validation
- 15% testing

## 3. Train Models

Train these Keras CNN models using transfer learning:

- ResNet50
- DenseNet121
- MobileNetV3

Each model should be trained for 50 epochs.

Training approach:

- Load each pretrained CNN with ImageNet weights.
- Freeze the base model first.
- Add a custom classification head for 5 classes.
- Train for 50 epochs.
- Optionally fine-tune selected top layers if time allows.
- Record training time.

## 4. Evaluate Models

For each model, record:

- Accuracy
- Mean average precision
- Training time
- Number of parameters
- Loss graph
- Accuracy graph
- Confusion matrix

## 5. Compare And Conclude

Compare the three models and decide which one is best for the classification task.

The conclusion should consider performance and efficiency, not accuracy alone.

Final comparison should discuss:

- Which model achieved the highest test accuracy.
- Which model achieved the highest mAP.
- Which model trained fastest.
- Which model has fewer parameters.
- Which breeds were most often confused.
- Which model is most suitable for cat breed classification.

