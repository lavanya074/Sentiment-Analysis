# Sentiment Analysis

A Natural Language Processing project that performs sentiment analysis on product reviews using both rule-based and transformer-based approaches.

This project compares the performance of VADER sentiment scoring and a RoBERTa transformer model to classify reviews as positive, neutral, or negative.

## Project Description

This project analyzes customer reviews and identifies the sentiment behind each review. It uses two different sentiment analysis techniques:

1. **VADER Sentiment Analysis**
   - A rule-based sentiment analysis model from NLTK.
   - It gives negative, neutral, positive, and compound sentiment scores.

2. **RoBERTa Transformer Model**
   - A pretrained transformer model used for sequence classification.
   - It understands context better than traditional bag-of-words models.

The project also includes data cleaning, exploratory data analysis, sentiment score comparison, and visualization of results.

## Features

- Load and analyze review dataset
- Perform text tokenization
- Apply Part-of-Speech tagging
- Perform Named Entity Recognition
- Use VADER for rule-based sentiment scoring
- Use RoBERTa for transformer-based sentiment classification
- Compare sentiment scores between models
- Visualize sentiment distribution using Matplotlib and Seaborn
- Analyze positive and negative review examples

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Hugging Face Transformers
- PyTorch
- SciPy
- tqdm

## Dataset

The project uses a review dataset file named:

```text
Reviews.csv.zip
```

# Project Structure
Sentiment-Analysis/
│
├── Sentiment Analysis (1).ipynb
└── README.md

# Installation
Clone the repository:
git clone https://github.com/lavanya074/Sentiment-Analysis.git
Navigate to the project folder:
cd Sentiment-Analysis
Install the required libraries:
pip install pandas numpy matplotlib seaborn nltk transformers torch scipy tqdm jupyter
Start Jupyter Notebook:
jupyter notebook
Open the notebook:
Sentiment Analysis (1).ipynb

# How to Run
Download or place the dataset file Reviews.csv.zip in your project folder.
Open the Jupyter Notebook.
Update the dataset path if required.


Author
Lavanya

License
This project is open-source and available for learning and development purposes.
