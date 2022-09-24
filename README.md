# Retinal_Fundus
## Dataset
Used Retinal Fundus dataset "1000 Fundus images with 39 categories"
Link: https://zenodo.org/record/3477553#.Yy5Uz6TMKUk

## Training
To train directly run file retina_fundus_classifier.ipynb, training will run using ResNet model
Models can be chosen in the cell heading "Task Two - Train":
```
#modelname="vgg"
#modelname="naive"
#modelname="inception"
modelname="resnet"
```
Here vgg16, resnet152, inception_v3, and custom models can be used for training.

## Hyperparmeters
Hyperparameters can be changed in file config.yml

## Testing
To run testing directly please provide path in config.yml in weights. Weight file model_resnet_50_epochs.pth is attached in email. Below is an example to test directly using path:
weights: 'model_resnet_50_epochs.pth'
