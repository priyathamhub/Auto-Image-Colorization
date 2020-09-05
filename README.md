## Auto-Colorization

In this project, we built a (simple) automatic image colorizer from scratch in PyTorch!

In image colorization, our goal is to produce a colored image given a grayscale input image. This problem is challenging because it is multimodal -- a single grayscale image may correspond to many plausible colored images. As a result, traditional models often relied on significant user input alongside a grayscale image.

Recently, deep neural networks have shown remarkable success in automatic image colorization -- going from grayscale to color with no additional human input. This success may in part be due to their ability to capture and use semantic information (i.e. what the image actually is) in colorization, although we are not yet sure what exacly makes these types of models perform so well.

Dataset Link : http://data.csail.mit.edu/places/places205/testSetPlaces205_resize.tar.gz
Download and unzip.
