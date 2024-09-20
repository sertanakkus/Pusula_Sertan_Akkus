Name: Sertan <br>
Surname: Akkuş <br>
E-mail: sertanakkus.sa@gmail.com

# Drug Side Effects Analysis

## Project Overview

This project focuses on an in-depth analysis of drug side effects using a dataset containing 18 categorical variables related to various drug types, user demographics, and reported side effects. The goal is to perform exploratory data analysis (EDA) and preprocessing to uncover patterns, correlations, and trends within the dataset.

The analysis is implemented in a Jupyter Notebook, where various techniques are used to clean, visualize, and process the data, including:

- Handling missing values
- Encoding categorical variables
- Visualizing relationships between features and side effects
- Correlation analysis

## Requirements

To run this analysis, you will need the following:

- **Python 3.x**
- **Jupyter Notebook** or **Jupyter Lab**
- Required Python libraries, which can be installed by running the following:
  ```bash
  pip install -r requirements.txt
  ```

### Required Libraries

The notebook uses the following libraries:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `scikit-learn` for data preprocessing

## Dataset

The dataset used in this analysis contains **18 categorical variables** related to drug use and side effects. The dataset includes the following key features:

- **Gender**: The gender of the user.
- **Date of Birth**: The date of birth of the user.
- **Nationality**: The nationality of the user.
- **City**: The city where the user lives.
- **Drug Name**: The name of the drug.
- **Drug Start Date**: The date the user started taking the drug.
- **Drug End Date**: The date the user stopped using the drug.
- **Side Effects**: Categorical variables representing the type and severity of side effects reported.
- **Side Effect Reporting Date**: The date the user reported using drug.
- **Allergies**: Allergies the user have.
- **Chronic Diseases**: Chronic diseases the user have.
- **Blood Types**: The blood type of the user.
- **Weight**: The weight of the user.
- **Height**: The height of the user.

## How to Run the Code

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sertanakkus/Pusula_Sertan_Akkus.git
   cd Pusula_Sertan_Akkus
   ```

2. **Install the dependencies**:
   Install all required libraries from the `requirements.txt` file.

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**:
   Start the Jupyter Notebook server and open the notebook:

   ```bash
   jupyter notebook
   ```

   Navigate to the `drug_side_effects_analysis.ipynb` file and open it.

4. **Run the notebook cells**:
   Execute the cells sequentially to perform the data analysis.

### Exploratory Data Analysis (EDA)

The notebook performs various EDA tasks, including:

- Visualizing numerical variables with a box plot to detect outliers.
- Visualizing the distribution of side effects across different drug types.
- Analyzing the frequency of side effects by age group and gender.
- Investigating correlations between side effect, allergy, blood type, gender and age group.
- Identifying trends and patterns in the data using statistical methods and visualizations.

### Data Preprocessing Steps

The notebook includes the following data preprocessing steps:

- **Missing Data Handling**: Checking missing data and applying various strategies to impute missing values.
- **Encoding Categorical Variables**: Converting categorical variables to numerical formats using techniques such as one-hot encoding or label encoding.
- **Normalization/Standardization**: Scaling the numerical features where appropriate.

## Results and Findings

The key findings and visualizations are presented throughout the notebook. This analysis highlights:

- The most common side effects reported for different drug classes.
- Trends in side effect frequency by demographic factors such as age and gender.
- Potential correlations between drug usage patterns and specific side effects.

## Future Work

- **Predictive Modeling**: Build predictive models to forecast potential side effects based on user characteristics and drug type.
- **Clustering**: Apply clustering techniques to group similar drugs based on side effects or user demographics.
- **Time Series Analysis**: Explore time-related patterns in drug usage and side effects, such as seasonality or trends over time.
