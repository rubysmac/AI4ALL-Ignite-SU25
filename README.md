# Navigate Vocational Student Well-being

(UPDATE IN README.md)
Built a multimodal machine learning pipeline to classify vocational college students’ mental health status using demographic, behavioral data and self-reflection, all under the guidance of AI4ALL Ignite program's intructors and mentor. 
Applied NLP, supervised learning models, and explainable AI techniques to help with early intervenetion of mental health problems.

## Problem Statement <!--- do not change this line -->

(UPDATE IN README.md)
Vocational students often face unique pressures and challenges, yet their mental health remains under-researched. While prior work has focused on clinical or general student populations, this project addresses the gap by exploring how structured behavioral data and unstructured text reflections can jointly inform mental health status prediction.

Student well-being has major implications for academic success, dropout prevention, and long-term employability. Given post-pandemic concerns and limited counseling resources, scalable early-warning systems using machine learning could support institutions in identifying students in need and intervening earlier.

## Key Results <!--- do not change this line -->

(UPDATE IN README.md)
Enumerate the main results of this project in a list and describe them.

*EXAMPLE:*
1. Created a labeled dataset with structured features (e.g., GPA, Sleep_Hours) and emotion vectors extracted from self-reported reflections.

2. Engineered and evaluated multiple supervised learning models (e.g., Random Forest, XGBoost, Logistic Regression) for multi-class classification (Healthy, At risk, Struggling).

3. Achieved [INSERT METRIC HERE — e.g., accuracy, F1 score] with the best-performing model.

4. Used feature importance analysis to identify key predictive features — [INSERT TOP IMPORTANT FEATURES HERE] — that strongly influenced mental health status.

## Methodologies <!--- do not change this line -->

To address our research question, we combined structured and unstructured data inputs:
- Applied NLP to free-text reflections using NRCLex for emotion extraction.
- Used LabelEncoder to convert categorical into numeric labels
- After converting textual and categorical data into numerical, used StandardScaler to normalize all numerical features
- Trained and fine-tuned supervised models (Random Forest, XGBoost, Logistic Regression) using multi-class classification techniques.
- Validated models using k-fold cross-validation and selected the best model based on metrics like F1 and AUC.
- Interpreted feature importance for transparency and ethical accountability.

## Data Sources <!--- do not change this line -->

(UPDATE IN README.md)
Kaggle Datasets: [Link to Kaggle Dataset](https://www.kaggle.com/datasets/ziya07/student-mental-health-and-resilience-dataset)

## Technologies Used <!--- do not change this line -->

(UPDATE IN README.md)
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


## Authors <!--- do not change this line -->

(UPDATE IN README.md)
Our dedicated team: 
- Aysha Mujeeb
- Jade Pham ([pham224n@mtholyoke.edu](mailto:pham224n@mtholyoke.edu)) | ([LinkedIn](https://www.linkedin.com/in/jade-pham-0689192a5/))
- Ruby Hong
