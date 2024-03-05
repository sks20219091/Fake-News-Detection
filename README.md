# Fake News Detection using Machine Learning

## Overview
This repository contains a Python project for detecting fake news using machine learning techniques. The project utilizes a combination of data preprocessing, text vectorization, and various machine learning models to classify news articles as either fake or true.

## Project Structure
- **Data:** Two CSV files, `Fake.csv` and `True.csv`, containing fake and true news articles.
- **Code:** The main code file is `fake_news_detection.py`. It includes data loading, cleaning, preprocessing, model training, and manual testing.
- **Libraries:** Required libraries are specified in the `requirements.txt` file.

## Instructions
1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Code:**
   ```bash
   python fake_news_detection.py
   ```

3. **Manual Testing:**
   Input a news article when prompted for manual testing.

## Libraries Used
- **Pandas and NumPy:** For data manipulation and analysis.
- **Seaborn and Matplotlib:** For data visualization.
- **Scikit-learn (sklearn):** For machine learning tools and metrics.
- **Re and String:** For text preprocessing.

## Models Trained
- **Logistic Regression**
- **Decision Tree**
- **Gradient Boosting**
- **Random Forest**

## Performance Evaluation
The project includes evaluation metrics such as accuracy, precision, recall, and F1-score for each trained model. The user can observe the performance of different models on the provided dataset.

## Enhancements and Alternatives
- Consider reducing the number of estimators in Gradient Boosting to speed up training.
- Experiment with subsampling to reduce the size of the dataset used for each tree.
- Explore alternative gradient boosting frameworks like LightGBM or XGBoost, known for faster training times.
- Utilize parallelization by setting the `n_jobs` parameter in the models.

## License
This project is licensed under the [MIT License](LICENSE.md).

Feel free to contribute, report issues, or suggest improvements!
