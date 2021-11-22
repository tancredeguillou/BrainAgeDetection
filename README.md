# Overview

Predicting the age of a brain from MRI features.
Magnetic Resonance Imaging (MRI) is a medical imaging technic used in radiology to form pictures of the anatomy and the physiological processes of the body.
More information can be found [here](https://en.wikipedia.org/wiki/Magnetic_resonance_imaging).

# Data description

The data for this task contains the following files:

- `X_train.csv` - the training features
- `y_train.csv` - the training targets
- `X_test.csv` - the test features (you need to make predictions for these samples)
- `sample.csv` - a sample submission file in the correct format

Each row in X_train.csv is one sample indexed by an id, so the first column contains the id. In addition to the id column, each sample has 832 features:
```
id,x0,x1,...,x831
0,10.8,832442.8,...,103088.6
...
```

The test set file (X_test.csv) has the same structure.
The training targets (age in years) are contained in y_train.csv:
```
id,y
0,71
1,73
2,66
...
```

