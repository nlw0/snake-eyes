Snake Eyes
===

Snake Eyes is an artificial dataset for image analysis research. It was first published at [Kaggle](https://www.kaggle.com/nicw102168/snake-eyes/home), where you may be able to find more information and useful discussions.

![Snake eyes data sample](https://github.com/nlw0/snake-eyes/blob/master/se-sample.png?raw=true)

The images resamble thrown dice, but with modified patterns. They were produced by rendering a geometric model given only the parameters of face, position and orientation of each die. 

![Snake eyes data sample](https://github.com/nlw0/snake-eyes/blob/master/se-faces.png?raw=true)

This dataset was inspired by other popular ones such as MNIST, CIFAR-10 and Fashion-MNIST. There are important differences, though. The objects are not centered in the image, and the intra-class variation in mostly due to translation and rotation. The small resolution and large volume &mdash; one million 20×20 images &mdash; was intended to allow a full exploration of the actual three or six-dimentional manifolds created in the image space by changing these continuous parameters for each face combination.

The data is artificial, with limited and very well-defined patterns, noise-free and properly anti-aliased. Our goal is to help researchers investigate how different analysis methods compare in efficiency, how hard is it to train different models, and how the translation and rotation invariance is enforced or achieved.
