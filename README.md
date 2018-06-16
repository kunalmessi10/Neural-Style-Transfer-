# Neural-Style-Transfer-
PyTorch implementation of the Neural Style Transfer Algorithm 

Neural style transfer is an algorithm that takes as a input a content-image, a style image, and returns the content of the content image as if it was painted using the artistic style of the style-image.

## How does it work?
In this algorithm, we define two distances namely the Content Distance(D_c) and the Style Distance(D_s).

Content Distance: It measures that how different is the content between the original image and the output image of the algorithm.

Style Distance: It indicates how different are the output image or feature map and the style image.

We take a third image ie the input and we transform it in order to both minimize its D_c with Content Image and D_s with Style Image.
