# QML-for-Conspicuity-Detection-in-Production

To solve the probelm of detecting conspicuity in Production,my solution presents two techniques, Quantum Neural Networks and Quanvolutional Neural Networks. Due to the alrge class imbalance the models were evaluated upon the F1 score. For the QNN, I reduced image dimensionality using PCA and implemented a hybrid model combining classical and quantum layers. For the second method, I applied a Quanvolutional layer on the images, and then passed them as input to a classical model. These results were compared to the passing just the images as it is to the same model, that is without quantum pre-processing.



