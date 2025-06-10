# Fake News Detection

This project uses machine learning techniques to classify news articles as **fake** or **real**.
It leverages natural language processing (NLP) to extract features from the text and applies classification algorithms to make predictions.

## Project Structure

* `Fake News Detection.ipynb`: Main Jupyter notebook containing data preprocessing, feature extraction, model training, and evaluation steps.

## Features

* Text preprocessing (stopword removal, stemming)
* TF-IDF vectorization
* Logistic Regression classifier
* Model accuracy evaluation
* Confusion matrix and classification report

## Dataset

The dataset used contains labeled news articles, each marked as **real** or **fake**. Common fields include:

* `title`: Headline of the news article
* `text`: Full content of the news article
* `label`: Ground truth (1 for fake, 0 for real)

## Requirements

Install the following Python libraries:

```bash
pip install pandas numpy sklearn matplotlib nltk
```

Also download the required NLTK resources:

```python
import nltk
nltk.download('stopwords')
```

## Usage

1. Clone this repository.
2. Open `Fake News Detection.ipynb` in Jupyter Notebook.
3. Run each cell in order to:

   * Preprocess the data
   * Vectorize the text
   * Train the model
   * Evaluate its performance

## Model Performance

The model achieves high accuracy on the validation data and provides detailed classification metrics like precision, recall, and F1-score.

## Assumptions

* The dataset is clean and contains no null values in important fields.
* Only English text is processed.
* The labels are correctly assigned.




