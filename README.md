# Melanoma Detection Assignment
This assignment is to to build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

    This project is aimed to create a solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the background of your project?

    Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?

    This project is building a CNN based model which can accurately detect melanoma. 

- What is the dataset that is being used?

    The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

    The data set contains the following diseases:

    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
    - To implementation the assignment I tried to follow a structured approach to handling the classification task of skin cancer types. The following key aspects were addressed:

    1. Class Imbalance Handling: The use of the Augmentor package effectively balanced the dataset by generating additional samples for underrepresented classes. This ensures fair representation across all classes and improves the model's ability to generalize.

    2. Enhanced Generalization with Data Augmentation: By applying data augmentation techniques like rotation, scaling, and flipping, the training dataset was artificially diversified. This approach reduces the risk of overfitting and strengthens the model's ability to handle unseen data.

    3. Comprehensive Model Design: The CNN architecture systematically integrates convolutional layers for feature extraction, max-pooling for dimensionality reduction, dropout for regularization, and fully connected layers for classification. The inclusion of normalization and flattening layers ensures efficient data preprocessing and flow.

    4. Regularization and Overfitting Prevention: The inclusion of dropout layers and early stopping during training mitigates overfitting. These techniques ensure the model remains robust and prevents unnecessary computational effort.

    5. Model Optimization and Validation: The use of Adam optimizer and sparse categorical cross-entropy loss ensures efficient optimization for multi-class classification. The implementation of callbacks, such as ModelCheckpoint and EarlyStopping, further guarantees model performance by saving the best model and halting training when improvement stagnates.

    6. Evaluation and Future Scope: The CNN model was trained and validated effectively, leveraging the outlined steps to achieve meaningful classification accuracy. Future enhancements could involve experimenting with deeper architectures, hyperparameter tuning, or advanced augmentation techniques to further improve performance.

    Overall, the methodology provides a solid foundation for skin cancer classification and highlights the importance of addressing data imbalance, applying data augmentation, and implementing a well-structured model architecture for achieving robust performance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.17.1
- matplotlib - version 3.8.0
- numpy - version 1.26.4
- pandas - version 2.2.2
- seaborn - 0.13.2
- Augmentor - version 0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by UpGrad IIITB Programme as a Melanoma Detection Assignment study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by [@Sinhakrrajesh@gmail.com] - feel free to contact me!


## License 
 This project is open source and available to all.