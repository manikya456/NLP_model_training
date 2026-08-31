# NLP Model Training

Notebook-based sentiment classification experiments on the IMDb movie review dataset.

## Dataset

This project uses the IMDb 50K movie review dataset:

- 50,000 labeled reviews
- binary sentiment labels: `positive` and `negative`
- stored locally in `data/IMDB Dataset.csv`

## What’s Included

- data exploration notebook
- baseline LSTM model
- GloVe-based LSTM and BiLSTM models
- LSTM with dropout
- DistilBERT experiment
- Word2Vec + LSTM experiment
- best-combo comparison notebook

## Setup

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

If you want to run the notebooks, start Jupyter after installing the requirements:

```bash
jupyter notebook
```

## Project Structure

- `notebooks/` - experiment notebooks
- `data/` - dataset and embedding files
- `results/` - evaluation outputs and plots

## Notes

- The repository is focused on experimentation and comparison across multiple NLP models.
- Some generated artifacts are intentionally excluded from version control to keep the repo manageable.
