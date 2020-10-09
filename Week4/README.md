## Using the ImageGenerator

 An ImageGenerator can flow images from a directory and perform operations such as resizing them on the fly. The next thing to be done is to design the neural network to handle these more complex images.  The objective is to train it from data that’s on the file system, which can be read by generators. To do this, we don’t use model.fit as earlier, but a new method call: _model.fit_generator_.
