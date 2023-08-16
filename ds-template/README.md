# Project

# Develop

1. Start VS Code
2. Open `ds-template`
3. Run the Dev Containers: Open Folder in Container... command from the Command Palette or Quick Actions Status Bar
4. Select the `Dockerfile.dev` file
5. Wait until the development container is running
6. Look here for more information on [Data Version Control (DVC)](https://dvc.org/doc)
7. Have fun developing!

# Structure

```
├── README.md <- The top-level README for developers using this project.
│
├── .dvc <- Data version control
│
├── data
│ ├── interim <- Intermediate data that has been transformed.
│ ├── processed <- The final, canonical data sets for modeling.
│ └── raw <- The original, immutable data dump.
│
├── models <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks <- Jupyter notebooks. Naming convention is a number (for ordering),
│ the creator's initials, and a short `-` delimited description, e.g.
│ `1.0-mg-initial-data-exploration`.
│
├── requirements.txt <- The requirements file for reproducing the analysis environment.
│
├── src <- Source code for use in this project.
│ ├── **init**.py <- Makes src a Python module
│ │
│ ├── data <- Scripts to download or clean data
│ │ └── generate_dataset.py
│ │
│ ├── features <- Scripts to turn data into features for modeling
│ │ └── generate_features.py
│ │
│ ├── models <- Scripts to train and evaluate models
│ │ ├── train_models.py
│ │ └── evaluate_models.py
│ │
│ └── visualization <- Scripts to create exploratory and results oriented visualizations
│ │ └── generate_visualizations.py
```
