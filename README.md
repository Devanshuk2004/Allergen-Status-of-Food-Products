# Allergen Status of Food Products Dataset Analysis

## About the Dataset

The **Allergen Status of Food Products** dataset is a valuable resource that provides detailed information on the allergen status of various food products. This dataset is particularly useful for researchers, food manufacturers, healthcare professionals, and individuals with food allergies who need to be informed about potential allergens in food items.

### Dataset Details

- **Size**: The dataset contains 400 records, each representing a specific food product and its associated allergen information.
- **Allergens Covered**: 
  - **Dairy**
  - **Wheat**
  - **Nuts** (Almonds, Peanuts, Pine Nuts)
  - **Seafood** (Anchovies, Fish, Shellfish)
  - **Grains** (Oats, Rice)
  - **Animal-Based Ingredients** (Chicken, Pork)
  - **Plant-Based Ingredients** (Celery, Mustard, Soybeans)
  - **Common Ingredients** (Cocoa, Eggs)
  - Some records also indicate the absence of specific allergens.

### Data Structure

The dataset is structured with nine informative columns:

1. **Food Product**: The name of the food product.
2. **Main Ingredient**: The primary ingredient used in the food product.
3. **Sweetener**: Any sweetening agent present in the product.
4. **Fat/Oil**: The type of fat or oil used in the food product.
5. **Seasoning**: Seasonings or spices used to flavor the dish.
6. **Allergens**: A list of allergens associated with the food item, specifying allergenic ingredients present.
7. **Price ($)**: The price of the food product.
8. **Customer Rating (Out of 5)**: Customer ratings on a scale of 5, reflecting their satisfaction.
9. **Prediction**: A classification indicating whether the food product contains allergens or not.

## Work Done

### Data Preparation

- **Unique Value Analysis**: Identified unique values across different columns to understand the diversity of data.
- **Null Value Handling**: Checked for missing values and filled them appropriately to ensure data completeness.

### Exploratory Data Analysis (EDA)

- **Correlation Matrix & Heatmap**: Analyzed correlations between variables to identify relationships and dependencies.
- **Histogram**: Plotted distributions of key numerical variables, such as price and customer ratings.
- **Boxplot**: Visualized the spread and central tendency of variables, especially focusing on the distribution of customer ratings and prices.

### Machine Learning Models

- **Data Splitting**: Split the dataset into training and testing sets to evaluate model performance.
- Applied the following machine learning models:
  - **Support Vector Classifier (SVC)**
  - **K-Nearest Neighbors (KNN)**
  - **Gaussian Naive Bayes (GaussianNB)**
- Each model was trained and tested to predict whether a food product contains allergens, with the results evaluated to determine the most effective approach.

