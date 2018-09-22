DeepNNImageMorph

Images are trained with a deep neural network configuration with (x,y) coordinates as input and (r,g,b) valuies as output.

The weights and biases of all the layers are extracted from the layers of the trained networks to form a parameter vector.

The parameter vectors are used to interpolate between two nets that each represent an image and produce a movie of images going from the first along a straight line in the network parameter space and to the second.

The file OrdinaryFunctionsAndGLSL shows how the neural networks can be expressed with ordinary matrix multiplications and also code to generate GLSL Fragment shader code.

The project is in the Mathematica notebook file.
