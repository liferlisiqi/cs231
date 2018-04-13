---
layout: page
mathjax: true
permalink: /assignments2017/assignment1/
---

In this assignment you will practice putting together a simple image classification pipeline, based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:

- understand the basic **Image Classification pipeline** and the data-driven approach (train/predict stages)
- understand the train/val/test **splits** and the use of validation data for **hyperparameter tuning**.
- develop proficiency in writing efficient **vectorized** code with numpy
- implement and apply a k-Nearest Neighbor (**kNN**) classifier
- implement and apply a Multiclass Support Vector Machine (**SVM**) classifier
- implement and apply a **Softmax** classifier
- implement and apply a **Two layer neural network** classifier
- understand the differences and tradeoffs between these classifiers
- get a basic understanding of performance improvements from using **higher-level representations** than raw pixels (e.g. color histograms, Histogram of Gradient (HOG) features)

## Working on the assignment:
Get the code as a zip file [here](http://cs231n.stanford.edu/assignments/2017/spring1617_assignment1.zip).

### Download data:
Once you have the starter code (regardless of which method you choose above), you will need to download the CIFAR-10 dataset.
Run the following from the `assignment2` directory:

```bash
cd cs231n/datasets
./get_datasets.sh
```

### Q1: k-Nearest Neighbor classifier (20 points)
The IPython Notebook `knn.ipynb` will walk you through implementing the kNN classifier.

### Q2: Training a Support Vector Machine (25 points)
The IPython Notebook `svm.ipynb` will walk you through implementing the SVM classifier.

### Q3: Implement a Softmax classifier (20 points)
The IPython Notebook `softmax.ipynb` will walk you through implementing the Softmax classifier.

### Q4: Two-Layer Neural Network (25 points)
The IPython Notebook `two_layer_net.ipynb` will walk you through the implementation of a two-layer neural network classifier.

### Q5: Higher Level Representations: Image Features (10 points)
The IPython Notebook `features.ipynb` will walk you through this exercise, in which you will examine the improvements gained by using higher-level representations as opposed to using raw pixel values.
