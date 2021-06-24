# Credit_Risk_Analysis

## Purpose

The purpose of this analysis is to utilize different machine learning techniques in an attempt to predict credit risk. We will then evaluate how well each technique performed.

## Results

### Technique 1: Random Oversampling
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/11.png)

</p>
<li> Balanced Accuracy Score: .68 </li>
<li> Precision: .01 </li>
<li> Recall: .71 </li>

### Technique 2: SMOTE Oversampling
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/2.png)

</p>
<li> Balanced Accuracy Score: .62 </li>
<li> Precision: .01 </li>
<li> Recall: .57 </li>

### Technique 3: Undersampling
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/3.png)

</p>

<li> Balanced Accuracy Score: .62 </li>
<li> Precision: .01 </li>
<li> Recall: .63 </li>

### Technique 4: Combination Sampling (over/under)
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/4.png)

</p>

<li> Balanced Accuracy Score: .55 </li>
<li> Precision: .01 </li>
<li> Recall: .70 </li>

### Technique 5: Balanced Random Forest
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/5.png)

</p>
<li> Balanced Accuracy Score: .78 </li>
<li> Precision: .03 </li>
<li> Recall: .67 </li>

### Technique 6: Easy Ensemble AdaBoost Classifier
<p align="center"

![alttext](https://github.com/sd2wiebe/Credit_Risk_Analysis/blob/main/6.png)

</p>

<li> Balanced Accuracy Score: .93 </li>
<li> Precision: .08 </li>
<li> Recall: .91 </li>

## Summary:

### Balanced accuracy score



### Precision

All of our models yielded a precision level of less than 0.10. In fact, every model had .01 precison other than the Random Forest and AdaBoost models (.03 and .08 respectively). Thus all of our models yield a very high amount of false positives, keeping our precision level very low.

### Recall

All in all our models had much better recall values than precision, ranging from .57-70 for the first 5 models, and a very good .91 for our last model.
