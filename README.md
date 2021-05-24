# Object Recognition using CNN on CIFAR10 Dataset

CIFAR-10  is an established computer-vision dataset used for object recognition. CIFAR is an acronym that stands for the Canadian Institute For Advanced Research and the CIFAR-10 dataset was developed along with the CIFAR-100 dataset by researchers at the CIFAR institute. The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc. The class labels and their standard associated integer values are listed below.

- 0: airplane
- 1: automobile
- 2: bird
- 3: cat
- 4: deer
- 5: dog
- 6: frog
- 7: horse
- 8: ship
- 9: truck

![cifar-10.png](/cifar-10.png)

These all are very small images, much smaller than a typical photograph, and the dataset was intended for computer vision research. CIFAR-10 is a well-understood dataset and widely used for benchmarking computer vision algorithms in the field of machine learning. The problem is “solved.” It is relatively straightforward to achieve 80% classification accuracy. Top performance on the problem is achieved by deep learning convolutional neural networks with a classification accuracy above 90% on the test dataset.

In this project, we are going to implement the following steps:
1. Importing the necessary packages
2. Loading the MNIST Dataset from Keras Datasets
3. Normalizing the Images
4. OneHot Encoding of output Classes
5. Creating the Convolutional Neural Network
6. Regularization to increase the accuracy of the model
7. Data Augmentation to reduce overfitting

After the successful training the baseline Model has given 68% accuracy. 

![Baseline Model Graph](/1.png)

By applying regularization methods we could achieve 83% accuracy.

![Regularization Graph](/2.png)

After applying DataAugmentation the accuracy has been increased to 87%.

![Data Augmentation Graph](/3.png)
