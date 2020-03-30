# vGG16

The VGG() class takes a few arguments:

1:include_top (True): Whether or not to include the output layers for the model. You don’t need these if you are fitting the model on your   own problem.
2:weights (‘imagenet‘): What weights to load. You can specify None to not load pre-trained weights if you are interested in training the     model yourself from scratch.
3:input_tensor (None): A new input layer if you intend to fit the model on new data of a different size.
4: input_shape (None): The size of images that the model is expected to take if you change the input layer.
5:pooling (None): The type of pooling to use when you are training a new set of output layers.
6:classes (1000): The number of classes (e.g. size of output vector) for the model
