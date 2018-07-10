# Data augumentation

Data augmentation is a type of regularization that changes training examples, modifying their appearances. With this technique, the network sees new training data from the original training data. 

# Dataset

In this project we will use [Flower-17 dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/17/).

# Usage

Train without data augmentation:
```sh
$ python minivggnet_flowers17.py --dataset "path_to_dataset"
```

Train with data augmentation:
```sh
$ python minivggnet_flowers17_data_aug.py --dataset "path_to_dataset"
```

# Reference
This code was obtained from book "Deep Learning for Compution Vision".

