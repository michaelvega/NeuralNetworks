# Neural Networks

### Includes three Neural Networks working with Keras Datasets
* **Articial Neural Network ([ANN.ipynb](https://github.com/michaelvega/NeuralNetworks/blob/main/lib/ANN.ipynb))** - An articial Neural Network that classifies the [Fashion MNIST dataset](https://keras.io/api/datasets/fashion_mnist/) with multiclass classification. This model utilizes two fully connected dense layers, a dropout layer, and a dense output layer.

* **Convolutional Neural Network ([CNN.ipynb](https://github.com/michaelvega/NeuralNetworks/blob/main/lib/CNN.ipynb))** - An articial Neural Network that classifies the [CIFAR10 dataset](https://keras.io/api/datasets/cifar10/) with multiclass classification. This model utilizes two convolutional layers followed by a pooling layer (twice), a flattening layer, and an ANN (same layers as above).

* **Recurrent Neural Network ([RNN.ipynb](https://github.com/michaelvega/NeuralNetworks/blob/main/lib/RNN.ipynb))** - An articial Neural Network that classifies the [IMDB movie review sentiment classification dataset](https://keras.io/api/datasets/imdb/) with binary classification—negative or positive review. The reviews are gauged through natural language processing sentiment analysis. This model utilizes an embedding layer (given the NLP nature of the problem), a Long Short Term Memory layer (for recurrent NN), and a dense output layer.

| Neural Network  | Accuracy |
| ------------- |:-------------:|
| ANN      | 0.883899986743927%     |
| CNN      | 0.7233999967575073%     |
| RNN      | 0.8447999954223633%     |

`Note:` The ANN and CNN models both use [MISH](https://arxiv.org/abs/2209.06119) instead of ReLU for activation functions, as these achieved better performance. 
