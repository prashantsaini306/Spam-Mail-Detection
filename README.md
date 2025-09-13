# Spam-Mail-Detection

**Brief:** A reproducible spam detection project using TF-IDF + Multinomial Naive Bayes.

**Contents**
- `data/mail_data.csv` - dataset (included)
- `src/model.py` - training script (run locally)
- `requirements.txt` - python dependencies
- `artifacts/` - directory where trained model and vectorizer will be saved after running

**Colab**
- Original Colab notebook: https://colab.research.google.com/drive/1A-LQcjX8rwqyTqG57RzU2UcPWF2cyq6-

## How to run (local)
1. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # on Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
2. Run training:
   ```bash
   python src/model.py
   ```
3. After running, check `artifacts/` for `nb_model.joblib` and `tfidf_vectorizer.joblib`.

## If dataset is large
GitHub limits files >100MB. If `data/mail_data.csv` is large, remove it and provide a download link (Google Drive / Kaggle) instead.

## To publish to your GitHub repo
1. Create a new repo on GitHub (https://github.com/new) named `Spam-Mail-Detection`.
2. From this project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - spam detection project"
   git branch -M main
   git remote add origin https://github.com/prashantsaini306/Spam-Mail-Detection.git
   git push -u origin main
   ```
3. Your project will appear on your profile: https://github.com/prashantsaini306

## Notes
- If you want me to prepare a Jupyter notebook version or help craft a better README with results and badges, tell me and I'll add it.