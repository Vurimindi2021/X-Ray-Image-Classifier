## Chest X-Ray Image Classifier

I developed convolution neural network (CNN), deep learning and computer-assisted  diagnostics model to detect pneumonia & other lung diseases in chest X-Ray images. The model is trained, tested and validated using NIH's 100,000 anonymized chest x-ray images belongs to 30,000 patients including many with advanced lung diseases ['Atelectasis','Cardiomegaly','Consolidation', 'Edema','Effusion','Emphysema','Fibrosis','Hernia', 'Infiltration', 'Mass', 'NoFinding', 'Nodule', 'Pleural_Thickening', 'Pneumonia','Pneumothorax']. The X-Ray images are available at https://nihcc.app.box.com/v/ChestXray-NIHCC.

# Sample Training Images
![matrix_images](https://user-images.githubusercontent.com/78239454/129116154-7f9469e4-e8bf-49bf-9a49-5af6b71036e0.png)

# CNN Models

Initially developed Sequential Model with Conv2D, AveragePooling2D, Flatten, Dropout, and Dense Layers with total trainable 10,633,185 parameters to train the model. Theereafter used transfer learned from four(4) different models VGG16(138 million trainable parameters), VGG19(144 million Trainable  parameters), InceptionResNetV2 (54,339,810 trainable parameters), ResNet152V2(8,450,754 trainable parameters).

# Model Performance 
![xraycm](https://user-images.githubusercontent.com/78239454/129116336-3cbc7c6e-1c33-4888-a051-b24f2cf861da.png)


# Predictions
![predictions](https://user-images.githubusercontent.com/78239454/129116261-76963b28-e43d-4707-953d-4ff1e65794fa.png)

# Conclusion
In conclusion none the models performed well. In future, to make the model better I will need to develop more complex CNN models and see if there are any more hyperparameters that can be tweaked for better performance. So work still in progress.
