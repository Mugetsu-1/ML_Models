# Finance_Cyberbully_MLMdel

Combined repository containing two analysis notebooks and their associated data and output images.

## Project structure

- Cyberbully/
  - cyberbullying_classifier.ipynb  — notebook for training/evaluating a cyberbullying tweet classifier
  - cyberbullying_tweets.csv        — dataset of tweets used by the notebook
  - model_comparison.png, confusion_matrices.png, target_distribution.png, wordclouds.png — generated visualizations

- Finance/
  - financial_sentiment_baseline.ipynb — notebook exploring a simple financial sentiment baseline
  - data.csv                             — dataset used by the finance notebook

## Quick start

1. Install Python 3.8+ and create a virtual environment:
   python -m venv .venv
   .\.venv\Scripts\activate  (Windows)

2. Install common dependencies used by the notebooks (adjust as needed):
   pip install jupyter pandas numpy scikit-learn matplotlib seaborn wordcloud nltk

3. Launch Jupyter and open the notebooks:
   jupyter notebook  # or `jupyter lab`

4. Run the notebooks top-to-bottom to reproduce analyses and regenerate the images in each folder.

## Data

Data files are included in the repository (see Cyberbully/cyberbullying_tweets.csv and Finance/data.csv). If you need larger or newer datasets, update the notebook data paths accordingly.

## Notes

- Notebooks produce visual artifacts (PNG files) that are included; if regenerating them, they will be overwritten.
- The repository does not currently include a requirements.txt; consider exporting one after installing packages (`pip freeze > requirements.txt`).

## Contact

For questions about the analyses or to request changes, open an issue or contact the repository owner.
