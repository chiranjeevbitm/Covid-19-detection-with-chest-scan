**Important note**
You can find all codes and jupyter notebook files in each model's folder


# Covid-19-detection-with-chest-scan
This repo contains covid-19 detection with three algorithms , CNN , ResNet 50  and VGG 16 . out of which I got best accuracy with vgg16 as 98.8%

* •	Dataset of chest X-ray is downloaded from Kaggle.com and it is visualised for the proper understanding of the data before processing. Data augmentation is applied on the images so that it can effectively classify the covid-19 cases.
* •	CNN is proposed for the detection of covid-19 and hence controls the fast spreading covid-19 cases.
* •	Pre trained deep learning model that is transfer learning algorithm VGG-16 is used to increase the accuracy of the proposed model


**Sample Dataset Image**

![Dataset image](Sample_Dataset_image.png)

# CNN model

**CNN ACCURACY CURVE**

![Accuracy CNN](CNN%20run/Acc_CNN.png)

**CNN Confusion Matrics**

![Confusion Matrix CNN](CNN%20run/Confusion_Matrix_CNN.png)

**CNN ROC**

![CNN ROC](CNN%20run/ROC_cnn.png)



# ResNet50 model

**ResNet50 ACCURACY CURVE**

![Accuracy ResNet50](Transfer_Learning_ResNet50_GPU/Acc_&_loss_RN50.png)

**ResNet50 Confusion Matrics**

![Confusion Matrix ResNet50](Transfer_Learning_ResNet50_GPU/Confusion%20Matrix_RN50.png)

**ResNet50 ROC**

![ResNet50 ROC](Transfer_Learning_ResNet50_GPU/ROC_RN50.png)


# VGG16 model

**VGG16 ACCURACY CURVE**

![Accuracy VGG16](TransferLearning_VGG16_GPU/Accuracy%20curve_TL.png)

**VGG16 Confusion Matrics**

![Confusion Matrix VGG16](TransferLearning_VGG16_GPU/Confudion%20Matrix_TL.png)

**VGG16 ROC**

![ROC VGG16](TransferLearning_VGG16_GPU/ROC_TL.png)



**Accuracy comarision table**

![table](acc_comparision.png)



**Accuracy Comparision graphs**

![bar graphs](Acc_Com_Bar.png)


