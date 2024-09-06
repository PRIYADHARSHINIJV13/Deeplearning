# Deeplearning
1. Problem Statement:
The project aims to develop a deep learning model capable of classifying Alzheimer's disease severity using MRI images. The model is trained on a dataset that contains images of different stages of Alzheimer's, and it uses convolutional neural networks (CNN) to accurately predict the severity level of the disease.
2. Dataset Source and Description:
•	Dataset Source: The dataset is obtained from Hugging Face's "Falah/Alzheimer_MRI" collection.
•	Description: The dataset contains MRI images of patients categorized into four different classes representing the stages of Alzheimer's disease:
o	Non-Demented
o	Very Mild Demented
o	Mild Demented
o	Moderate Demented
These images are used for training, validating, and testing the CNN model to assess its accuracy in predicting Alzheimer's stages.
3. Model Training and Regularization Techniques:
•	The model is a CNN architecture with several convolutional layers followed by max-pooling layers. It also includes flattening and dense layers with a softmax output for classification.
•	Training Process: The model was trained on a split dataset (train, validation, and test sets), with an input size of 180x180 pixels, using the Adam optimizer and Sparse Categorical Crossentropy loss function.
•	Regularization: While no explicit regularization like dropout was used, the model employed early stopping, with 5 epochs being sufficient to prevent overfitting.
4. Results:
•	Validation Accuracy: Approximately 96%
•	Validation Loss: ~0.15 across epochs.

