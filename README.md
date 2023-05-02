Download Link: https://assignmentchef.com/product/solved-comsw4995-homework3-featuring-enggineering
<br>
<h1>Task 1 Identify Features</h1>

Assemble a dataset consisting of features and target (for example in a dataframe or in two arrays X and y). What features are relevant for the prediction task?

Are there any features that should be excluded because they leak the target information?

Show visualizations or statistics to support your selection.

You are not required to use the description column, but you can try to come up with relevant features using it. Please don’t use bag-of-word approaches for now as we’ll discuss these later in the class.

<h1>Task 2 Preprocessing and Baseline Model</h1>

Create a simple minimum viable model by doing an initial selection of features, doing appropriate preprocessing and cross-validating a linear model. Feel free to exclude features or do simplified preprocessing for this task. As mentioned before, you don’t need to validate the model on the whole dataset.




<h1>Task 3 Feature Engineering</h1>

Create derived features and perform more in-depth preprocessing and data cleaning. Does this improve your model? In particular, think about how to encode categorical variables and whether adding interactions (for example using PolynomialFeatures or manually) might help.

<h1>Task 4 Any model</h1>

Use any regression model we discussed (trees, forests, gradient boosting, SVM) to improve your result. You can (and probably should) change your preprocessing and feature engineering to be suitable for the model. You are not required to try all of these models. Tune parameters as appropriate.




<h1>Task 5 Feature Selections</h1>

Identify features that are important for your best model. Which features are most influential, and which features could be removed without decrease in performance? Does removing irrelevant features make your model better? (This will be discussed in the lecture on 03/04).




<h1>Task 6 An explainable model</h1>

Can you create an “explainable” model that is nearly as good as your best model?

An explainable model should be small enough to be easily inspected – say a linear model with few enough coefficients that you can reasonably look at all of them, or a tree with a small number of leaves etc.