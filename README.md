# Car-Brand-Prediction
Used tranfer learning(ResNet50) to train the model. It predicts brand of the car among the 4 car brands (Audi,Lamborghini,Mercedes,Porsche)
Training image contains 121 car images and testing image contains 87 images.
Data Augmentation is performed to increase the number of images.
Intially the number of images where less, because of that I got higher accuracy but less validation accuracy. In order to increase the validation accuracy added more images to training and testing dataset.
Also decreased the Batch_size
Because of more images validation accuracy increased from
### Accuracy: , Validation_Accuracy:
Model is saved as model_resnet50.h5
Deployment is done using Flask and Heroku
