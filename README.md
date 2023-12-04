# Melanoma Detection CNN - Case Study

## Overview
Automated Melanoma Detection CNN project utilizing TensorFlow and Augmentor for early and accurate skin cancer diagnosis with a dataset of diverse oncological images.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Dataset Information](#Dataset-Information)
* [Model Findings](#Model-Findings)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project aims to build a Convolutional Neural Network (CNN) model for accurately detecting melanoma, a potentially deadly type of skin cancer. Early detection is crucial in reducing the mortality rate associated with melanoma. The dataset used for this project consists of 2357 images of malignant and benign oncological diseases, categorized into different classes.

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
The training and validation accuracy exhibit an upward trend, indicating the model is learning from the data.
A significant gap between training and validation accuracy suggests potential overfitting, indicating that the model may be memorizing the training data.
The training loss decreases, signifying an improvement in minimizing differences between predicted and actual values on the training set.
The initial accuracy is relatively low, highlighting the need for improvement.
### Model 2: Epochs 1-20
While an improvement over Model 1, there is still room for enhancement.
Incorporating data augmentation contributes to improved model performance.
A noticeable gap between training and validation accuracy suggests potential overfitting.
The training loss decreases steadily, but fluctuations in the validation loss are observed.
### Model 1: Epochs 1-30
Outperforming both Model 1 and Model 2.
The combination of data augmentation and dropout layers significantly enhances model performance.
Both training and validation loss consistently decrease, indicating robust learning and generalization.
The model achieves a high validation accuracy, demonstrating successful learning and effective generalization to previously unseen data.

## Conclusions
The initial model showed a gradual improvement in accuracy but exhibited overfitting, suggesting a need for further optimization.
Model 2, incorporating data augmentation, demonstrated enhanced performance but still requires refinement.
Model 3, with data augmentation and dropout layers, outperformed the previous models, achieving high validation accuracy and effective generalization.

## Conclusion

The final model, with data augmentation and dropout layers, achieved a validation high accuracy of 75%. The validation loss was 0.5, demonstrating effective learning and generalization. The Augmentor library was used to artificially generate additional samples, addressing the imbalance in the dataset.

For detailed findings and insights from each model, refer to the corresponding sections above.

## Acknowledgements

This project was inspired by a case study from the Executive PG Programme in Machine Learning by IIIT Bengaluru.

## Contact

Created by @rajni1624 - Feel free to reach out for further details or discussions.
