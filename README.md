# Fake News Detection Project

## Project Overview
In today's fast-paced digital world, the rapid spread of information, both true and false, has become a significant challenge. The dissemination of fake news can have serious negative impacts on society, culture, and public opinion. This project focuses on developing a machine learning model that can accurately identify and classify news articles as either real or fake. By leveraging multiple machine learning techniques, we aim to provide a robust solution for detecting and combating misinformation.

## Objective
The goal of this project is to build and train a machine learning model that can effectively classify news articles into two categories: genuine (true) or fake (false). We utilize a diverse dataset and apply multiple classification algorithms to achieve reliable results.

## Techniques Used
To determine the best-performing model, we have implemented and compared four different machine learning techniques:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Gradient Boosting Classifier**
4. **Random Forest Classifier**

## Dataset
The dataset used in this project consists of labeled news articles, each marked as either true or false. The dataset is divided into two classes:

- **True**: Represents genuine news articles.
- **False**: Represents fake or fabricated news articles.

## System Requirements

### Software:
- **Anaconda**
- **Python**

## Dependencies
Ensure the following libraries and packages are installed before running the code:

- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression

To install the necessary packages, run the following commands:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install seaborn
pip install re
```

## Usage
Follow these steps to run the project:

1. **Clone the repository** to your local machine:

   ```bash
   git clone https://github.com/kapilsinghnegi/Fake-News-Detection.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd fake-news-detection
   ```

3. **Run the Python scripts** associated with each classifier to train and test the models. For instance, to execute the Random Forest Classifier:

   ```bash
   python random_forest_classifier.py
   ```

4. **View the results**, including evaluation metrics like accuracy, precision, recall, and F1 score. The output will indicate whether the news article is classified as true or false based on the model's predictions.

## Results
Each classifier's performance was rigorously evaluated using standard metrics such as accuracy, precision, recall, and F1 score. Detailed results and comparisons of the models are available in the project documentation.

## Model Deployment
After evaluating the performance of the classifiers, you can choose the most effective one for deployment. The selected model can be integrated into a real-world application or incorporated into a larger system for automatic fake news detection.
