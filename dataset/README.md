# Dataset

This project uses the Oxford-IIIT Pet Dataset and focuses on 5 cat breeds:

- Abyssinian
- Bengal
- Birman
- Bombay
- British Shorthair

Official dataset page:

https://www.robots.ox.ac.uk/~vgg/data/pets/

Organize the filtered dataset into three splits:

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
```

Use the same class names in `train`, `validation`, and `test`.

Recommended split:

- 70% training
- 15% validation
- 15% testing

If the dataset is too large for GitHub, upload it to Google Drive, Kaggle, or another storage platform and place the dataset link in the main `README.md`.
