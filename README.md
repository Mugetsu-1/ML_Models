# NLP Text Classification Notebooks

Recommended repository name: `nlp-text-classification-notebooks`

This repository contains two independent notebook-based NLP classification projects:

| Area | Notebook | Dataset | Models / Outputs |
| --- | --- | --- | --- |
| Finance | `Finance/financial_sentiment_baseline.ipynb` | `Finance/data.csv` | TF-IDF + Logistic Regression baseline for sentence-level sentiment |
| Online safety | `Cyberbully/cyberbullying_classifier.ipynb` | `Cyberbully/cyberbullying_tweets.csv` | TF-IDF + Multinomial Naive Bayes and Random Forest, plus saved charts |

## Repository layout

| Path | Purpose |
| --- | --- |
| `Finance/financial_sentiment_baseline.ipynb` | Finance sentiment baseline notebook |
| `Finance/data.csv` | Finance sentiment dataset with `Sentence` and `Sentiment` columns |
| `Cyberbully/cyberbullying_classifier.ipynb` | Cyberbullying detection notebook with EDA, preprocessing, training, and evaluation |
| `Cyberbully/cyberbullying_tweets.csv` | Cyberbullying tweet dataset with class labels |
| `Cyberbully/*.png` | Generated visualizations from the cyberbullying notebook |

## Quick start

1. Create and activate a virtual environment.

```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

2. Install the project dependencies.

```powershell
pip install -r requirements.txt
```

3. Launch Jupyter.

```powershell
jupyter lab
```

4. Open each notebook from its project folder and run it top-to-bottom.

## Current project notes

- The cyberbullying notebook is the more complete and better-documented workflow in the repository. It includes EDA, cleaning, model comparison, and saved plots.
- The finance notebook now targets `Finance/data.csv` directly so it no longer picks up the cyberbullying dataset by mistake.
- `requirements.txt` is included to make local setup easier, though you may still want to pin exact package versions for stricter reproducibility.

## Suggested cleanup

- Re-run the finance notebook to regenerate outputs after code changes.
- Add a short results section with screenshots or key metrics for each project.
- If you plan to publish this as a portfolio repo, consider renaming the repository to `nlp-text-classification-notebooks`.
