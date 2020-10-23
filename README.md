# Vehicle Orientation

Using [InceptionV3](https://www.tensorflow.org/api_docs/python/tf/keras/applications/InceptionV3), use transfer learning to train a model to learn
the orientation of a vehicle with the following classes:
 * Back
 * Back left
 * Back right
 * Front
 * Front left
 * Front right
 * Interior
 * Left
 * Right
 * Unclassified (e.g. a logo)
 
 ```
Model: 
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
inception_v3 (Functional)    (None, None, None, 2048)  21802784  
_________________________________________________________________
global_average_pooling2d_2 ( (None, 2048)              0         
_________________________________________________________________
dense_2 (Dense)              (None, 64)                131136    
_________________________________________________________________
dropout_2 (Dropout)          (None, 64)                0         
_________________________________________________________________
out (Dense)                  (None, 10)                650       
=================================================================
Total params: 21,934,570
Trainable params: 19,102,026
Non-trainable params: 2,832,544
 
 
Epoch 1/3
70/70 [==] - 22s 310ms/step - loss: 0.1433 - accuracy: 0.9634 - val_loss: 0.1928 - val_accuracy: 0.9751
Epoch 2/3
70/70 [==] - 22s 314ms/step - loss: 0.1275 - accuracy: 0.9698 - val_loss: 0.1491 - val_accuracy: 0.9627
Epoch 3/3
70/70 [==] - 22s 312ms/step - loss: 0.1196 - accuracy: 0.9689 - val_loss: 0.0802 - val_accuracy: 0.9876
```

### Accuracy graph

![Accuracy](https://github.com/danrosher/colab/blob/main/accuracy.png)


### Loss graph


![Loss](https://github.com/danrosher/colab/blob/main/loss.png)


 
 
