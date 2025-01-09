# Decision Tree Project

## Overview
This repository showcases the implementation of a custom **Decision Tree** algorithm from scratch in Python. The project demonstrates core machine learning concepts like decision tree construction, splitting, and classification, along with parameter tuning for optimizing accuracy. The repository also includes multiple datasets for evaluation and analysis.

## Features
- Custom implementation of a Decision Tree for classification.
- Parameter tuning to optimize accuracy on different datasets.
- Example notebooks for step-by-step understanding.
- Includes multiple datasets for hands-on experimentation.

## Folder Structure

## Datasets
The `datasets/` folder contains the following files:
- **titanic.csv**: Data for predicting Titanic survival based on passenger features.
- **spam.csv**: Data for classifying messages as spam or not spam.

### Example Data Snippets
#### `titanic.csv`:
| PassengerId | Pclass | Age  | Fare  | Survived |
|-------------|--------|------|-------|----------|
| 1           | 3      | 22.0 | 7.25  | 0        |
| 2           | 1      | 38.0 | 71.28 | 1        |

#### `spam.csv`:
| Feature1 | Feature2 | Feature3 | Label |
|----------|----------|----------|-------|
| 0.12     | 0.34     | 0.56     | 1     |
| 0.98     | 0.76     | 0.45     | 0     |

---

## Example Usage
### Parameters for Titanic Dataset
To achieve **78.78% accuracy**:
```python
params = {
    "max_depth": 5,
    "min_samples_leaf": 40,
    "criterion": "entropy",
}









DecisionTree | 
For titanic to give 78.78% accuracy you should change
the params to :
if __name__ == "__main__":
 #dataset = "titanic"
 dataset = "spam"
 params = {
 "max_depth": 5,
 "min_samples_leaf": 40,
 "criterion": "entropy",
 }
 N = 10
For spam to give 80.20% accuracy you should change the
params to:
if __name__ == "__main__":
 #dataset = "titanic"
 dataset = "spam"
 params = {
 "max_depth": 5,
 "min_samples_leaf": 40,
 "criterion": "entropy",
 }
 N = 20
 


E2EE File Sharing System | Golang : https://gitfront.io/r/fauti/oKjwY9KgsX5P/A-Secure-File-Sharing-System/


Traceroute Implementation | Python : https://gitfront.io/r/fauti/NiiJwJpbmmrC/project2-traceroute-Fatemeh110/


Concurrency Control and Lock Management System | java, Database Systems : https://gitfront.io/r/fauti/hymZXTT1arkK/Concurrency-Lock/
