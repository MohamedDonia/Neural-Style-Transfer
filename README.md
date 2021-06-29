# Neural Style Transfer

Neural Style Transfer (NST) is one of the most fun and interesting optimization techniques in deep learning. 
It merges two images, namely: a "content" image (C) and a "style" image (S), to create a "generated" image (G). 
The generated image G combines the "content" of the image C with the "style" of image S.

We are going to combine the Louvre museum in Paris (content image C) with the impressionist style of Claude Monet (content image S) to generate the following image:
<img width="725" alt="louvre_generated" src="https://user-images.githubusercontent.com/81274360/123808061-b4ae3b00-d8f0-11eb-9bec-a9bb615dd64a.png">

You will be using the the epynomously named VGG network from the original NST paper published by the Visual Geometry Group at University of Oxford in 2014. Specifically, you'll use VGG-19, a 19-layer version of the VGG network. This model has already been trained on the very large ImageNet database, and has learned to recognize a variety of low level features (at the shallower layers) and high level features (at the deeper layers).
