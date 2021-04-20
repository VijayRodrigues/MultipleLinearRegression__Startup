# MultipleLinearRegression__Startup


## Description

This project consists of a startup datasets where we are comparing the given profit with the predicted profit. It has 4 features and one being a categorical feature.
The categorical feature is encoded to contain dummy values and then the dataset is split accordingly.



## Installation

The following libraries have been used:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline

import warnings
warnings.filterwarnings('ignore')

```

For the purpose of encoding categorical data, the following packages are used:

```python
from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder
```

## Tools Used

Jupyter Notebook


## Result

The predicted output is then concatenated with the existing profit for comparison.  

![MultipleLinearRegression_udemy](https://user-images.githubusercontent.com/72039550/115437675-19328700-a22a-11eb-8d85-6222c65b72fc.jpg)

