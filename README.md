# 🎵 Music Genre Classifier

Music Genre Classifier is a machine learning project that classifies
audio files into different music genres using extracted audio features
and supervised learning models.

This project focuses on feature extraction from audio signals and
training classification models to predict genre labels accurately.

------------------------------------------------------------------------

## 📌 Project Overview

The system processes audio files and extracts meaningful features such
as:

-   Tempo
-   Rhythm patterns
-   Spectral energy
-   Frequency-based characteristics

These features are then used to train machine learning models for genre
classification.

------------------------------------------------------------------------

## 🧠 Methodology

### 1️⃣ Audio Feature Extraction

Audio files are processed using Librosa to extract relevant features
such as tempo, spectral properties, and rhythm-related metrics.

### 2️⃣ Data Preparation

-   Features are stored using NumPy arrays.
-   Hash maps are used to map genre labels to numerical values.
-   Data is organized into structured format for model training.

### 3️⃣ Model Training

Two models were implemented using Scikit-learn:

-   Random Forest Classifier
-   K-Nearest Neighbors (KNN)

The models were trained on extracted audio features to classify music
into predefined genres.

### 4️⃣ Evaluation

Model performance was evaluated using classification metrics such as
accuracy on test data.

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Python\
-   Scikit-learn\
-   Librosa\
-   NumPy\
-   Pandas

------------------------------------------------------------------------

## 📂 Project Structure

    Music_Genre_Classifier/
    │
    ├── Music_Genre_Classifier.ipynb
    ├── LICENSE
    ├── README.md
    └── .gitignore

------------------------------------------------------------------------

## ▶ How to Run

1.  Install dependencies:

``` bash
pip install -r requirements.txt
```

2.  Place dataset in the `data/` folder.

3.  Run the notebook:

``` bash
jupyter notebook
```

------------------------------------------------------------------------

## ⚠ Kaggle API Setup (Important)

This project requires downloading datasets from Kaggle.

### How to Configure Kaggle API

1.  Download `kaggle.json` from your Kaggle account.
2.  Create a `.kaggle` folder in your home directory.
3.  Move the file:

``` bash
mkdir ~/.kaggle
mv kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
```

------------------------------------------------------------------------

## 🎯 Project Objective

-   Apply machine learning techniques to audio classification.
-   Perform structured feature extraction from raw audio signals.
-   Compare classification performance across different models.
-   Organize data efficiently for scalable ML workflows.

------------------------------------------------------------------------

## 📎 Notes

-   This project is built for educational and experimentation purposes.
-   No deployment or production API integration is implemented.

------------------------------------------------------------------------

## 👤 Author

Sarth Kaushik\
IIT Delhi
