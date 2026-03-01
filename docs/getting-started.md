# Getting Started

This guide will help you set up your environment and begin the learning journey.

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd ml-dl
```

### 2. Create Virtual Environment (Recommended)

```bash
# Using venv
python -m venv .venv
.venv\Scripts\activate  # Windows
# source .venv/bin/activate  # Linux/Mac

# Or using conda
conda create -n ml-dl python=3.10
conda activate ml-dl
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Verify Installation

```bash
python -c "import numpy, pandas, sklearn, torch; print('All packages installed!')"
```

## Running Notebooks

### Option 1: Jupyter Notebook

```bash
jupyter notebook
```

### Option 2: VS Code

1. Install VS Code
2. Install Python extension
3. Open the `.ipynb` file and select your kernel

### Option 3: Google Colab

Upload notebooks to Google Colab for free GPU access.

## Recommended Learning Path

| Order | Module                  | Estimated Time |
| :---- | :---------------------- | :------------- |
| 1     | Module 1: Basic ML      | 4-6 hours      |
| 2     | Module 2: Advanced ML   | 4-6 hours      |
| 3     | Module 3: Deep Learning | 6-8 hours      |
| 4     | Module 4: CV & NLP      | 8-10 hours     |
| 5     | Module 5: LLMs          | 10-12 hours    |

## Hardware Requirements

| Module | CPU | RAM  | GPU                  |
| :----- | :-- | :--- | :------------------- |
| 1-2    | ✓   | 8GB  | Optional             |
| 3      | ✓   | 16GB | Recommended          |
| 4-5    | ✓   | 16GB | Strongly Recommended |

## Troubleshooting

### Common Issues

1. **Import errors**: Ensure all packages from `requirements.txt` are installed
2. **Out of memory**: Reduce batch size in deep learning notebooks
3. **Missing data**: Datasets are included in the `data/` folder

See [Troubleshooting Guide](troubleshooting.md) for more details.
