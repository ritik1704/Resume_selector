# Resume Classification Project

## Overview
This project focuses on classifying resumes based on the type of text they contain. The approach utilizes **Natural Language Processing (NLP)** techniques, including text preprocessing and the **TF-IDF** method for vectorization. Several machine learning models, including **K-Nearest Neighbors (KNN)**, **Random Forest**, and **One-vs-Rest**, were trained and evaluated. The goal is to select the best-performing model for accurately classifying resumes into predefined categories. The final model is used to predict the category of new resumes effectively.

## Project Structure

### 1. Data Preprocessing and Feature Engineering
- **Text Preprocessing**:
  - Tokenization: Breaking down resumes into words.
  - Stopword Removal: Removing common words (e.g., 'the', 'is') to focus on meaningful content.
  - Lemmatization: Reducing words to their base form (e.g., 'running' → 'run').
- **Vectorization**:
  - The **TF-IDF** approach was used to convert the text data into numerical vectors for input into machine learning models.
  - Feature extraction includes identifying key words that differentiate resume categories.

### 2. Model Building and Evaluation
- **Machine Learning Models**:
  - **KNN (K-Nearest Neighbors)**: A simple yet effective classification algorithm based on proximity to other points.
  - **Random Forest**: An ensemble method that builds multiple decision trees and aggregates their results.
  - **One-vs-Rest**: A multiclass classification strategy where a binary classifier is trained for each class.
- **Model Evaluation**:
  - The models were evaluated using performance metrics like **Accuracy**, **Precision**, **Recall**, and **F1-Score**.
  - Cross-validation was performed to ensure robust model evaluation.

### 3. Model Selection
- **Best Model**: After evaluation, the best-performing model was selected based on the accuracy and efficiency of classifying resumes.

## Dataset
The dataset used in this project consists of resumes categorized by job type or industry. The dataset is used to train machine learning models to classify resumes based on their content. It is ideal for understanding the relationship between textual features and resume classification.

## Dependencies Installation
To run the project locally, install the necessary dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
## Running the Project Locally

### Steps to Execute

1. **Preprocessing and Feature Engineering**
   - Open the `resume-selector.ipynb` file using Jupyter Notebook or Anaconda.
   - Run all cells sequentially to:
     - Perform text preprocessing.
     - Vectorize the resume text using TF-IDF.

2. **Model Building and Evaluation**
   - Follow the steps in the notebook to:
     - Train the machine learning models.
     - Evaluate the performance of each model using various metrics.
     - Select the best-performing model for classification.

3. **Resume Classification**
   - After training the model, use it to classify new resumes by providing them as input to the trained classifier.

## Contact

For any questions or feedback, please contact Ritik Suri at [Ritik1704@gmail.com](mailto:Ritik1704@gmail.com).
