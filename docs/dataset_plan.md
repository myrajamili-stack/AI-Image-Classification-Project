# Dataset Plan

## Topic

Cat breed classification using the Animal subspecies domain.

## Dataset Source

Oxford-IIIT Pet Dataset  
Official page: https://www.robots.ox.ac.uk/~vgg/data/pets/

The dataset includes cat and dog breed images with breed labels. This project uses only selected cat breed classes.

## Selected Classes

| Class | Label Name For Folders |
|---|---|
| Abyssinian | `Abyssinian` |
| Bengal | `Bengal` |
| Birman | `Birman` |
| Bombay | `Bombay` |
| British Shorthair | `British_Shorthair` |

## Why This Dataset Fits The Brief

- It belongs to the Animal subspecies domain.
- It has more than the minimum 3 classes.
- It has fewer than the maximum 10 selected classes.
- It is suitable for image classification.
- It supports CNN transfer learning experiments.

## Dataset Preparation Tasks

1. Download or access the Oxford-IIIT Pet Dataset.
2. Select only the 5 chosen cat breeds.
3. Check images for corrupted files.
4. Resize images during model training.
5. Split into training, validation, and testing sets.
6. Visualize class distribution.

## Recommended Split

| Split | Percentage | Purpose |
|---|---:|---|
| Training | 70% | Used to train the model |
| Validation | 15% | Used to monitor training performance |
| Testing | 15% | Used for final evaluation |

## Notes

The dataset images should not be committed to GitHub if they make the repository too large. If needed, store the dataset in Google Drive and add the shared dataset link to the main README.

