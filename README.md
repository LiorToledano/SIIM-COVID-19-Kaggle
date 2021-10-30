# SIIM-COVID-19-Kaggle
81st place Solution for SIIM COVID 19 Kaggle competition 

## My main approach
Ensemble modelling
### Classification – Study level

* EfficientNet b7 – Trained on 600X600 resized images.
* EfficientNet V2 – Trained on 768X768 resized images.
* EfficientNet b7 – Trained on 640X640 resized images with external data from vinbigData competition.


### Classification – Image Level
* EfficientNet b7 – Trained on 512X512 resized images.
* EfficientNet b7 – Trained with dropout  on 512X512 resized images
* EfficientNet b5 – Trained with dropout on 512X512 resized images.

### Detection – Image Level
* Cascade RCNN 101 – Trained on 512X512 resized images
* I took the best two epochs from each fold to create a bigger and robust ensemble.

**5 Folds technique used in all models training.**


* I upload only one fold from 5 I trained  On Cascade RCNN 101.
* Each fold took approx 6 hours, so I divided each fold into another's Kaggle notebook.
* You can see the results of 4 extra folds, including some other training results on my weight & biases profile.

Thank you for your time.
