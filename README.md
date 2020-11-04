# DecisionTreeModel

##### decision trees use a very natural decision-making process: asking a series of questions in a nested if-then-else structure
##### A decision tree uses a tree-like model to make predictions. It resembles an upside-down tree. It is also very similar to how you make decisions in real life: you ask a series of questions to arrive at a decision.
##### A decision tree splits the data into multiple sets. Then, each of these sets is further split into subsets to arrive at a decision

##### predicting Income of a given population

In this lab, we will build a decision tree to predict the income of a given population, which is labelled as <= 50𝐾𝑎𝑛𝑑> 50K. The attributes (predictors) are age, working class type, marital status, gender, race etc.

In the following sections, we'll:

- clean and prepare the data,
- build a decision tree with default hyperparameters,
- understand all the hyperparameters that we can tune, and finally
- choose the optimal hyperparameters using grid search cross-validation.

##### predicting a patient has heart disease or not
- In the heart disease example, the leaf nodes (bottom) are labelled yes (the person has heart disease) or no (the person doesn’t have heart disease).
- The decision tree predicts that if, ‘Thal’ is not equal to 3, ‘coloured fluoroscopy’ is less than 0.5, ‘exercise.angina’ is equal to 0, and ‘age’ is less than 51, then the - --person will have heart disease (the path indicated by the red line in the figure). Similarly, there are three other paths which lead to a yes labelled leaf.
