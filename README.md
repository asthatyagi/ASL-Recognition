# ASL-Recognition
To recognize ASL signs
American Sign Language (ASL) substantially facilitates communication in the deaf community. However, there are around 500,000 speakers which significantly limits the number of people that they can easily communicate with. The alternative of written communication is cumbersome, impersonal and even impractical when an emergency occurs. In order to diminish this obstacle and to enable dynamic communication, we present an ASL recognition system that uses Convolutional Neural Networks (CNN) to translate a picture of a user‟s ASL signs into text.
Convolutional Neural Networks take advantage of the fact that the input consists of images and they constrain the architecture in a more sensible way. In particular, unlike a regular Neural Network, the layers of a ConvNet have neurons arranged in 3 dimensions: width,height, depth.

The Database distribution is as follows:

1. Training data: We use 80% for training purposes.

2. Validation data: 20% images will be used for validation. These images are taken out of training data to calculate accuracy independently during the training process.

3. Test set: This is the Separate independent data for testing which has around 200 images for each alphabet.

tools: Python,Tensorflow,Docker,OpenCV,Numpy
