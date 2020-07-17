# Image Caption Generator

In the notebook, we implement and test the image caption geneartor proposed in [1]. We use the MobileNetV2 network to generate neural codes for each image in the flickr8k dataset. We then create encoder and decoder models based on RNNs. This is followed by predicting and evaluating the test captions using a greedy search and BLEU scores, respectively. 

[1] *Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan, "Show and Tell: A Neural Image Caption Generator", CVPR, 2015.* https://arxiv.org/abs/1411.4555

