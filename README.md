# wine-tree
The goal of this task was to classify wine samples from the provided wine dataset. This task involved loading the dataset, splitting it into training and testing sets, training a decision tree using the ‘entropy’ criterion, and visualising the resulting tree. 

### Logic of Implementation
1.	Loading the data<br>
_The dataset is loaded using the ‘load_wine’ function._
2.	Converting the dataset to a Pandas DataFrame<br>
_The dataset is then converted to a Pandas DataFrame for efficient analysis._
3.	Splitting the data<br>
_The dataset is split into training and testing sets to ensure the model can be trained on one subset and tested on another._
4.	Initialising the classifier<br>
_Classifier is initialised with the ‘entropy’ criterion which measures the information gain at each split of the tree._
5.	Training the classifier<br>
_Classifier is trained using ‘fit’ method._
6.	Visualising the tree<br>
_The trained tree is visualised using ‘plot_tree’ and includes feature and class names. The tree is then saved as a pdf file._ 
7.	Evaluating the model<br>
_The accuracy of the model is computed by comparing the predictions against the true labels._
