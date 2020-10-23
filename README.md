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
 Epoch 1/10
70/70 [==============================] - 30s 422ms/step - loss: 0.1236 - accuracy: 0.9693 - val_loss: 0.1030 - val_accuracy: 0.9710
Epoch 2/10
70/70 [==============================] - 29s 417ms/step - loss: 0.0592 - accuracy: 0.9883 - val_loss: 0.1119 - val_accuracy: 0.9668
Epoch 3/10
70/70 [==============================] - 29s 416ms/step - loss: 0.0675 - accuracy: 0.9878 - val_loss: 0.0907 - val_accuracy: 0.9710
Epoch 4/10
70/70 [==============================] - 29s 417ms/step - loss: 0.0528 - accuracy: 0.9914 - val_loss: 0.0880 - val_accuracy: 0.9834
Epoch 5/10
70/70 [==============================] - 29s 416ms/step - loss: 0.0370 - accuracy: 0.9964 - val_loss: 0.0532 - val_accuracy: 0.9876
Epoch 6/10
70/70 [==============================] - 29s 418ms/step - loss: 0.0675 - accuracy: 0.9838 - val_loss: 0.0981 - val_accuracy: 0.9793
Epoch 7/10
70/70 [==============================] - 29s 418ms/step - loss: 0.0274 - accuracy: 0.9964 - val_loss: 0.1205 - val_accuracy: 0.9751
Epoch 8/10
70/70 [==============================] - 29s 416ms/step - loss: 0.0224 - accuracy: 0.9977 - val_loss: 0.1015 - val_accuracy: 0.9751
Epoch 9/10
70/70 [==============================] - 29s 414ms/step - loss: 0.0795 - accuracy: 0.9833 - val_loss: 0.0939 - val_accuracy: 0.9793
Epoch 10/10
70/70 [==============================] - 29s 414ms/step - loss: 0.0430 - accuracy: 0.9928 - val_loss: 0.1273 - val_accuracy: 0.9751
```


 
 
