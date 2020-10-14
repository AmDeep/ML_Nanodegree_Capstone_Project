# ML_Nanodegree_Capstone_Project
Code, Datasets and Results for AWS Nanodegree Capstone Project on the study of predictive maintenance in a turbofan machine as researched by the NASA Ames Research Center

## Feature Engineering
The engineering features along with the code and description of the individual new columns have been described in the main ipynb file. These features relate to signal processing and fourier transofrms as well as ARIMA decomposed models. Due to the extensive number of signals, the total number of generated features is 279 with the RUL forming the main output to measure. Functions for the signal process modelling and the results for signal tests have been referenced from online sources and self generated code as well.
## Tuning and LSTM
Due to the lower accuracies obtained from both conventional and ensemble regression techniques, the use of CNNs, RNNs and LSTMs was devised as initially described in the proposal. These were compared against a base model and fine tuned for various parameters including activation functions, learning rates, layer density and so on. 
## Controller Tests
Some controller tests were conducted for build MPC controllers but require proprietary software for true exection. Current research and studies are being conducted in the space and the results will be updated when possible.
## Conclusions and Article
The results and sumamrized snippets of the entire project have been linked to a Medium article accessible here.
https://medium.com/@f20140267d/devising-a-predictive-maintenance-model-for-the-study-of-turbofan-engines-a-dive-into-machine-9b7abdc9c21b?source=friends_link&sk=387a67b983e8f75150ded8fd7f39c0d4
## References and code snippets used.
1. Pyimagesearch.
2. Kaggle.
3. MachineLearningMastery.
4. AWS.

