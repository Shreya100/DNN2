# DNN2

### Log for 20 epochs
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 14s 231us/step - loss: 0.3313 - acc: 0.9366 - val_loss: 0.0837 - val_acc: 0.9821
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0935 - acc: 0.9802 - val_loss: 0.0478 - val_acc: 0.9875
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 7s 108us/step - loss: 0.0699 - acc: 0.9835 - val_loss: 0.0368 - val_acc: 0.9900
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0566 - acc: 0.9857 - val_loss: 0.0330 - val_acc: 0.9909
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 7s 111us/step - loss: 0.0497 - acc: 0.9876 - val_loss: 0.0333 - val_acc: 0.9915
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 7s 111us/step - loss: 0.0460 - acc: 0.9879 - val_loss: 0.0285 - val_acc: 0.9919
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 7s 109us/step - loss: 0.0417 - acc: 0.9891 - val_loss: 0.0260 - val_acc: 0.9930
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0412 - acc: 0.9889 - val_loss: 0.0327 - val_acc: 0.9907
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 7s 109us/step - loss: 0.0356 - acc: 0.9904 - val_loss: 0.0266 - val_acc: 0.9927
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0337 - acc: 0.9911 - val_loss: 0.0218 - val_acc: 0.9937
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0323 - acc: 0.9911 - val_loss: 0.0239 - val_acc: 0.9930
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0316 - acc: 0.9914 - val_loss: 0.0234 - val_acc: 0.9938
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0302 - acc: 0.9919 - val_loss: 0.0220 - val_acc: 0.9937
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0289 - acc: 0.9918 - val_loss: 0.0217 - val_acc: 0.9934
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 6s 107us/step - loss: 0.0278 - acc: 0.9922 - val_loss: 0.0218 - val_acc: 0.9939
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0282 - acc: 0.9921 - val_loss: 0.0220 - val_acc: 0.9939
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 7s 108us/step - loss: 0.0285 - acc: 0.9919 - val_loss: 0.0220 - val_acc: 0.9940
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0258 - acc: 0.9926 - val_loss: 0.0233 - val_acc: 0.9934
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 7s 109us/step - loss: 0.0263 - acc: 0.9924 - val_loss: 0.0206 - val_acc: 0.9939
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 6s 108us/step - loss: 0.0242 - acc: 0.9933 - val_loss: 0.0208 - val_acc: 0.9945


### model.evaluate (on test data)
[0.020821313086221926, 0.9945]


### Approach
* Added 16,32,10,16,16,16,16 Convolution layers
* Used Batch Normalization after each layer
* Added dropOut of 0.1
* Added a 1 X 1 kernel to convert 2D to 1D
* Added GAP on the last layer 
