# kaggle-Intel-Image-classification-fastai

This is the fastai implementation of Intel Image Dataset available at [kaggle](https://www.kaggle.com/puneet6060/intel-image-classification)


The data contains 25k images of size 150x150 distributed under 6 categories:


{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }

Pretrained and freezed resnet 34 and resnet 50 are used. Accuracy on valid set for resnet 34 is 92.3667% and for resnet 50 is 94.133%


## TODO

- Unfreeze whole model and train again and observe changes in the metrics.
- Get accuracy on the test set provided. 


More info about the data in the link above.

