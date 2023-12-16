# CS-422-Term-Project
Term project for CS 422 ODU Fall 2023. Image recognition and categorization using photos of food.
To run the code open image_classification.ipynb in vscode or jupeter notebook and insure tensor flow is installed.

functions:
    gen_training_data
        creates and returns training data of a specified size
    model_creation
        creates and returns the ResNet-50 model to be trained
    trainModel
        Trains the given model with the training proved training data
    find_accuracy
        uses the given labels and predictions to determine the accuracy of the predictions