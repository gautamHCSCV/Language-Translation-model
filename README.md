# Language-Translation-model
Tensorflow model to translate English text to German language.
We made a custom encoder model which also returns cell state and hidden state of the LSTM layer. This encoder model runs on english text corpus and outputs the cell state of final LSTM layer. These states are used as the initial state for the decoder model, which helps to predict the tokenized sequence of German text. A pre-trained embedding layer is used to tokenise the english text. Finally implemented the model using flask.


# Some Demo of Flask implementation of the model

![image](https://user-images.githubusercontent.com/65457437/126872790-a2734248-cb4d-45fb-8bbd-1b82802eeeec.png)


![image](https://user-images.githubusercontent.com/65457437/126872593-3ec91bf6-6ca4-4719-b8fa-6fb39d44f576.png)


![image](https://user-images.githubusercontent.com/65457437/126872722-e9ff568a-c287-44d8-b490-794f9957c2c9.png)


