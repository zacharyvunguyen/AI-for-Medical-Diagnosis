# AI for Medical Diagnosis
![](images/screenshots/img.png)-
---
## Handling Class Imbalance and Small Training Sets
### Building and Training a Model for Medical Diagnosis

Building an algorithm to identify whether an X-Ray image has a mass or not <br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 12.58.37 PM.png)
<br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 12.58.52 PM.png)
---
## Train, prediction & loss
Algorithm has many different names:
<br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.05.50 PM.png)
<br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.06.04 PM.png)
<br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.06.43 PM.png)
<br>
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.07.09 PM.png)

---
### Image Classification and Class Imbalance
3 key challenges of image classification:
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.20.19 PM.png)
Class Imbalance:
* In real life, there is not equal samples of normal and disease in the dataset
* There are a lot more examples of normals than of mass, especially if we're looking at X-rays of a healthy population.
* In a medical dataset, you might see 100 times as many normal examples as mass examples.

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.20.48 PM.png)
 ---
### Binary Cross Entropy Loss Function
![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.33.51 PM.png)

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.34.06 PM.png)

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.35.37 PM.png)

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.36.14 PM.png)

---
### Resampling to Achieve Balanced Classes

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.54.25 PM.png)

![](images/screenshots/week 1/Screen Shot 2022-06-29 at 1.54.41 PM.png)

---
### Multi-Task
![](images/screenshots/week 1/img.png)