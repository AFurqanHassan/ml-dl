# ML to LLMs: A Modular Learning Journey (with Geospatial Focus)

Welcome to your hands-on learning path from Machine Learning basics to Large Language Models, with a special emphasis on **Geospatial Data Analysis**. This repository contains modular units designed to take you from a beginner to an advanced practitioner.

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone <repository-url>
cd ml-dl

# 2. Create virtual environment
python -m venv .venv

# 3. Activate environment
.venv\Scripts\activate     # Windows
# source .venv/bin/activate  # Linux/Mac

# 4. Install dependencies
pip install -r requirements.txt

# 5. Start learning!
jupyter notebook
```

---

## 📋 Prerequisites

| Requirement | Details                                               |
| :---------- | :---------------------------------------------------- |
| **Python**  | 3.8 or higher                                         |
| **RAM**     | 8GB minimum (16GB recommended)                        |
| **Storage** | ~2GB for datasets                                     |
| **GPU**     | Optional for Modules 1-2, Recommended for Modules 3-5 |

---

## 📚 Curriculum Overview

### [Module 1: Basic Machine Learning](./1_basic_ml/)

- **Concepts:** Linear Regression, Logistic Regression, Data Preprocessing, Spatial Joins.
- **Hands-on:** California Housing prices (Spatial), Titanic survival, Geospatial Basics.

### [Module 2: Advanced Machine Learning](./2_advanced_ml/)

- **Concepts:** Ensemble Methods (Random Forest, XGBoost), Feature Engineering (Spectral Indices), Model Optimization.
- **Hands-on:** Land Cover Classification using multi-spectral satellite imagery.

### [Module 3: Deep Learning Foundations](./3_deep_learning/)

- **Concepts:** Neural Networks, Backpropagation, Optimizers (Adam, SGD), PyTorch basics.
- **Hands-on:** Land Use classification using the EuroSAT dataset (Satellite Imagery).

### [Module 4: Computer Vision & NLP](./4_cv_nlp/)

- **Concepts:** CNNs, RNNs, LSTMs, Attention Mechanisms, Transformers, YOLO.
- **Hands-on:** Image classification (Flowers-102 Transfer Learning), Sentiment analysis with geospatial visualization, Object detection (YOLOv8).

### [Module 5: LLMs & Generative AI](./5_llms/)

- **Concepts:** LLM Foundations, Tokenization, Prompt Engineering, RAG, Fine-tuning (LoRA/QLoRA), Context Management.
- **Hands-on:** Local LLM inference (Ollama & HuggingFace), Prompt engineering techniques, RAG from scratch, Fine-tuning with LoRA, Building a chatbot with memory.

---

## 🗂️ Included Datasets

| Dataset     | Location                        | Description                           |
| :---------- | :------------------------------ | :------------------------------------ |
| Flowers-102 | `data/flowers-102/`             | 102 flower categories (~8,000 images) |
| EuroSAT     | `3_deep_learning/data/eurosat/` | 10 land cover classes from satellite  |

> **Note:** Datasets are included in the repository. No download required!

---

## 💻 Recommended Learning Path

| Order | Module   | Topics                                   | Est. Time |
| :---- | :------- | :--------------------------------------- | :-------- |
| 1     | Module 1 | Linear/Logistic Regression, EDA          | 4-6 hrs   |
| 2     | Module 2 | Random Forest, XGBoost, Spectral Indices | 4-6 hrs   |
| 3     | Module 3 | Neural Networks, CNN, PyTorch            | 6-8 hrs   |
| 4     | Module 4 | Transformers, YOLO, NLP                  | 8-10 hrs  |
| 5     | Module 5 | LLMs, RAG, LoRA, Ollama                  | 10-12 hrs |

---

## 📖 Detailed Documentation

For more information, see the [docs/](docs/) folder:

- [Getting Started Guide](docs/getting-started.md) - Detailed installation instructions
- [Dataset Guide](docs/datasets.md) - Information about included datasets
- [Troubleshooting](docs/troubleshooting.md) - Common issues and solutions

---

## 🛠️ Hardware Requirements by Module

| Module | CPU | RAM  | GPU                  |
| :----- | :-- | :--- | :------------------- |
| 1-2    | ✅  | 8GB  | Optional             |
| 3      | ✅  | 16GB | Recommended          |
| 4-5    | ✅  | 16GB | Strongly Recommended |

---

## 🤝 Contributing

This is a learning resource. Feedback and improvements are welcome!

---

_Learning path from ML fundamentals to LLMs with geospatial applications._
