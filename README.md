DeepNNImageMorph

A deep neural network configuration with (x,y) coordinates as input and (r,g,b) values as output is trained on images.

The weights and biases of all the layers are extracted from the layers of the trained network to form a parameter vector.

The parameter vectors are used to interpolate between two nets that each is trained on an image. The interpolated parameter vector for each image frame is used to reconstruct a network with the corresponding weights and biases and use that to produce the image of the frame. The result is a movie which starts in the first image and then goes on a straight line in parameter space to the second image during one minute.

The file OrdinaryFunctionsAndGLSL shows how the neural networks can be expressed with ordinary matrix multiplications and also code to generate GLSL Fragment shader code.

The project is in the Mathematica notebook file.
