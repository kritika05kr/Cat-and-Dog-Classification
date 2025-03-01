# Cat-and-Dog-Classification
A CNN-based model using TensorFlow and Keras to classify cats and dogs. It features three convolutional layers, batch normalization, and max pooling for efficient feature extraction. The model processes 256x256 images and uses sigmoid activation for classification. 

Features
Deep Learning-Based Classification: Utilizes a CNN for accurate image classification.

Layered Architecture: Three convolutional layers with increasing filters (32, 64, 128) to extract complex patterns.

Batch Normalization: Reduces internal covariate shift and improves training stability.

Max Pooling: Downsamples feature maps to retain essential information while reducing computational cost.

Fully Connected Layers: Flattened output is passed through dense layers for final classification.

Binary Classification: Uses a sigmoid activation function to classify images as either a cat or a dog.

Dataset:
The model is trained on a dataset containing images of cats and dogs, resized to 256x256 pixels for uniform input size. The dataset is preprocessed before training to ensure optimal model performance.

Model Architecture:

1.Three Convolutional Layers

Filters: 32, 64, 128
Kernel Size: 3x3
Activation: ReLU
Batch Normalization
Max Pooling (2x2)

2.Fully Connected Layers:

Flattening Layer
Dense Layer (128 neurons, ReLU activation)
Dropout (0.1)
Dense Layer (64 neurons, ReLU activation)
Dropout (0.1)
Output Layer (1 neuron, Sigmoid activation)
