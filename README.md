<!-- Overview of the analysis: Explain the purpose of this analysis. -->
## Overview

The purpose of this project is to utilize and optimize neural network model.

---

<!-- Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance? -->
## Results

* Variable IS_SUCCESSFUL is considered the target of the model.

* Variables EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT are considered the features for the model.

* Variables that are neither targets nor features, and should therefore be removed from the input data, have not been identified.

* 8 neurons, 2 hidden layers, and activation functions ReLU and Sigmoid are selected for the model to increase accuracy of prediction.

* I was not able to achieve the target model performance of 75% accuracy.

* In order to increase model performance, I increase the number of nodes to 1000, 800, and 500. I also used a total of 3 hidden layers and pruned the feature USE_CASE.

---

<!-- Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation. -->
## Summary

Overall the attempts at optimization of model performance result in loss of 0.5806 and accuracy of 0.7266. One recommendation for solving this classification problem is to further prune the features that do not correlate with target which will hopefully train the model better.