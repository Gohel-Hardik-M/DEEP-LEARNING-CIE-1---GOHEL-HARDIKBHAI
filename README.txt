Project 1 — Sentiment Analysis of Movie Reviews (Bi-LSTM)
===========================================================

HOW TO RUN
----------
1. Keep this folder structure exactly as-is:
     Project1_Sentiment_Analysis/
       Project1_Sentiment_Analysis_IMDB.ipynb
       data/sentiment/reviews.csv
2. Open the .ipynb in Jupyter Notebook / JupyterLab / VS Code / Google Colab
   from INSIDE this folder (so the notebook can see the data/ folder next to it).
3. Run all cells top to bottom (Kernel -> Restart & Run All).
   No internet connection or manual download is needed — the included
   data/sentiment/reviews.csv (1,000 custom-generated movie reviews) is used
   automatically.
4. Two images are saved automatically in this same folder when you run it:
     performance_metrics.png   -> upload as "Performance Metrics Screenshot"
     project_output.png        -> upload as "Project Output / Prediction Screenshot"

REQUIREMENTS
------------
Python 3.9+ with: tensorflow, numpy, pandas, matplotlib, scikit-learn
Install with:  pip install tensorflow numpy pandas matplotlib scikit-learn

SWITCHING TO THE FULL-SIZE DATASET FOR FINAL SUBMISSION
---------------------------------------------------------
This folder ships with a small custom dataset (800 train / 200 test reviews)
so the notebook trains in under a minute for your lab demo. For your real
submission, the notebook already documents how to point CSV_PATH at the full
50,000-review IMDb dataset (links are in the notebook's Dataset Description
section) — the model/training/evaluation code does not need to change.
