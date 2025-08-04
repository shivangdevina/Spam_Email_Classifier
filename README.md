# Spam Email Classifier

This repository provides a simple and effective machine learning solution to classify emails as spam or not spam ("ham"). The implementation is done using Jupyter Notebook, making it easy to understand and experiment with.

## Folder Structure

```
Spam_Email_Classifier/
├── Spam_Email_Classifier.ipynb   # Main Jupyter Notebook with all code, explanations, and results
├── spam.csv                      # Dataset containing email texts and labels (spam/ham)
└── README.md                     # Project documentation (this file)
```

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python (>=3.6 recommended)
- Jupyter Notebook/Colab
- Required Python packages (see below)

You can install the main dependencies using:
```bash
pip install pandas scikit-learn matplotlib nltk
```

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/shivangdevina/Spam_Email_Classifier.git
    cd Spam_Email_Classifier
    ```

2. **Open Jupyter Notebook:**
    ```bash
    jupyter notebook Spam_Email_Classifier.ipynb
    ```

    or open with google colab.

3. **Run the notebook cells:**
    - The notebook will guide you through data loading, preprocessing, feature extraction, model training, and evaluation.
    - You can modify the code or try other classifiers as you wish.

## Dataset

- **spam.csv**: This file contains the labeled email messages. Each row includes the text of an email and its label (spam/ham).

## Features

- Data cleaning and preprocessing
- Exploratory data analysis and visualization
- Feature extraction using NLP techniques
- Training and evaluation of machine learning models
- Final predictions and performance metrics
