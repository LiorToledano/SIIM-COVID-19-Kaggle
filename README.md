# SIIM-COVID-19-Kaggle
81st place Solution for SIIM COVID 19 Kaggle competition 

My main approach

Classification – Study level - ensemble modeling

EfficientNet b7 – Trained on 600X600 resized images.
EfficientNet V2 – Trained on 768X768 resized images.
EfficientNet b7 – Trained on 640X640 resized images with external data from vinbigData comepition.


Classification – Image Level
EfficientNet b7 – Trained on 512X512 resized images.
EfficientNet b7 – Trained with dropout  on 512X512 resized images
EfficientNet b5 – Trained with dropout on 512X512 resized images.

Detection – Image Level
Cascade RCNN 101 – Trained on 512X512 resized images
I took the two best epochs from each fold inorder to create an ensemble

All models were trained with 5 Folds technique.


On siim-mmdetection-image train i upload only 1 fold from 5 i trained.
Each one of them took approx 6 hours so I divided each fold to another's kaggle notebook.
you can see the results of the 4 other folds including some others traning on my weight & biases profile

https://wandb.ai/liortoledano/projects

