# int5

In this project, I explored classification using a Decision Tree Classifier and a Random Forest Classifier. 

## Steps followed
### Training a Decision Tree and Visualizing the Tree
I started by training a Decision Tree Classifier on my dataset. Once trained, I visualized the decision tree to understand how the model was making decisions at different splits. This helped me see the hierarchy of features and how the tree classified observations based on their values.

### Analyzing Overfitting and Controlling Tree Depth
Initially, I noticed that the Decision Tree achieved 100% training accuracy, which signaled overfitting. To address this, I experimented with limiting the tree’s depth. By controlling the max_depth parameter, I reduced overfitting and achieved a better balance between training and testing accuracy. This step helped improve the model’s generalization to unseen data.

### Training a Random Forest and Comparing Accuracy
I then trained a Random Forest Classifier on the same dataset. While the Random Forest also achieved perfect training accuracy. I compared the test accuracy of both models to evaluate which one generalized better.

### Interpreting Feature Importances
After training both models, I examined their feature importances to understand which variables contributed most to the predictions. This allowed me to identify the most influential features in the dataset, providing insights into what factors were driving the model’s decisions.

### Evaluating Using Cross-Validation
Finally, I evaluated both models using cross-validation to ensure their performance wasn’t dependent on a particular train-test split. By computing cross-validation scores, I verified the consistency and stability of the models’ accuracy across different folds, which helped confirm their reliability.


## Conclusion
Through this workflow, I built, visualized, tuned, and validated classification models while gaining insights into the data’s predictive structure. I compared the strengths and weaknesses of Decision Trees and Random Forests, balancing interpretability and accuracy.
