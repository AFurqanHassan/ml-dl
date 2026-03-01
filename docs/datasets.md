# Dataset Guide

This guide documents the datasets included in this repository.

## Included Datasets

### 1. Flowers-102

**Location:** `data/flowers-102/`

**Description:** Image classification dataset containing 102 flower categories.

| Split      | Count     |
| :--------- | :-------- |
| Training   | 1,020     |
| Validation | 1,020     |
| Testing    | 6,149     |
| **Total**  | **8,189** |

**Used in:**

- [Module 4: Transfer Learning with ResNet](../module_4_cv_nlp/transfer_learning_flowers.ipynb)

**Format:**

- JPEG images (500x500 pixels typical)
- Labels in `imagelabels.mat`
- Split IDs in `setid.mat`

### 2. EuroSAT

**Location:** `3_deep_learning/data/eurosat/`

**Description:** Sentinel-2 satellite imagery for land cover classification.

| Class                | Description           |
| :------------------- | :-------------------- |
| AnnualCrop           | Annual crops          |
| Forest               | Forests               |
| HerbaceousVegetation | Grasslands            |
| Highway              | Roads/highways        |
| Industrial           | Industrial buildings  |
| Pasture              | Pastures              |
| PermanentCrop        | Permanent crops       |
| Residential          | Residential buildings |
| River                | Rivers                |
| SeaLake              | Lakes/seas            |

**Used in:**

- [Module 2: Land Cover Classification](../2_advanced_ml/land_cover_classification.ipynb)
- [Module 3: EuroSAT CNN](../3_deep_learning/eurosat_cnn.ipynb)

**Format:**

- JPEG images (64x64 pixels)
- Multi-spectral (13 bands in original, RGB in this subset)

## External Datasets (Downloaded Automatically)

The following datasets are downloaded by notebooks when needed:

| Dataset            | Source  | Used In                       |
| :----------------- | :------ | :---------------------------- |
| California Housing | sklearn | Module 1: Linear Regression   |
| Titanic            | seaborn | Module 1: Logistic Regression |

## Data Preprocessing

Notebooks handle preprocessing automatically:

- Image resizing and normalization
- Train/val/test splitting
- Label encoding
- Data augmentation (in deep learning modules)

## Storage

```
data/
├── flowers-102/
│   ├── 102flowers.tgz      # Original archive
│   ├── imagelabels.mat      # Labels
│   ├── setid.mat            # Split IDs
│   └── jpg/                 # Extracted images (~660MB)

3_deep_learning/data/
└── eurosat/
    └── EuroSAT.zip          # (~85MB compressed)
```

## Notes

- All datasets are included in the repository for offline use
- If datasets are missing, re-run the notebooks - they may need to extract archives
- Git LFS recommended for version controlling large data files
