Tech Stack: Tensorflow, Keras, Python, CNN-RNN and LSTM, Image processing and NLP

• In this project, I have created a neural network architecture to automatically generate captions from images.

• After using the Microsoft Common Objects in COntext (MS COCO) dataset to train your network, this project' network can be used on novel images!

• I passed all the inputs as a sequence to an LSTM. A sequence looks like this: first a feature vector that is extracted from an input image, then a start word, then the next word, the next word, and so on.

• Embedding Dimension: The LSTM is defined such that, as it sequentially looks at inputs, it expects that each individual input in a sequence is of a consistent size and so we embed the feature vector and each word so that they are embed_size.
