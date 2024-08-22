This code implements two neural network models, an Artificial Neural Network (ANN) and a Spiking Neural Network (SNN), 
to classify handwritten digits from the MNIST dataset. The ANN consists of three fully connected layers with ReLU activations,
while the SNN follows a similar architecture. The dataset is loaded with data augmentation techniques, and the models are trained 
using the Adam optimizer with a learning rate of 0.001 and the CrossEntropy loss function over 20 epochs. After training, both models
are evaluated on a test dataset to calculate their accuracy, aiming to achieve high performance (potentially over 99%) 
in the image classification task.
