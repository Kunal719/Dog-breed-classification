End-to-end Multi-class Dog Breed Classification
This notebook builds an end-to-end multi-class image classifier using Tenserflow 2.0 and TenserFlow Hub

1. Problem
Identifying the breed of the dog given an image of dog.

2. Data
Data is being used from - https://www.kaggle.com/c/dog-breed-identification

3. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

4. Features
Some info about the data:

We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning
There are 120 breeds of dogs (means there are 120 classes)
There are 10,000+ images in the training and test set
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Epoch Accuracy Graph for Full Model

![full_model_epoch_accuracy](https://user-images.githubusercontent.com/24477155/132215879-105837f6-61e4-4111-a2f7-bed340c061ac.PNG)

Epoch Loss Graph for Full Model

![full_model_epoch_loss](https://user-images.githubusercontent.com/24477155/132215966-a3d2b3d7-0c4c-4a27-9dc4-b0e9bb595a39.PNG)


