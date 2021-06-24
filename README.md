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

Our balanced accuracy scores were mediocre for the first 5 models, ranging from .55 to .78. Our last model however had a quite high accuracy of 0.93.

### Precision

All of our models yielded a precision level of less than 0.10. In fact, every model had .01 precison other than the Random Forest and AdaBoost models (.03 and .08 respectively). Thus all of our models yield a very high amount of false positives, keeping our precision level very low.

### Recall

All in all, our models had much better recall values than precision, ranging from .57-71 for the first 5 models, and a very repectable .91 for our last model.

### recommendation

If we had to choose one of our models, the clear choice would be the Easy Ensemble AdaBoost Classifier model. The numbers speak for themselves relative to the other models, with a precision over .01, and balanced accuracy score and recall above 0.90.
However, I would not reccomend any of these models to predict credit risk, this is becasue of the very low precision numbers (<0.10). Each model has an enormous amount of false positives, thus a very high percentage of applicants that have low-risk would be classified as high risk.

