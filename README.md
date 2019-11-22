# EIP_04_Session_02
Assignment -02

1. Logs for 20 Epochs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 17s 275us/step - loss: 0.5195 - acc: 0.8556 - val_loss: 0.0806 - val_acc: 0.9852
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 11s 177us/step - loss: 0.2471 - acc: 0.9280 - val_loss: 0.0530 - val_acc: 0.9891
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1968 - acc: 0.9408 - val_loss: 0.0437 - val_acc: 0.9901
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 11s 177us/step - loss: 0.1661 - acc: 0.9475 - val_loss: 0.0385 - val_acc: 0.9896
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 11s 177us/step - loss: 0.1523 - acc: 0.9492 - val_loss: 0.0301 - val_acc: 0.9925
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 11s 177us/step - loss: 0.1374 - acc: 0.9515 - val_loss: 0.0271 - val_acc: 0.9926
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 11s 175us/step - loss: 0.1282 - acc: 0.9534 - val_loss: 0.0287 - val_acc: 0.9921
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 11s 179us/step - loss: 0.1217 - acc: 0.9538 - val_loss: 0.0251 - val_acc: 0.9930
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 11s 178us/step - loss: 0.1144 - acc: 0.9561 - val_loss: 0.0307 - val_acc: 0.9921
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1112 - acc: 0.9551 - val_loss: 0.0227 - val_acc: 0.9932
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1103 - acc: 0.9559 - val_loss: 0.0221 - val_acc: 0.9937
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1056 - acc: 0.9565 - val_loss: 0.0210 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 11s 177us/step - loss: 0.1022 - acc: 0.9573 - val_loss: 0.0256 - val_acc: 0.9931
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1007 - acc: 0.9577 - val_loss: 0.0186 - val_acc: 0.9946
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 11s 175us/step - loss: 0.0979 - acc: 0.9577 - val_loss: 0.0201 - val_acc: 0.9947
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 11s 176us/step - loss: 0.0998 - acc: 0.9563 - val_loss: 0.0178 - val_acc: 0.9949
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 11s 176us/step - loss: 0.0953 - acc: 0.9575 - val_loss: 0.0187 - val_acc: 0.9944
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 11s 176us/step - loss: 0.0923 - acc: 0.9590 - val_loss: 0.0207 - val_acc: 0.9940
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 11s 176us/step - loss: 0.0946 - acc: 0.9569 - val_loss: 0.0216 - val_acc: 0.9938
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 11s 177us/step - loss: 0.0908 - acc: 0.9585 - val_loss: 0.0194 - val_acc: 0.9946



2. score = model.evaluate(X_test, Y_test, verbose=0)
print(score)
[0.01938052006261423, 0.9946]


3.Strategy

Instead of using 32 channels in the 2nd convolution layer of eigth DNN, I used only 16 channels.

And used Bias.
