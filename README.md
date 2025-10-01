# Fake-news-detector

## 1. Project Overview

This project is to make a machine learning model that can predict if a news article is fake or real. This task will be done with a multinomial naive bayes classifier and an embedding-based model like a BERT model from Huggine Faces. The models will be optimized and compared to determine which model is best for this task.
---

## 2. Dataset

* **Source:** Fake News Classification
* **Platform:** Kaggle
* **Link:** [Dataset](https://www.kaggle.com/datasets/aadyasingh55/fake-news-classification/data)
* **License:** MIT License
* **Description:** 

---

## 3. Methodology
1.  **Exploratory Data Analysis (EDA):**
    * Analyzed features and checked for missing values
    * Investigate features

2. **Preprocessing**
   * Lemmatization and stop word removal
   * Tokenize all datasets
   * Clean data

3. **Create and train models**
   * Creating copies of data
   * Naive Bayes Classifier
   * Hugging Faces BERT model

4. **Evaluate model differences**
   * Compare the output of models
   * Determine best model type
   * Consider trade-offs
---

## 4. Repository Structure
```
├── data/
│   └── evaluation.csv
│   └── test (1).csv
│   └── train (2).csv      
├── EDA.ipynb             
├── requirements.txt
└── README.md
```
---

## 5. Setup & Usage
Python 12.8

**Instructions:**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AlexBrakas/Fake-news-detector
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the training script:**
    * Place your Kaggle CSV files inside a `data/` directory.
    * Update the file path in scripts.
    * Run the `main.py` script from the root directory:
    ```bash
    python main.py
    ```

---

## 6. Results
TBD

---

## 7. Future Work

Fine tune hyper parameters