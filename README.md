# HOSPITAL-HYPOTHYROIDISM-ANALYSIS-AND-PREDICTIONS

## Links to the various tools used 

Dataset - [Source link](http://bit.ly/hypothyroid_data)

Python Notebook - [Notebook]()



## Dataset Description

Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients. Use the healthcare datasets provided to accomplish the following:  

Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.

Within your deliverable you are expected to:

Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.

Part 1: Decision trees:
- For this section, you should build a model that makes the above prediction. You should not use individual decision trees, rather you should use at least 2 out of the 3 advanced models we have studied: Random forests, Ada boosted trees, and gradient boosted trees.
- Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.
- Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction
- Note that with decision trees, you don't need to do a lot of data cleaning. This will be very different with SVM.

Part 2: SVM:

- In this section, you may be required to clean the data a little bit so as to make sense of the features.

- Document what transformation you've done on the data.

- Apply Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best. Remember to tune your parameters to improve the performance of your model. To make your life easier, make sure to visualize the models you've created. Use any two features to build the models for this step.

- After getting your best performing kernel, use this kernel together with your tuned parameters and repeat the prediction but this time using additional features. Compare the model you've just created with the 2-features version. 

#### -- Project Status: [Completed]

## Project Intro/Objective
Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients. Use the healthcare datasets provided to accomplish the following:  

Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroi


### Methods Used
* Descriptive Statistics
* Data Visualization
* Data Analysis
* EDA Analysis
* Machine learning Algorithms
* Kfold cross-validation
* Heteroskdasticity tests
* Decision trees
* Support Vector machine
* Grid search CV
   
### Technologies
* Python
* Pandas,Numpy,Gooogle Colab


```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
```

 * Data Preprocessing Methods used
    *  Boxplots to get rid of outliers in the data
    *  No null/missing values in the dataset 
    *  No duplicates in the dataset
    *  Dropping of unnecessary columns in the dataset
    *  Creating Dummy variabels
    *  Label  Encoding 
    *  Changing of columns 
    
 * Data Analysis used
      * Univariate Analysis 
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
       * Bivariate Analysis
           * scatterplots
       * Multivariate Analysis 
           * Pair plots
  * Modelling
       * Desicision Trees
            * Scaling data
            * Feature Importance
       * Support Vector Machine
            * Modeeling with different kernels (poly, linear and rbf(radial basis function))
            * K-fold cross validation
            * Grid search cv(Hyperparameter tuning)  
   
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Analysis 
- Modelling


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate

## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
