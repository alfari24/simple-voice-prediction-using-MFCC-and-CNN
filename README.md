

# simple-voice-prediction-using-MFCC-and-CNN


# how to use
very simple, just simply open it on google colab, or jupyter notebook.
you can adjust the program to your needs, hope it helps

- pip install pydub (needed to read voice)

here we train some sounds to predict, I have provided 3 files that will be prediscussed using 3 layers and 32.16.8 filter size 3x3 softmax activation using sparse_categorical_crossentropy so that we get 0.9630 accuracy and 0.1365 loss

7/7 [==============================] - 0s 9ms/step - loss: 0.1115 - accuracy: 0.9630
Epoch 29/30
7/7 [==============================] - 0s 8ms/step - loss: 0.1066 - accuracy: 0.9630
Epoch 30/30
7/7 [==============================] - 0s 9ms/step - loss: 0.1365 - accuracy: 0.9630



![download](https://user-images.githubusercontent.com/56450870/128736514-68fa7c13-1fde-4bb3-bb4a-a1cfdd839b4b.png)

this is the result of training from 3 voices


# save Model
then at the end of the program you can save the results of the voice training into a .h5 file that you will use in your program

classifier.save_weights('suara.h5') or use classifier.save('suara.h5')
according to your needs





