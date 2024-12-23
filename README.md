
# Mushroom Classification: Logistic Regression vs. Deep Neural Network (MLP)  

This repository contains a classification project focused on identifying whether a mushroom is edible or poisonous based on its characteristics. The project uses two machine learning approaches: Logistic Regression and a Multi-Layer Perceptron (MLP).  

## Features  
- **Dataset**: The dataset contains mushroom characteristics (e.g., cap shape, color, odor) encoded as features to classify whether a mushroom is edible or poisonous.  
- **Models**:  
  - Logistic Regression  
  - Multi-Layer Perceptron (Deep Neural Network)  

- **Metrics for Evaluation**:  
  - Confusion Matrix  
  - Accuracy  
  - F1-Score  

## Results  

1. **Logistic Regression Confusion Matrix**:  
   ```
   [[3284 2803]
    [2135 5287]]
   ```  
   - The model struggles to separate classes effectively, leading to a significant number of misclassifications.  

2. **MLP Confusion Matrix**:  
   ```
   [[5933  154]
    [ 115 7307]]
   ```  
   - The deep neural network (MLP) outperforms logistic regression, achieving higher accuracy and significantly fewer misclassifications.  

## Project Workflow  

1. **Data Preprocessing**:  
   - Load and preprocess the mushroom dataset.  
   - Encode categorical features using one-hot encoding or label encoding.  
   - Split the data into training and testing sets.  

2. **Modeling with Logistic Regression**:  
   - Train a logistic regression model on the dataset.  
   - Evaluate the model using the test data.  
   - Generate a confusion matrix and calculate evaluation metrics.  

3. **Modeling with MLP**:  
   - Design and train a deep neural network (MLP) using TensorFlow/Keras.  
   - Evaluate the model on the test data.  
   - Generate a confusion matrix and calculate evaluation metrics.  

4. **Comparison**:  
   - Compare the performance of Logistic Regression and MLP in terms of confusion matrix, accuracy, and F1-Score.  

## Requirements  
- Python 3.8+  
- TensorFlow/Keras for the MLP model  
- Required libraries:  
  ```bash
  pip install numpy pandas scikit-learn matplotlib tensorflow
  ```  

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/SebasKHE/Musroom-Classification-Logistic-Regression-vs-Deep-Netfowk-MLP.git
   ```  
2. Navigate to the directory:  
   ```bash
   cd Musroom-Classification-Logistic-Regression-vs-Deep-Netfowk-MLP
   ```  
3. Run the Jupyter notebook or Python scripts to train and evaluate the models.  

## Visualizations  
- Plot confusion matrices for both models.  
- Display bar charts comparing accuracy and F1-Score between Logistic Regression and MLP.  

## Dataset  
The mushroom dataset used in this project is publicly available.  

