# BeerML
James Dean, 2018

Written for a statistics course I took in Fall of 2018. In this repo, you can find various statistical techniques applied to the Brewer's Friend dataset on Kaggle with the overall intent of predicting the alcohol content of a beer given various parameters of the recipe. Investigated methods are:

* OLS (R, Linreg.ipynb)
* LASSO (R, Linreg.ipynb)
* KNN (R, Linreg.ipynb)
* Bagged Trees / Random Forests (R, Trees.ipynb)
* 2-layer Neural Network (Python, NeuralNet.ipynb)
* Kriging (R, Kriging.ipynb)

I've included the Jupyter notebook files for these methods. Source code can be found within them.

Overall, we're approximating some known relations which can be found [here](http://www.brewunited.com/abv_calculator.php). In particular, our OLS produces an equation that is remarkably similar to the commonly-used formula of (Original_Gravity - Final_Gravity) * 131.25.
