# WeaponDetectionYoloV5
Weapon detection model using yoloV5 pytorch


## Images Dataset 
https://github.com/ari-dasci/OD-WeaponDetection


## Data Preprocessing
Has two classes: Knife and Pistol

Images were labelled and split into Test (75%), Validation (10%) and Training set (15%)


## Training the Model
Model trained using the YoloV5 model on Google Colab
 
Trained for 100 epochs with batch size 32


## Training stats
|Class|Images|Labels|P|R|mAP@.5|mAP@.5:.95: 100%|
| --- | --- | --- | --- | --- | --- | --- |           
|all|697|799|0.92|0.839|0.91|0.618|
|knife|697|320|0.917|0.884|0.936|0.589|
|pistol|697|479|0.922|0.793|0.884|0.647|

## Inference
![knife](https://user-images.githubusercontent.com/73357431/171991389-a84e3bb1-c9c6-4b3c-95ab-6e2e37979a30.png)
![2](https://user-images.githubusercontent.com/73357431/171991416-81214327-7814-4410-9880-7a0354096673.jpg)


![4](https://user-images.githubusercontent.com/73357431/171991441-3b10c41d-b417-4f45-9cf4-176a932e6eef.jpg)
