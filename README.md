# LSTM-Model-for-Audio-Emotion-Classification
I trained a deep learning model on 5600 data to predict emotions on speech sound

As part of a project i am working on, i trained an LSTM model for predicting emotions on audio data and speach sound. I used the Toronto emotion speach set from kaggle for training the model https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess.

The dataset conprises of 5600 labaled data of different emotion sounds which includes: Angry, disgust, fear, happy, neutral, surprise, and sad. each of the emotions has 800 data.![Audio Barchat](https://github.com/user-attachments/assets/848cc32f-f892-4086-b911-9c6691342aed)

I build the neutral network with an input layer LSTM with 128 nuerons , two hidden layers and an output layer of 7 neuron and softmax as activation function. The network architecture is shown below:
![Neural Network](https://github.com/user-attachments/assets/689ecc1c-940b-406a-b789-c97afe53fbf8)

The model trained for 50 epochs having an accuracy of 0.98 and a loss of 0.03. The plot of accuracy and loss is shown below:
![accuracy plot](https://github.com/user-attachments/assets/9366f7a2-1c16-41b7-b4ac-10949a438956)

![loss Plot](https://github.com/user-attachments/assets/c67957f5-86e0-4f7a-8669-8477f3b432c2)

The model was also eveluated using confusion matrix.
The matrix score is show below
![Audio Confusion Matrix](https://github.com/user-attachments/assets/c32eeba5-0e2f-4885-94c3-cd1d0b3fd996)

