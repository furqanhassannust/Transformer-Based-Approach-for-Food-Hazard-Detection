# 🥗 Food Hazard Classification using BERT & Deep Learning

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![BERT](https://img.shields.io/badge/Model-BERT%20Fine--tuned-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-70%25%2B-green)

## 📌 Project Overview
Food safety is a critical pillar of public health. This project leverages **BERT (Bidirectional Encoder Representations from Transformers)** and deep learning architectures to classify food hazard data into **4 main categories**, each containing **10+ specific labels**. 

By applying state-of-the-art NLP, this system automates the identification of potential risks in text-based reports, enabling faster intervention and more robust safety analytics for the food industry.



---

## 🚀 Key Features
* **Multi-Class & Multi-Label Classification:** Identifies complex hazards across 4 primary domains with granular sub-labeling.
* **Semantic Embeddings:** Uses BERT-based embeddings for superior contextual understanding of safety terminology.
* **Hybrid Modeling:** Comparison between a **Fine-tuned BERT** model and **LSTM/RNN** architectures.
* **High Performance:** Achieved **>70% accuracy** across all hazard classes.
* **Visual Analytics:** Comprehensive Matplotlib visualizations for performance metrics and error analysis.

---

## 🛠️ Tech Stack
* **Language:** Python 🐍
* **NLP & Deep Learning:** * Hugging Face Transformers (`bert-base-uncased`)
    * TensorFlow / PyTorch
* **Data Science:** * Pandas & NumPy
    * Scikit-learn
* **Visualization:** * Matplotlib & Seaborn

---

## 📂 Dataset Structure
The model processes text-based hazard reports categorized into:
1.  **Biological** (e.g., Salmonella, Listeria)
2.  **Chemical** (e.g., Pesticide residues, allergens)
3.  **Physical** (e.g., Plastic, metal fragments)
4.  **Other** (e.g., Labeling errors, storage issues)

**Preprocessing Steps:**
* Text normalization (lowercase, punctuation removal).
* BERT-specific tokenization (WordPiece).
* Padding and attention masking for uniform input length.

---

## ⚙️ Workflow

### 1. Data Preprocessing
Standardization of raw text data and generation of BERT-compatible tokens.

### 2. Feature Extraction
Generation of dense semantic embeddings to capture the context of food safety terminology.

### 3. Model Training
We compared three distinct approaches:
* **BERT Fine-Tuning:** The primary model, updated specifically for hazard labels.
* **LSTM:** Long Short-Term Memory network used for sequential data dependencies.
* **RNN:** A baseline Recurrent Neural Network for comparison.



### 4. Evaluation
Models were evaluated using Accuracy, F1-Score, and Confusion Matrices to ensure balanced performance across all 40+ possible labels.



---

## 📊 Results
| Model | Accuracy | Strengths |
| :--- | :--- | :--- |
| **Fine-tuned BERT** | **70% +** | Best contextual understanding; handles nuances well. |
| **LSTM** | ~62% | Good at capturing long-term dependencies in text. |
| **RNN** | ~55% | Fast training, but struggles with complex context. |

---

## 💻 Getting Started

**Clone the repository:**
```bash
git clone [https://github.com/your-username/food-hazard-classification.git](https://github.com/your-username/food-hazard-classification.git)
cd food-hazard-classification
