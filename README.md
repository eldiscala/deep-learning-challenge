# deep-learning-challenge


I. Introduction
In this analysis, we explore the development, training, and evaluation of a deep neural network model. The model is designed to address the task given by the nonporfit foundation Alphabet Soup and its performance is assessed through various metrics. This report provides insights into the purpose, methodology, and outcomes of the analysis.

II. Purpose of the Analysis
The primary objective of this analysis is to build, train, and evaluate a deep neural network model for binary classification. The model is intended to predict outcomes based on input features, providing valuable insights for Alphabet Soup.  The goal is to find a a tool that can help it select the applicants for funding with the best chance of success in their ventures.  Given the csv with morfe than 34,000 organiztions, a binary classifier was crested that can predict whether applicants will be successful if funded by Alphabet Soup.  By understanding the purpose of the analysis, we can better interpret the results and assess the model's effectiveness.

III. Model Development
A. Model Architecture
The neural network model comprises an input layer followed by three hidden layers and an output layer. The architecture is designed to capture complex relationships within the data.

B. Training Process
The model is trained using a specified number of epochs and a chosen batch size. The training process involves adjusting the model's parameters to minimize the chosen loss function.

C. Evaluation Metrics
Performance metrics such as accuracy and loss are used to assess the model's effectiveness. These metrics provide insights into how well the model generalizes to new, unseen data.

IV. Results
A. Model Summary
The model architecture and parameters are summarized, providing a clear overview of its structure.

B. Training and Validation Performance
The training and validation accuracy and loss curves are analyzed to understand the model's learning behavior over epochs.

C. Evaluation on Test Data
The model is evaluated on a separate test dataset, and key metrics such as accuracy are reported.
The initial model produced a very low accuracy using ReLu so tanh was used to produce more accurate results.  Changing the amount of epochs and batch size did not make much of a difference, but the accuracy reulted in aproximately 72-73%.

VI. Alternative Models
Relu was the original selection of the neural network model, but did not produce accurate results. Additional approaches using this model could be attempted to get closer to 75% accuracy, but this was achieved with tanh with little change.
