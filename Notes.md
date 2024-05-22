# Stellar-Data-Classification-Prediction

## Background

In the branches of astronomy, the classification of celestial objects is essential. The ability to collect data samples of stars, galaxies, and quasars is its main advantage. Even though quasars are crucial to a variety of astronomical studies and research, their sample sizes are still in the relative minority group. Significant increases in the sample sizes of quasars and other astronomical objects can only be produced through improved data classification methods, which will then make it possible to advance study. The use of machine learning models in the task of classification has grown more significant and common as contemporary telescopes capture a growing amount of astronomical data due to their precision and speed. 
The classification models of random forest and support vector model (SVM), along with decision tree and Boosting Trees, were used with supervised machine learning models to either exclusively identify and distinguish quasars from other objects or to classify all three of the objects: stars, galaxies, and quasars. Additionally, the fact that numerous supervised classification models were trained using data from kaggle.com shows that the information and variables the dataset supplies are comprehensive, trustworthy, and closely related to the objective of identifying celestial objects. 
 
## Data Description

The data used in this study are from the Sloan Digital Sky Survey (SDSS), which is a famous astronomical survey that has spent more than 20 years attempting to create incredibly accurate and detailed images and a map of the universe. The data represents 100,000 observations of space collected by the SDSS (Sloan Digital Sky Survey). Every observation is defined by 17 feature columns and a class column that categorizes it as a star, galaxy, or quasar. 


## Models

The first model used is Decision Tree. A decision tree model consists of a number of nodes, or conditions, which are joined by branches, or the results of the conditions of the nodes. Each node has two or more branches leading to additional nodes or leaf nodes that begin at the root node (the resulting predictions/classification). The feature variables and their values were used to create the conditions for the nodes in the decision tree, and the Gini index was used to determine where each node should be located. The Gini index measures the heterogeneity/impurity of the data as a result of the separation of the data by the condition, and the smallest value was chosen for each node. Additionally produced were the tree visualization and its confusion matrix. 

The second Model used is Random Forest. This is an algorithm for collective tree- based learning and is the random forest classifier. A collection of decision trees was drawn from a randomly chosen portion of the training set make up the random forest classifier. In order to determine the final class of the test object, it combined the votes from many decision trees. Additionally, the algorithm was conceived as a confusion matrix to help in classification. 

The last model used is Support Vector Machine. SVM is particularly effective in high-dimensional spaces and is used to find a hyperplane that best separates the data into different classes in feature space. Ordinary Linear SVC can only be used to classify two uniwue classes, however in our situation we have 3 classes. Kernel SVM using rbf kernel in particular is adept at multi class classification using the one-to-one approach.



The Three models were fitted to the training data and evaluated using testing sample for a range of performance criteria.When it comes to classifying stars, galaxies and quasars the random forest model developed in this project has a best accuracy, can be used as a competent and reliable classification tool.


