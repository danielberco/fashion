# Fashion-Mnist
### Fashion-Mnist is a data classification problem that used by 60,000 images of clothing. Each image is a 28x28 grayscale image, that labeld by 10 clothing classes.
### In this project, i took the train and test files from kaggle.com/zalando-research/fashionmnist/ . You can see the whole process of the machine learning and the models evaluation on the jupyter notebook.
## Labels:

Each training and test example is assigned to one of the following labels:

0 T-shirt/top

1 Trouser

2 Pullover

3 Dress

4 Coat

5 Sandal

6 Shirt

7 Sneaker

8 Bag

9 Ankle boot

#### After setting the labels and adjusting the data, i started to split the data to train and test models and i used PCA before to see the diffrences between the models.

| Model        | Before PCA     | After PCA  |
| ------------- |:-------------:| -----:|
| KNN      | 85% | 86% |
| Decision Tree      | 79% | 77% |
|Naive Bayes      |60%| 77% |
| Logistic Regression     | 85% | 83%|
| Random Forest     | 87% | 86% |

