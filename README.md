Fake Detect: A Deep Learning Ensemble Model for Fake News Detection

A machine learning and deep learning project designed to automatically detect and classify fake news using ensemble modeling techniques and Natural Language Processing (NLP).


📌 Project Overview
With the rapid spread of misinformation online, automated text classification is vital. This project implements an ensemble deep learning pipeline that preprocesses text datasets, extracts features, and runs multi-model predictions to determine news authenticity accurately.

Key Features
* Deep Learning & Ensemble Architecture: Combines multiple classifier outputs for robust predictions.
* NLP Processing Pipeline: Tokenization, cleaning, and feature extraction from textual datasets.
* Modular Implementation: Includes standalone Python scripts (`Main.py`) and exploratory Jupyter notebooks (`FakeNewsColabCode.ipynb`).



 🛠️ Tech Stack & Requirements
* Language: Python
* Libraries: TensorFlow / Keras, Scikit-learn, Pandas, NumPy, NLTK
* Environment: Jupyter Notebook / Python Script


📂 Project Structure

fake-news-detection-ensemble/
├── Dataset/              #Raw and processed text datasets
├── model/                #Saved model weights and architecture
├── Main.py               #Main Python script execution file
├── FakeNewsColabCode.ipynb  #Jupyter notebook version of the pipeline
├── requirements.txt     # Python project dependencies
├── run.bat              # Windows batch execution script
└── .gitignore           # Git exclusion configurations

🚀 Setup & Installation
Clone the Repository:
git clone [https://github.com/Varun846237/fake-news-detection-ensemble.git](https://github.com/Varun846237/fake-news-detection-ensemble.git)
cd fake-news-detection-ensemble
Install Dependencies:
pip install -r requirements.txt
Run the Project:
python Main.py
