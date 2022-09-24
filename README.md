# Retinal_Fundus
## Dataset
Used Retinal Fundus dataset "1000 Fundus images with 39 categories"

Link: https://zenodo.org/record/3477553#.Yy5Uz6TMKUk

## Training
To train just directly run Jupter Notebook retina_fundus_classifier.ipynb.

Testing will run straight after finishing of training.

Training will run using ResNet model.

Here I also used other models like vgg16, resnet152, inception_v3, and a custom model for training.

Other models can be chosen by uncommenting/commenting in the cell heading "Task Two - Train":
```
#modelname="vgg"
#modelname="naive"
#modelname="inception"
modelname="resnet"
```

Note please keep weights: just empty to train

## Hyperparmeters
Hyperparameters can be changed in file config.yml

## Testing
To run separate testing, please provide path in config.yml in weights. 

Please use link https://drive.google.com/file/d/1mRSCq4mg-KdpJA_do-0D9G_5yV60Jiaq/view?usp=sharing for sample weights model_resnet_50_epochs.pth. 

Below is an example to test directly using path:
weights: 'model_resnet_50_epochs.pth'
