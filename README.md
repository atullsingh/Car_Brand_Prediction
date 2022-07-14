Heroku App: https://carbranding.herokuapp.com/
# Car-Brand-Prediction Using VGG16 
Initially used ResNet50 for transfer learning to train the model. It predicts brand of the car among the 4 car brands (Audi,Lamborghini,Mercedes,Porsche)
Training image contains 126 car images and testing image contains 80 images.
Data Augmentation is performed to increase the number of images.
Also Increase the epochs from 20 to 50.
Intially the number of images where less, because of that I got higher accuracy but less validation accuracy. In order to increase the validation accuracy added more images to training and testing dataset.

Because of above steps accuracy increased marginally. 
 Accuracy:78.57% , Validation_Accuracy:58.75%
### Running VGG16, for better accuracy 
Also added a dense layer before the output with the activation function relu
Finally accuracy for vgg16 after 20 epochs.
#### Accuracy:100 % , Validation_Accuracy=80 %
Model is saved as model_vgg16.h5
## Model deployement is done using Heroku
Initially tried deployment using Azure but after few checks it stopped working. Decided to use Heroku for deployement
Azure app link  :https://carbrand.azurewebsites.net
## This repository does not contain model_vgg.h5 file because of its large size
