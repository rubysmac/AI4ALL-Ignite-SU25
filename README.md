# Navigate Vocational Student Well-being

Built a machine learning pipeline to classify vocational college students’ mental health status using demographic, behavioral data and self-reflection, all under the guidance of AI4ALL Ignite program's intructors and mentor.
Applied NLP, supervised learning models, and explainable AI techniques to help with early intervenetion of mental health problems.

- [Slides](https://docs.google.com/presentation/d/1-6Dz0SPcrJ-Ekz8U1AxIo8pPlRRZSJIvjUXRBCVCq5k/edit?slide=id.g375aa85c003_0_1#slide=id.g375aa85c003_0_1)
- [Poster](https://docs.google.com/presentation/d/18nT5MbeGxRJGluTwZgDCDmvRhgSUs7RnrTnwp9XM6BI/edit?usp=sharing)


## Problem Statement <!--- do not change this line -->

Vocational students often face unique pressures and challenges, yet their mental health remains under-researched. While prior work has focused on clinical or general student populations, this project addresses the gap by exploring how structured behavioral data and unstructured text reflections can jointly inform mental health status prediction.

Student well-being has major implications for academic success, dropout prevention, and long-term employability. Given post-pandemic concerns and limited counseling resources, scalable early-warning systems using machine learning could support institutions in identifying students in need and intervening earlier.

## Key Results <!--- do not change this line -->

1. Created a labeled dataset with structured features (e.g., GPA, Sleep_Hours) and emotion vectors extracted from self-reported reflections.

2. Engineered and evaluated multiple supervised learning models (e.g., Random Forest, XGBoost, Logistic Regression) for multi-class classification (Healthy, At risk, Struggling).

3. Achieved 68% accuracy score with the best-performing model.
4. Used feature importance analysis to identify key predictive features — GPA, anticipation, sadness, negative, Sleeping_Hours, Steps_Per_Day, etc. — that strongly influenced mental health status.

## Methodologies <!--- do not change this line -->

To address our research question, we combined structured and unstructured data inputs:

- Applied NLP to free-text reflections using NRCLex for emotion extraction.
- Used LabelEncoder to convert categorical into numeric labels
- After converting textual and categorical data into numerical, used StandardScaler to normalize all numerical features
- Trained and fine-tuned supervised models (Random Forest, XGBoost, Logistic Regression) using multi-class classification techniques.
- Validated models using k-fold cross-validation and selected the best model based on metrics like F1 and AUC.
- Interpreted feature importance for transparency and ethical accountability.

## Data Sources <!--- do not change this line -->

Kaggle Datasets: [Link to Kaggle Dataset](https://www.kaggle.com/datasets/ziya07/student-mental-health-and-resilience-dataset)

## Technologies Used <!--- do not change this line -->

- Programming language: Python
- Data handling & processing:
  - pandas – data wrangling and manipulation
  - numpy – numerical operations
  - LabelEncoder – categorical feature encoding
  - StandardScaler – feature normalization
  - joblib – model serialization/saving
- Machine Learning models:
  - scikit-learn – model training, evaluation, preprocessing
  - XGBoost – advanced gradient boosting classifier
- Natural Language Processing
  - NLTK / NRCLex – text preprocessing and emotion detection
- Visualization & Interpretation
  - matplotlib / seaborn – data visualization
  - SHAP – explainable AI (feature importance interpretation)

## How to Navigate <!--- do not change this line -->

mental_health_dataset.csv --> mental_health_eda.ipynb --> data_prep.ipynb --> df_with_emotions.csv
--> LogisticRegression.ipynb or RandomForest.ipynb or XGBoost.ipynb

## Authors <!--- do not change this line -->

Our dedicated team:

- Aysha Mujeeb (aysha.mujeeb@sjsu.edu) | ([LinkedIn](https://www.linkedin.com/in/aysha-mujeeb-13b0b6379))
- Jade Pham ([pham224n@mtholyoke.edu](mailto:pham224n@mtholyoke.edu)) | ([LinkedIn](https://www.linkedin.com/in/jade-pham-0689192a5/))
- Ruby Hong ([rhong08@smith.edu](mailto:rhong08@smith.edu)) | ([LinkedIn](https://www.linkedin.com/in/ruby-hong-639143326/))
