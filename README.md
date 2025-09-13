# Spam Email Classification

A machine learning pipeline for classifying SMS messages as **spam** or **ham** (not spam) using Python, pandas, and scikit-learn in a Jupyter/Colab notebook.

## Dataset

The project uses a labeled SMS text dataset (`spam.csv`) containing:
- `label`: Indicates "ham" (not spam) or "spam"
- `message`: The SMS text

*The dataset is loaded from Google Drive as a zip file. Make sure you have the archive in your Drive, or update the notebook with your dataset path.*

## How to Use

### 1. Open the Notebook

- Upload `Spam_Email.ipynb` to your Google Drive or access directly from this repository.
- Open it in [Google Colab](https://colab.research.google.com/).

### 2. Mount Your Google Drive

### 3. Point to Your Dataset Location

### 4. Run All Cells

- Extracts and loads the CSV.
- Cleans and prepares the data.
- Trains a spam classification model.
- Outputs predictions and notebook results.

### 5. Requirements

*No manual installs needed for Colab.*  
For local use:
- Python 3.x
- pandas
- numpy
- scikit-learn


## Results

- Shows dataset shape and spam/ham distribution.
- Explains preprocessing, modeling, and predictions with code comments and examples.

## Launch in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Pramodhhhh/Spam-Email-Classification/blob/main/Spam_Email.ipynb)


## License

For educational purposes.  
Dataset sourced from [UCI SMS Spam Collection].

---

**References**
- UCI SMS Spam Collection Dataset
- scikit-learn Documentation
- Google Colab Guide



