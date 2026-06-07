# Google Colab Guide

This project can be completed in Google Colab.

## 1. Open The Notebook

Use the direct Colab links in the main `README.md`, or open a notebook manually:

1. Go to https://colab.research.google.com/
2. Choose the `GitHub` tab.
3. Paste this repository URL:

```text
https://github.com/myrajamili-stack/AI-Image-Classification-Project
```

4. Select the notebook you want to run.

## 2. Use GPU For Training

For model training notebooks, enable GPU:

```text
Runtime > Change runtime type > Hardware accelerator > GPU
```

Use GPU for:

- `02_resnet50_training.ipynb`
- `03_densenet121_training.ipynb`
- `04_mobilenetv3_training.ipynb`

The data preparation notebook can run without GPU.

## 3. Recommended Running Order

Recommended single-notebook option:

1. `00_full_cat_breed_project_colab.ipynb`

This is the safest option because the dataset preparation, model training, evaluation, and comparison happen in the same Colab runtime.

Backup separate-notebook option:

Run the notebooks in this order:

1. `01_data_preparation.ipynb`
2. `02_resnet50_training.ipynb`
3. `03_densenet121_training.ipynb`
4. `04_mobilenetv3_training.ipynb`
5. `05_model_comparison.ipynb`

## 4. Saving Work

Colab sessions reset, so save important output files.

Recommended options:

- Mount Google Drive in each notebook.
- Save the `dataset`, `results`, and `models` folders to Google Drive.
- Download final graphs and result CSV/JSON files.
- Upload final notebooks and result files back to GitHub.

## 5. Important Note About Dataset And Models

Do not upload very large datasets or model files directly to GitHub if they exceed GitHub limits.

Instead:

- Store the dataset in Google Drive.
- Store large `.keras` model files in Google Drive.
- Add the shared Google Drive links to the project README.

## 6. What To Submit

For the VLE submission, submit the GitHub link:

```text
https://github.com/myrajamili-stack/AI-Image-Classification-Project
```

Make sure the repository includes:

- Completed notebooks
- Result graphs
- Confusion matrices
- Model comparison table
- Final conclusion
- Dataset link, if dataset is stored outside GitHub
