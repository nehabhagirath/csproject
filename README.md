# Breast Cancer detection using Python and a CNN algorithm

This repository contains a Jupyter Notebook (`breast_cancer_detection_cnn.ipynb`) with a Python implementation of a Convolutional Neural Network (CNN) used for Breast Cancer detection. 

The code is structured as follows:
1. Importation of necessary libraries and configuration of the Seaborn aesthetic parameters.
2. Load and explore the breast cancer dataset from `sklearn.datasets`.
3. Split the dataset into training and testing sets.
4. Normalize features using `StandardScaler` from `sklearn.preprocessing`.
5. Reshape data to fit CNN input requirements.
6. Create and summarize the CNN model.
7. Compile and train the CNN model.
8. Evaluate model performance and plot the results.

## Installation

Before running the notebook, please ensure you have the following Python libraries installed. If not, you can use the provided commands to install them:

```
pip install tensorflow
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install sklearn
pip install keras
```

## How to Run

To run the notebook, you need to have Jupyter Notebook installed. If you haven't installed it yet, you can do so with the following command:

```
pip install jupyter
```

Once Jupyter is installed, you can start it in your terminal with the command `jupyter notebook`. This will open a new tab in your web browser where you can navigate to the `breast_cancer_detection_cnn.ipynb` file and open it. 

To run the cells in the notebook, you can click on a cell and hit 'Shift+Enter'. This will run the current cell and select the one below. 'Ctrl+Enter' runs the selected cells and keeps selection on the current cell. You can also use the "Run" button in the toolbar at the top of the notebook.

## Expected Results

The code should run without errors and provide a variety of outputs at different stages. After the model training, it will plot Accuracy and Loss curves to visualize the model's learning progress during the training phase. 

Next, it will output a table that includes various metrics such as precision, recall, and F1-score for each class (malignant and benign), as well as the overall accuracy. 

It will also output the AUC-ROC score and a confusion matrix to provide a more in-depth view of the model's performance, including the numbers of True Positives, True Negatives, False Positives, and False Negatives. A heatmap representing this confusion matrix will also be displayed. 

By the end of the script, you should have a thorough understanding of the model's performance and its potential utility in the task of breast cancer detection.
