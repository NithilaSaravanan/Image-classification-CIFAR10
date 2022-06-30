# Image classification on CIFAR-10 dataset

The primary motive of this project was to understand,
implement and test two complex models on Image
classification. Even though it is known that Convolutional Neural Networks would emerge as the superior
algorithm, it is important to understand the workings of
Multilayer Perceptron.
- For both the models, data was preprocessed before being
fed into the classification models for MLP it was essential
to flatten, standardize and finally one hot encoded
and for CNN the data was augmented and normalized to
prevent over-fitting
- For both the models, the Generalization error estimated
on the validation dataset, which was collected from the
training dataset (20% split)
- Mini batch SGD with L2 and SGD with momentum
was selected as the best optimizers for MLP and CNN,
respectively


### Abstract from the report

The performance
of two Deep learning algorithms were compared with an
objective to classify image data; specifically the CIFAR - 10 data
set. The input data was augmented to support better predictions
and fed into the models. Along with various regularization
techniques, the models were also iteratively tested with different
types of optimizers as well as their performance was noted with
respect to varying model parameters. As expected, CNN proved
to be the superior technique for image classification. Morever,
additional experiments were performed with both the models,
one of which gives us a peek into how machines visualize the
world.
