# Music-Recommendation-Model
This report aims to develop a recommendation system for the KKBox music streaming service.

# Music-Recommendation-Model

## 1. Objective
This report aims to develop a recommendation system for the KKBox music streaming service.

## 2. Data Description
The dataset is retrieved from [KKBox's Music Recommendation Challenge](https://www.kaggle.com/c/kkbox-music-recommendation-challenge). KKBOX provides a training data set consists of information of the first observable listening event for each unique user-song pair within a specific time duration. Metadata of each unique user and song pair is also provided. The dataset includes:
- **train.csv**: Contains user-song interaction data and target labels indicating recurring listening events.
- **test.csv**: Similar to train.csv but without target labels, used for model testing.
- **sample_submission.csv**: Template for submitting predictions.
- **songs.csv**: Metadata about songs including song length, genre, artist, composer, lyricist, and language.
- **members.csv**: User information such as city, age (bd), gender, registration method, registration date, and expiration date.
- **song_extra_info.csv**: Additional song information including song names and International Standard Recording Code (ISRC).

## 3. Tools
Python was utilized along with essential libraries:
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations and array operations.
- **scikit-learn (sklearn)**: For machine learning algorithms, including Decision Tree, Random Forest, Naive Bayes, Logistic Regression.
- **matplotlib** and **seaborn**: For data visualization.

## 4. Implementation
The project implementation involved the following steps:
1. **Data Cleaning**: Preparing the data by handling missing values, outliers, and incorrect data entries.
2. **Data Transformation**: Transforming the data into suitable formats for analysis.
3. **Feature Engineering**: Creating new features to improve model performance.
4. **Model Building**: Implementing various machine learning models and choose the best model by evaluation metrics.

## 5. Outcome
A prediction model with approximately 69% accuracy.
