# Early crop disease discovery using leaf symptom images on a basis of Deep Convolutional Neural Networks

## **Description**
This model uses deep convolutional neural networks to detect early signs of crop diseases based on images of the plants' leaves. By analyzing the symptoms of the disease in the leaf images, the model is able to identify potential issues and alert farmers, allowing them to take action to prevent further spread of the disease and protect their crops. This can be an important tool for farmers, as early detection and intervention can help prevent significant losses.

## **Dataset**
The dataset used for this model is the [PlantVillage](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset) dataset, which contains images of healthy and diseased plant leaves. The dataset contains 54,305 images of 38 different plant species, with 14,308 images of diseased leaves and 39,997 images of healthy leaves. The dataset is split into 38 different folders, each containing images of a specific plant species. Within each folder, there are two subfolders, one containing images of healthy leaves and the other containing images of diseased leaves. The images are all in .jpg format and are 256x256 pixels in size.

## **Model**
The model used for this project is an ensemble of ResNet50 and ConvNext50.

## **Results**
The model was able to achieve an accuracy of 0.992 compared to the baseline model with 0.964 accuracy.

## **Future Work**
The model can be improved by using a larger dataset, as the current dataset is relatively small. The model can also be improved by using a more complex model, such as a ResNet101 or a ResNet152.

## **Code structure**
The code is structured as follows:
- `README.md`: This file.
- `requirements.txt`: The requirements for the project.
- `Project_Crop_disease.ipynb`: The notebook containing the code for the project.

