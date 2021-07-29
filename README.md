# ClassifyIris
The purpose of this project was to gain introductory exposure to Machine Learning Classification concepts along with data visualization by using Iris Dataset.

The Iris flower data set, also know as the Fisher's Iris data set is a multivariate data set introduced by Ronald Fisher which consists the following information for 150 flowering plants samples,

1) sepal length (in cm)
2) sepal width (in cm)
3) petal length (in cm)
4) petal width (in cm)
5) class: Iris Setosa, Iris Versicolour, Iris Virginica

Using ```iris_classifier.ipynb``` we compared the accuracy of different models (like  K-Nearest Neighbours, Decision Tree, Support Vector Machine and Linear Regression) to find the best classifier. 

| Algorithm               |  Jaccard Similarity Score  |  F1 score  |  Log Loss  |
|-------------------------|----------------------------|------------|------------|
| K Nearest Neighbour     | 0.91                       | 0.91       | NA         |
| Decision Tree           | 0.93                       | 0.93       | NA         |
| Support Vector Machine  | 0.91                       | 0.91       | NA         |
| Logistic Regression     | 0.84                       | 0.83       | 0.84       |

Finally ```Decision Tree classification algorithm```, which is the best model is trained using the complete dataset and deployed as a web-application on ```Heroku```, so that user can predict the class of the iris flowers as Iris Setosa (or) Iris Versicolour (or) Iris Virginica given its attribute information (namely the sepal length, sepal width, petal length and petal width values in centimeter).
<br><br>

## 1) USAGE:

The final trained model is available as a deployed web-application on Heroku at .

Apart from this user can fine-tune current model by improving parameters in ```iris_classifier.ipynb``` file available at . Please open this file as a Google Colaboratory to avoid environment setup.
<br><br><br>
