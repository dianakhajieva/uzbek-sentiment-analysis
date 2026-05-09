# Uzbek Sentiment Analysis using XLM-RoBERTa

This project presents sentiment analysis for the Uzbek language using both classical machine learning methods and transformer-based deep learning models.

## Models Used
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest
- XLM-RoBERTa

## Dataset
The project uses Uzbek sentiment datasets containing:
- negative
- neutral
- positive

sentiment labels.

## Transformer Model
The final transformer model was fine-tuned using:
- xlm-roberta-base
- HuggingFace Transformers
- PyTorch

## HuggingFace Model
https://huggingface.co/Dyanne05/xlmr-uzbek-sentiment

## Results
XLM-RoBERTa achieved the best overall performance among all evaluated models.

## Research Paper
The full research paper is available in:
research_paper/paper.pdf

## Visualizations

### Evaluation Metrics
![Evaluation Metrics](figures/evaluation_metrics.png)

### XLM-RoBERTa Confusion Matrix
![XLM-R Confusion Matrix](figures/xlmr_confusion.png)

## Technologies
- Python
- Scikit-learn
- Transformers
- PyTorch
- Pandas
- Matplotlib
