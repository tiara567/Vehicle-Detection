# Vehicle Vs. Non-Vehicle Classification

## Intoduction to Machine Learning

Machine Learning (ML) is a part of Artificial Intelligence (AI). It provides a machine "intelligence" to act more and more like humans. The smarter ML is, the more it helps us as humans to accomplish our goals. It can achieve the narrow AI (machines or robot that performs humans' specific task e.g. classify an image, recognize a voice, detect fraud, etc.) through a system or model that can find a pattern from data and learn from it to predict the upcoming input. ML itself divides into four main types. There are:

**1. Supervised Learning.** 
The ML model learns from labeled data. It has two branches. There are **classification** and **regression**.

**2. Unsupervised Learning.**
The ML model learns to find the pattern from unlabelled data, group them, and then label them to give a recommendation. Two examples of this ML model type are **dimension reduction* and **clustering**. 

**3. Transfer Learning.**
This type of ML model uses the existed ML model then adapts and modifies it to meet the current need. For example, person A has an ML model that classifies types of car, then person B borrows it to classify the types of truck. Person B does not need to program the ML from scratch. He only needs to transfer the "ML model's intelligence/knowledge" and re-train it using the new dataset.

**4. Reinforcement Learning.** 
The ML model learns based on a trial and error training process, where the model learns moves that leads to winning by maximizing the score from the punish and reward system. Simply, this type of ML model learns based on the response of its action. For example, Grace deploys her ML model to a robot to win her mother's love. On day 1, the robot decides to wash the dish and get a compliment from the mother. The robot learns that washing dishes is the right thing to do. On day 2, the robot keeps washing the dish and then throws them to the floor. As a result, the mother scolds the robot. The robot learns washing the dish is a good thing but throwing them to the floor is not. From the mother's response, the robot makes a dataset of what will make the mother happy and which one won't.

## Machine Learning Framework
Machine learning frameworks divides into four to five main processes. There are:

**1. Collecting the Dataset**
Machine Learning without data is nothing. The ML ability (classifies pictures, predicts the stock price, gives video recommendations, etc.) depends on the data that is used to train it. A data analyst describes the importance of data as " trash in, trash out." The quality of data defines the performance of the model. Data itself divides into two types. There are **structured (column and raws)** and **unstructured (pictures, audios,etc.)** data. Different types of data will need different treatments. 

**2. Pre-processing the Dataset**
This process relies on the type of dataset that we have. The treatment from structured data is different from the unstructured one. For example, the structured data (.Xls or .csv) sometimes need to be resampled e.g. upsampling and downsampling to make predictions, while unstructured data (images) need to be converted to an array to perform classification. However, the aim is the same. The aim of this process is to prepare the dataset to be well prepared and ready to be used for the next process.

**3. Building and Training the ML Model**
Each type of dataset uses a different algorithm to build the ML model. For example, structured data uses CatBoost or RandomForest Algorithm, while the unstructured data uses Convolutional Neural Network (CNN) and Decision Tree algorithm. The architect of the model relies on the algorithm that is used. For example, if the CNN algorithm is used, the model's architect will contain the convolution and pooling layers. 

**4. Evaluating and Tunning the ML Model**


**5. Deploying the Model**


