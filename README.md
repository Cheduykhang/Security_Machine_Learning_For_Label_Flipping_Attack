# Security_Machine_Learning_For_Label_Flipping_Attack
Attack Model use Label Flipping Attack then apply Security Machine Learning

# Model Used in the Program Implementation: (ResNet32)
ResNet32 is a deep neural network commonly used for image classification, particularly on datasets like CIFAR-10. It is a variant of the Residual Network (ResNet) architecture with 32 layers, designed to address issues such as vanishing gradients when training very deep networks. This allows ResNet32 to learn complex image features without losing information quality.

# Label Flipping Attack: 
Is a form of training data poisoning, where an attacker intentionally alters the labels of some data samples to degrade the performance of a machine learning model.
 - Poisoned Data: A small portion of the training data has its labels modified.
 - Attack Objective: When the model is trained on the poisoned data, it may produce incorrect predictions or perform poorly on test data.

# Workflow in project:
 - Train the Model: Train a deep learning model on clean (unaltered) training data.
 - Attack the Model: Apply a Label Flipping Attack by modifying the labels of a subset of the training data.
 - Train on Poisoned Data: Retrain the model using the attacked dataset.
 - Compare and Visualize: Evaluate and compare the performance of the clean and attacked models using metrics like accuracy, precision, recall, and F1-score. Visualize the differences through confusion matrices, loss curves, or decision boundary plots.
