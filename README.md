# ClassifyIris
The purpose of this project was to gain introductory exposure to Machine Learning Classification concepts along with data visualization using the ```Iris flower dataset```. 

This dataset is a multivariate data set introduced by Ronald Fisher which is available at https://archive.ics.uci.edu/ml/datasets/iris. It consists the following information for 150 iris species flowering plants samples:

1) sepal length (in cm)
2) sepal width (in cm)
3) petal length (in cm)
4) petal width (in cm)
5) class: Iris Setosa, Iris Versicolour, Iris Virginica


Through ```iris_classifier.ipynb``` we compared different classification algorithms namely ```K-Nearest Neighbours```, ```Decision Tree```, ```Support Vector Machine``` and ```Linear Regression``` for their accuracy to predict the class of the iris flowers. After comparison we find that ```Decision Tree classification algorithm``` is the best classifier. 

Finally we train this best model using the complete dataset and use it as a web-application hosted on ```Heroku``` to predict the class of the iris flowers as Iris Setosa (or) Iris Versicolour (or) Iris Virginica given its attribute information namely the sepal length, sepal width, petal length and petal width values in centimeter.<br><br>

Thus, this project can be used in two ways:

1) As a  ```Heroku``` deployed web-application based on ```Decision Tree``` trained on ```Iris flower dataset```:- https://iris-classsifier.herokuapp.com/

2) Or, by fine-tuning current final model and exploring other options in ```iris_classifier.ipynb``` file located at Google Drive:- https://drive.google.com/file/d/1_988PXug6vy9q9ELjK_Rq52O_crzf4iy/view?usp=sharing 

