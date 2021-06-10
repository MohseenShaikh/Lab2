# Breast Cancer Wisconsin Classification
The goal of this notebook is the application of classification techniques to classify whether the tumor mass is benign or malignant in women residing in the state of Wisconsin, USA. This will help in understanding the important underlaying importance of attributes thereby helping in predicting the stage of breast cancer depending on the values of these attributes.

## Installation

**Installing Python**

Make sure that you have [Python3 installed](https://realpython.com/installing-python/) on your machine.

Depending on your installation you might have access to Python3 interpreter either by
running `python` or `python3`. The same goes for pip package manager - it may be accessible either
by running `pip` or `pip3`.

You may check your Python version by running:

```bash
python --version
```

Note that in this repository whenever you see `python` it will be assumed that it is Python **3**.

**Installing dependencies**

Install all dependencies that are required for the project by running:

```bash
pip install -r requirements.txt
```
Also you might want to install jupyter to access the notebook in the repository.

## Dataset

The dataset is included in the repository with file names *data.csv*
You can also visit the [dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

1) ID number 2) Diagnosis (M = malignant, B = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) b) texture (standard deviation of gray-scale values) c) perimeter d) area e) smoothness (local variation in radius lengths) f) compactness (perimeter^2 / area - 1.0) g) concavity (severity of concave portions of the contour) h) concave points (number of concave portions of the contour) i) symmetry j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant
## Attributes in the dataset

    Predicting if the cancer diagnosis is benign or malignant based on several observations/features

    30 features are used, examples:

      - radius (mean of distances from center to points on the perimeter)
      - texture (standard deviation of gray-scale values)
      - perimeter
      - area
      - smoothness (local variation in radius lengths)
      - compactness (perimeter^2 / area - 1.0)
      - concavity (severity of concave portions of the contour)
      - concave points (number of concave portions of the contour)
      - symmetry 
      - fractal dimension ("coastline approximation" - 1)

    Datasets are linearly separable using all 30 input features
    Number of Instances: 569
    Class Distribution: 212 Malignant, 357 Benign
    Target class: Diagnosis

       - Malignant (M)
       - Benign (B)

## Usage

You would need to clone the repo to access all the contents
```
git clone https://github.com/MohseenShaikh/Lab2.git
```

Install all the dependencies using the environment manager or using the `pip install requirements.txt` command

Access the Lab_2_Breast_Cancer_Wisconsin.ipynb notebook which contains the source code for feature selection and modelling

## Implementation

The dataset was divided into training and testing data with the test size of 20%

We have used Logistic Regression and Random Forest to classify and predict wheter the patient's cancer state

After training the data we have calculted the accuracy for each model and saved the latest model for future use as a `pickel` file named `model.pkl`


# Credits

  - Noopa Jagadeesh 
  - Mohseen Shaikh
  
# License 

  This is released under the MIT License. http://www.opensource.org/licenses/mit-license

# Contribution

Feel free to raise any issue at this repository or please raise pull request to incorporate changes

