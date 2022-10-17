# Melanoma Detection Assignment
> This mini project is to build a predictive model using convolutional neural network model to predict a form of Skin cancer called Melanoma which is one of the most deadliest form of Skin Cancer. The objective of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment uses a dataset of about 2357 images of skin cancer types provided by Upgrad as a part of the assignment. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively. The predictive model should be trained on the train dataset and validated using a subset of the train dataset (test data). 
- This solution aims to assist the medical practitioners and dermatologists to do pre-checks before asking the patients to go for a biopsy or a medical tests. It doesn't aim to replace the medical tests. 
- Good thing is that by just looking at the images the model should be able to predict if it's Melanoma or some other skin related issue (out of the 9 classes). 

Steps followed in this assignment.

1. Import the images and visualize them (EDA)
2. Convert the images to Tensorflow dataset (Preprocessing, Scaling etc.)
3. Build a basic CNN model --> Observation from the model 
4. Add overfitting measures like Data augmentation, Dropouts etc.
5. Build another model with new components to control overfitting ---> Observation from the model 
6. Analzye the Class imbalance issue in the dataset
7. Use Augmentor pipeline to generate new images for training purposes to resolve the class imblance issues. 
8. Build a CNN model and test the same with the newly generated data. --> Observations from the model 
9. Final observation and conclusion.

## Technologies Used
- Tensorflow v2.9.2
- Keras v2.9.0
- Matplotlib v3.2.2
- Seaborn v0.11.2
- Numpy v1.21.6
- Pandas v1.3.5
- Augmentor v0.2.10
- Python packages OS,PIL etc.
- Google Colab

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- First basic CNN model which was overfitting. In the second model we applied overfitting measures like Data augmentation, Dropouts and Batch normalization. But the second model resulted in very low training accuracy i.e. underfitting. Finally, we used the Augmentor to generate more images to fix the class imbalance issue. Using the new and the old dataset for training the final model, we were able to get 82.6% test accuracy i.e. the model was able to correctly predict 82.6% of the images into correct classes. 
- Below is our final model

![image](https://user-images.githubusercontent.com/28692811/196173619-c01e7dbe-99e1-4dcb-9179-0beb0b487c83.png)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the online tutorials and live sessions conducted by the Upgrad and IIIT(B) faculty.

## Contact
Created by [@gautamjoshi1984] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
