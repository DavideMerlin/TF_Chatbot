# TF_Chatbot
Implemented TensorFlow Sequence to Sequence model to train a ChatBot on a [Movie Dialogue Dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html) provided by Cornell. The model should take a few hours to fully train. Currently working on the UI. Also, I look forward to improve this model to adapt TF learn. It will then generate styled-specific sentences. It is interesting to play with the hyperparameters as well. 

Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``
