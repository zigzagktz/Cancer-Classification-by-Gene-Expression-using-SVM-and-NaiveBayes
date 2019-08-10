## Cancer Classification using Gene Expression (SVM and NaiveBayes)

#### 1- Result Comparision after data pre-processing and Model Implementation

Before PCA                                           | After PCA
:--------------------------------------------------------:|:---------------------------------------------------------:
![cross_tab](https://user-images.githubusercontent.com/32847030/62818004-54e8f400-bb0e-11e9-866a-135f2c3c3052.GIF) | ![cross_tab2](https://user-images.githubusercontent.com/32847030/62818005-561a2100-bb0e-11e9-8fc7-d29ea920c29e.GIF)

#### 2- Dimension Reduction (Implementation of PCA)

![snap2](https://user-images.githubusercontent.com/32847030/62817974-c4121880-bb0d-11e9-9c20-b5830d476402.GIF)


### Lower accuracy after PCA needed HyperParameter Tuning in order to regain accuray

![snap](https://user-images.githubusercontent.com/32847030/62818006-59151180-bb0e-11e9-94c3-13f5b95e4750.GIF)

### Here is the results after tuning

![accuracy](https://user-images.githubusercontent.com/32847030/62818007-5aded500-bb0e-11e9-83b8-7a9d54c9190c.gif)

#### Linear Kernal works best for SVM providing 100% accurate results
