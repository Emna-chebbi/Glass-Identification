# Glass-Identification Dataset

This project aims to classify the type of glass based on its optical and chemical properties. 
The goal is to identify which type of glass it is, using a Random Forest classifier.

## Dataset Overview

The dataset consists of 214 data points, with no separate test set provided. The features in the dataset are:

- **Refractive index (RI)**: An optical property of the glass.
- **Chemical elements** (measured in weight percent):
  - Sodium (Na)
  - Magnesium (Mg)
  - Aluminium (Al)
  - Silicon (Si)
  - Potassium (K)
  - Calcium (Ca)
  - Barium (Ba)
  - Iron (Fe)

The target variable is the **type of glass**, which is represented by numbers from 1 to 7.

### Key Points:
- **Number of Data Points**: 214
- **Features**: Refractive index and chemical composition (Na, Mg, Al, Si, K, Ca, Ba, Fe)
- **Target**: Type of glass
- **Model Used**: Random Forest classifier
- **Data Split**: Train-test split (no separate test set in the original dataset)

## Objective

The objective of this project is to predict the glass type based on its refractive index and chemical composition using a **Random Forest classifier**. 
The dataset is split into training and testing subsets using the `train_test_split` method from scikit-learn.

## Model Performance

After training the Random Forest model, I evaluated the model's performance using a classification report. The report shows the precision, recall, and F1-score for each class (glass type). This gives an insight into how well the model performs for each glass type.
