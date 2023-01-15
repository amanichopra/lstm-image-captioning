# LSTM Image Captioning

In this project, I use the flickr8k dataset to generate captions for images. First, I create image embeddings using Inception V3 off-the-shelf. Then, I build a  network with a text embedding layer, concatenation layer to condition on the image, a bi-directional LSTM layer, and a dense layer with a softmax output. Lastly, I implement beam search to decode the image and generate a caption.
