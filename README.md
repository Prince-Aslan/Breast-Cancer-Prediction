# BREAST CANCER PREDICTION
Both notebook contain code and solution of logistic regression for the same dataset; 
The Wisconsin Breast Cancer dataset while using different approach

While Note A took a different approach by not factoring the class inbalance during traning

Note B emphasizes the use of Stratify to ensures that the class distribution in both sets reflects the original dataset's class distribution (y) 
and StandardScaler for normalizing the input variables (X) to a common scale while training the model

Note C majorly looked an improving the models by implementing various techniques


## Brief Explanation of Stratify and StandardScaler Use

## Stratify:
Ensures that the split into training and test sets maintains the same proportion of each class (target variable)
Deals with imbalanced datasets, where some classes have a much larger number of instances than others
Affects the target variable (y)

## StandardScaler:
Normalizes the features (input variables) to have zero mean and unit variance
Scales the data to a common range, reducing the effect of features with large ranges
Affects the input variables (X)

## Summary:
Stratify is about maintaining class balance in the target variable (y)
StandardScaler is about normalizing the input variables (X) to a common scale
You use stratify when you want to ensure that your model is trained and evaluated on a representative sample of each class, 
and you use StandardScaler when you want to normalize your input features to improve the performance of your model.
