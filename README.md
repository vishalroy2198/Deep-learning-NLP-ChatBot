# Deep learning NLP ChatBot (RNNs LSTM)

We will through this tutorial build a SEQ2SEQ architecture ChatBot.
The RNN structure chosen, or to be exact the most adequate for this problem will be the many-to-many structure, that has a non-specified input length (which means it is a paramater of the algorithm and varies with the length of the query), and a non-specified output length (it's up to the network to decide the length, but we can make a threshold for the length of the ChatBot answers if we need to).   

![RNN model used](https://user-images.githubusercontent.com/47015407/63578572-aa9ab300-c588-11e9-934a-8f3accd9ee34.png)
Source: http://karpathy.github.io

So the be perfectly precise the model chosen is an LSTM network, since we want the network to not only get use of the memory pipeline provided by the RNN idea, but also to get information from each response it generated previously. 

![RNN model used](https://user-images.githubusercontent.com/47015407/63579938-9c01cb00-c58b-11e9-9b74-467e55c10967.png)

