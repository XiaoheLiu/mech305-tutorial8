# Q & A Session, Python Demo

Updated on Thursday Mar 26

Leave a message in the chat box if you have questions, and I will answer them! :)

1. I have more than two features / I have important categorical features, so I cannot do "gscatter" or plot the decision boundary! What do I do?
    - It is totoally ok not to do the gscatter or plot the decision boundary. It is not always possible to make visualizations. In the Car_Advertisement project, we were only lucky to have a simple enough problem that we can do all the visualizations. For more complicated problems, you have to rely on the cv_errors to compare acorss ML models.

2. What do I do with missing data?
    - If you have a lot of examples, you can delete the rows with missing data. 
    - If you have a limited number of data, you can consider replace the missing data with the median or the mean value of that column of data.

3. Why every time I run my code, I get a slightly different model?
    - (a) Train-test split is a random process. Every time you may get a slightly different training set.
    - (b) Some ML algorithms have a random initialtion process, which may lead to a slightly different model. (eg. decision tree)
    
4. Is it true that generally if we increase the number of features considered in our model the the accuracy should improve?
    - Not always. If the feature is correlated with the target, it will improve the accuracy to include it in your ML model. But if the feature is not very correlated with the target (eg. "Gender" v.s. "Purchased" in the tutorial project), the extra feature will only confuse your ML model and it is better to drop it.
    
5. In Python Notebook, how can I inspect the variables like in MATLAB "Workspace"?
    - Checkout this extension: [https://github.com/lckr/jupyterlab-variableInspector] (Thank you, Thomas)

