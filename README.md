# Melanoma Detection CNN - Case Study

## Overview

The aim of this project is to build a Convolutional Neural Network (CNN) model for accurately detecting melanoma, a potentially deadly type of skin cancer. Early detection is crucial in reducing the mortality rate associated with melanoma. The dataset used for this project consists of 2357 images of malignant and benign oncological diseases, categorized into different classes.

## Technologies Used

- Python 3.10.12
- TensorFlow 2.13.0
- Augmentor 0.2.12

## Dataset Information

The dataset includes images of the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

The dataset was sourced from the International Skin Imaging Collaboration (ISIC), and images were categorized based on ISIC classification.

## Model Findings

### Model 1: Epochs 1-20
The training and validation accuracy show an increasing trend, indicating the model is learning from the data.
A significant gap between training and validation accuracy suggests potential overfitting.
The training loss decreases, indicating improvement in minimizing differences between predicted and actual values on the training set.
Overall, the initial accuracy is low, and there is room for improvement.
### Model 2: Epochs 1-20
Incorporating dropout layers and data augmentation improves model performance.
A noticeable gap between training and validation accuracy suggests overfitting.
The training loss decreases steadily, but there are fluctuations in the validation loss.
Data augmentation contributes to the model's ability to generalize to unseen data.
### Model 3: Epochs 1-30
Data augmentation and dropout layers effectively improve model performance.
Both training and validation loss decrease consistently, indicating effective learning and generalization.
The model achieves high validation accuracy, indicating successful learning and generalization to unseen data.


## Conclusion

The final model, with data augmentation and dropout layers, achieved a validation accuracy of around 84%. The validation loss was 0.56, demonstrating effective learning and generalization. The Augmentor library was used to artificially generate additional samples, addressing the imbalance in the dataset.

For detailed findings and insights from each model, refer to the corresponding sections above.

## Acknowledgements

This project was inspired by a case study from the Executive PG Programme in Machine Learning by IIIT Bengaluru.

## Contact

Created by @rajni1624 - Feel free to reach out for further details or discussions.
