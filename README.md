__Support Vector Machines (SVM) with the Iris Dataset__

__Introduction__

Support Vector Machines (SVM) are a class of statistical learning methods based on the principle of margin maximization (class separation). There are several formulations (linear, kernel versions) which can be applied to separable data (linearly) but also to non-separable data.

__Advantages of SVM:__

•	Very effective in high dimensions.
•	Effective in cases where the dimension of the space is larger than the number of training samples.
•	Require less memory as they do not use all the training samples, but only a part (the support vectors).

__Disadvantages:__

•	Performance can degrade if the number of attributes is much larger than the number of samples.
•	They do not provide probability estimates as these are class discrimination methods.

__Dataset__

The Iris dataset is used in this project. It is a well-known dataset in the machine learning community and is part of the sklearn library. For the purpose of this project, only the first two attributes (sepal length and sepal width) are used for visualization.

__Project Structure__

__1. Loading Data__

The project begins by loading the Iris dataset and selecting only the first two attributes (sepal length and sepal width) for simplicity. The dataset is then split into training and test sets.
__2. Training a Linear SVM__

A linear SVM model is trained on the training data. The regularization parameter C is used to control the trade-off between achieving a low error on the training data and minimizing the norm of the weights.

__3. Visualizing the Decision Surface__

The decision surface learned by the model is visualized to understand how well the SVM separates the data. The visualization includes both the decision boundary and the training/testing points.

__Exploration Tasks__

1.	Model Performance Evaluation: Evaluate the performance of the model by calculating the score of well-classified samples on the test dataset.
2.	Parameter Tuning: Experiment with different values for the parameter C. Analyze how the decision boundary evolves as a function of C. Based on the visualization, evaluate the appropriateness of this model for the problem and suggest possible improvements.
3.	Multi-Attribute Optimization: Perform the optimization of a new linear support vector machine using all four attributes of the Iris dataset. Analyze whether the test classification score has increased and provide reasoning.
4.	Digits Data Classification: Use the Digits dataset to build a Linear SVC classifier and evaluate its performance. If training time is extensive, consider using a smaller subset of the data (e.g., 10000 samples). Identify the value of C that yields the best generalization results.
5.	Gaussian Kernel Application: Redo the classification of the Iris dataset using a Gaussian kernel. Test the effects of the kernel scaling parameter (gamma) and the regularization parameter C. Compare the results with those of the linear SVM.
   
__Useful References__

•	NumPy Documentation
•	SciPy Documentation
•	Matplotlib Documentation
•	scikit-learn Documentation
•	Python Programming Language
![image](https://github.com/user-attachments/assets/f47ddf53-ea1c-43cd-9654-d449111dce20)

