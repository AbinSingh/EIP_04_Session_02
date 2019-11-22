# EIP_04_Session_02
Assignment -02

1. Logs for 20 Epochs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 17s 281us/step - loss: 0.5332 - acc: 0.8519 - val_loss: 0.0917 - val_acc: 0.9832
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 11s 185us/step - loss: 0.2570 - acc: 0.9241 - val_loss: 0.0644 - val_acc: 0.9872
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 11s 183us/step - loss: 0.1997 - acc: 0.9406 - val_loss: 0.0554 - val_acc: 0.9857
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 11s 191us/step - loss: 0.1744 - acc: 0.9447 - val_loss: 0.0430 - val_acc: 0.9889
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1560 - acc: 0.9471 - val_loss: 0.0337 - val_acc: 0.9911
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 11s 181us/step - loss: 0.1430 - acc: 0.9500 - val_loss: 0.0318 - val_acc: 0.9918
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 11s 185us/step - loss: 0.1348 - acc: 0.9506 - val_loss: 0.0275 - val_acc: 0.9921
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 11s 186us/step - loss: 0.1241 - acc: 0.9548 - val_loss: 0.0281 - val_acc: 0.9921
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 11s 185us/step - loss: 0.1202 - acc: 0.9536 - val_loss: 0.0261 - val_acc: 0.9933
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 11s 190us/step - loss: 0.1157 - acc: 0.9554 - val_loss: 0.0229 - val_acc: 0.9941
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 11s 186us/step - loss: 0.1113 - acc: 0.9548 - val_loss: 0.0228 - val_acc: 0.9933
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 11s 190us/step - loss: 0.1102 - acc: 0.9537 - val_loss: 0.0216 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1048 - acc: 0.9564 - val_loss: 0.0210 - val_acc: 0.9939
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 11s 181us/step - loss: 0.1043 - acc: 0.9563 - val_loss: 0.0218 - val_acc: 0.9935
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 11s 189us/step - loss: 0.1016 - acc: 0.9567 - val_loss: 0.0207 - val_acc: 0.9942
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 11s 187us/step - loss: 0.0986 - acc: 0.9569 - val_loss: 0.0208 - val_acc: 0.9937
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 11s 185us/step - loss: 0.0997 - acc: 0.9557 - val_loss: 0.0220 - val_acc: 0.9936
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 11s 187us/step - loss: 0.0943 - acc: 0.9592 - val_loss: 0.0190 - val_acc: 0.9944
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 11s 185us/step - loss: 0.0968 - acc: 0.9563 - val_loss: 0.0192 - val_acc: 0.9943
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 11s 187us/step - loss: 0.0955 - acc: 0.9576 - val_loss: 0.0191 - val_acc: 0.9940


2. score = model.evaluate(X_test, Y_test, verbose=0)
print(score)
[0.019137114971666598, 0.994]

3.Strategy

Instead of using 32 channels in the 2nd convolution layer of eigth DNN model, I used only 16 channels.

And used Bias.
