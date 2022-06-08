# Image-Caption-Generation: Self-Attention
1) This model is an enhancement on simple Encoder Decoder Image Caption Generation model.
2) Four different techniques we employed to boost the performance of model:
a) Trainable Embedding layer without any pre-initialization of weights
b) Bidirectional LSTM with higher number of units to encode the texts input better
c) Self-Attention layer to focus on specific part
d) Concatenate layer for merging the image and text feature vectors
3) Model is trained for 70 epochs with adam optimizer and we got an accuracy of >70%
   (which is an improvement of >23% from the previous, simple Encoder Decoder model.
