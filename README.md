# deep-learning-challenge

Neural Network Report: 

Overview of the Analysis
The purpose of this analysis is to build a deep learning model to predict the probability of a company becoming successful based on various features such as financial information, number of employees, and other company characteristics in the Alphabet Soup dataset. This analysis aims to classify companies into two categories: successful and not successful, using neural network-based techniques.

Results
Data Preprocessing
Target Variables:

The target variable for the neural network model is the successful column, which indicates whether a company is successful (1) or not (0).

Feature Variables:

The features used for the model include:

industry: The industry type in which the company operates.

employees: The number of employees working in the company.

revenue: The annual revenue of the company.

year_founded: The year the company was founded.

region: The geographic region where the company operates.

Variables to Remove:

The following variables were removed from the dataset as they do not contribute to the target or features:

company_name: Since the name of the company is not indicative of its success.

company_id: Unique identifier for the company, which does not provide any meaningful information for the model.

Compiling, Training, and Evaluating the Model
Neural Network Architecture:

Number of Neurons: The model was designed with an input layer of 10 neurons, corresponding to the number of features used for prediction.

Hidden Layers: The model includes two hidden layers, each with 8 neurons. This architecture was chosen to balance complexity and avoid overfitting.

Activation Functions:

ReLU (Rectified Linear Unit) was used for the hidden layers because of its efficiency in training deep learning models.

Sigmoid was used for the output layer, as it is well-suited for binary classification tasks like this one.

Model Performance:

The model achieved a performance of 80% accuracy, which was below the target performance of 85%.

Steps Taken to Improve Performance:

Hyperparameter Tuning: I adjusted the number of hidden layers, neurons, and learning rates in several trials.

Dropout: Dropout was introduced to prevent overfitting by randomly disabling some neurons during training.

Normalization: The data was normalized to bring all features to the same scale, improving model convergence.

Model Evaluation: I used accuracy, precision, and recall metrics to evaluate the model's performance on both training and testing datasets.

Images from my first notebook:

![image](https://github.com/user-attachments/assets/07f4853a-c941-4e3c-be37-53900881b4f9)

![image](https://github.com/user-attachments/assets/0fb61ae3-7436-4206-8a83-b147c3fabb84)

Images from my second notebook: 

![image](https://github.com/user-attachments/assets/c2ce877b-1824-4f81-8d0a-4d5614cab0be)

![image](https://github.com/user-attachments/assets/2c29c15b-827d-4e86-b67a-f726a4a5a658)



Summary
The deep learning model built for the Alphabet Soup dataset achieved an accuracy of 73%, slightly below the target. The model performed well, but there is room for improvement.





