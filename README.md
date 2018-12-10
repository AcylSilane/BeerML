# BeerML
James Dean, 2018

Written for a statistics course I took in Fall of 2018. In this repo, you can find various statistical techniques applied to the Brewer's Friend dataset on Kaggle with the overall intent of predicting the alcohol content of a beer given various parameters of the recipe. Investigated methods are:

* OLS (R, initial.r)
* LASSO (R, initial.r)
* Bagged Trees / Random Forests (R, initial.r)
* 2-layer Neural Network (Python, NeuralNet.py)

Overall, we're approximating some known relations which can be found [here](http://www.brewunited.com/abv_calculator.php). In particular, our OLS produces an equation that is remarkably similar to the commonly-used formula of (Original_Gravity - Final_Gravity) * 131.25.
