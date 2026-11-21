# Red-Wine-Quality-Prediction-Using-Machine-Learning
A machine learning project that analyzes the UCI Red Wine Quality dataset to explore wine characteristics, visualize data patterns, and predict wine quality using classification algorithms.

Project Overview

This project focuses on analyzing and predicting the quality of red wine using machine learning techniques. The dataset contains physicochemical properties of red wine, such as acidity, alcohol content, density, sulphates, and other chemical characteristics.

The project uses Python for data analysis, visualization, preprocessing, and machine learning model development.

Dataset

- **Dataset:** Red Wine Quality
- **Source:** UCI Machine Learning Repository
- **File:** `winequality-red.csv`
- **Target Variable:** `quality`

The dataset contains numerical features describing the chemical properties of red wine.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Project Workflow

1. Importing the required Python libraries
2. Loading the dataset
3. Exploring the dataset using basic statistical methods
4. Checking missing values and duplicate records
5. Removing duplicate records
6. Detecting and handling outliers using the IQR method
7. Performing data visualization
8. Separating independent and dependent variables
9. Splitting the dataset into training and testing sets
10. Selecting important features
11. Scaling the features
12. Training machine learning models
13. Evaluating model performance

Data Visualization

The project includes visualizations such as:

- Wine quality distribution
- Alcohol content distribution
- Volatile acidity distribution
- Alcohol content versus wine quality
- Average wine quality by alcohol category
- Correlation heatmap

These visualizations help understand the relationships between wine characteristics and quality.

Machine Learning Algorithms

The notebook includes the following classification algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

The models are evaluated using accuracy, precision, recall, and F1-score.

 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
3. Open the Jupyter Notebook:
4. Open `RedWineQuality.ipynb`.
5. Run the notebook cells in order.

## Conclusion

This project demonstrates the application of data preprocessing, exploratory data analysis, visualization, feature selection, and machine learning classification to the Red Wine Quality dataset.
