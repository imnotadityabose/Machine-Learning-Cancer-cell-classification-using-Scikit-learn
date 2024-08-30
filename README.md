Machine Learning is a sub-field of Artificial Intelligence that gives systems the ability to learn themselves without being explicitly programmed to do so.
Machine Learning can be used in solving many real world problems. 
Let’s classify cancer cells based on their features, and identifying them if they are ‘malignant’ or ‘benign’. 
We will be using scikit-learn for a machine learning problem. Scikit-learn is an open-source machine learning, data mining and data analysis library for Python programming language.
The dataset: 
Scikit-learn comes with a few small standard datasets that do not require downloading any file from any external website. 
The dataset that we will be using for our machine learning problem is the Breast cancer wisconsin (diagnostic) dataset.
The dataset includes several data about the breast cancer tumors along with the classifications labels, viz., malignant or benign.


It can be loaded using the following function: 



load_breast_cancer([return_X_y])

The data set has 569 instances or data of 569 tumors and includes data on 30 attributes or features like the radius, texture, perimeter, area, etc. 
of a tumor. We will be using these features to train our model.
Installing the necessary modules: 
For this machine learning project, we will be needing the ‘Scikit-learn’ Python module.
If you don’t have it installed on your machine, download and install it by running the following command in the command prompt: 
 

pip install scikit-learn

Note: You can use any IDE for this project, by it is highly recommended Jupyter notebook for the project. 
This is because, since Python is an interpreted language, so, one can take its full advantage by running a few lines of code and see and understand what’s happening, 
step by step, instead of writing the whole script and once and then running it. 
