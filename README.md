# Penguin Dataset Analysis - Classification 🐧💥

## Dataset Information
The dataset contains measurements for three species of penguins (Adelie, Chinstrap, and Gentoo). The dataset includes various features such as bill length, bill depth, flipper length, and body mass, which can be used to classify the species of the penguins.

*Note:* Ensure the dataset is properly cleaned and prepared for analysis.

*Download Link:* [Penguin Dataset on Kaggle](https://www.kaggle.com/datasets/parulpandey/penguin-dataset)

## Steps:

### Step 1: Import Modules
Import libraries for data manipulation (pandas, numpy), visualization (matplotlib, seaborn), and machine learning (scikit-learn).

### Step 2: Load Dataset and Derive Insights
Load the Penguin dataset.

Display the first few rows to understand the structure.

Get dataset information (data types, null values).

Generate a statistical summary (mean, median, standard deviation).

### Step 3: Preprocess the Dataset (Handling Null Values)
Check for and remove any null values to ensure a clean dataset.

### Step 4: Exploratory Data Analysis (Histogram and Scatter Plot)
Create histograms for feature distribution.

Generate pair plots to visualize relationships between features, categorized by species.

### Step 5: Correlation Matrix (Heat Map)
Compute and visualize the correlation matrix using a heat map to identify relationships between features.

### Step 6: Label Encoder
Convert categorical species labels into numeric form using a label encoder for machine learning compatibility.

### Step 7: Model Training

Split data into features and target, then into training and testing sets.

Train models (Logistic Regression, K-Nearest Neighbors, Decision Tree).

Predict species on test data and evaluate model accuracy.

Compare accuracies to determine the best-performing model.

### Libraries
pandas

matplotlib

seaborn

scikit-learn

### Algorithms
Logistic Regression

Decision Tree

K-Nearest Neighbors
