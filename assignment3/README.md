# Assignment3

In this assignment you will implement recurrent networks, and apply them to image captioning on Microsoft COCO. You will also explore methods for visualizing the features of a pretrained model on ImageNet, and also this model to implement Style Transfer. Finally, you will train a generative adversarial network to generate images that look like a training dataset!

The goals of this assignment are as follows:

- Understand the architecture of **recurrent neural networks (RNNs)** and how they operate on sequences by sharing weights over time
- Understand and implement both Vanilla RNNs and Long-Short Term Memory (LSTM) RNNs
- Understand how to sample from an RNN language model at test-time
- Understand how to combine convolutional neural nets and recurrent nets to implement an image captioning system
- Understand how a trained convolutional network can be used to compute gradients with respect to the input image
- Implement and different applications of image gradients, including saliency maps, fooling images, class visualizations.
- Understand and implement style transfer.
- Understand how to train and implement a generative adversarial network (GAN) to produce images that look like a dataset.

## Working on the assignment:
Get the code as a zip file [here](http://cs231n.stanford.edu/assignments/2017/spring1617_assignment3_v3.zip).

### Download data:
Once you have the starter code (regardless of which method you choose above), you will need to download the CIFAR-10 dataset.
Run the following from the `assignment2` directory:

```bash
cd cs231n/datasets
./get_assignment3_data.sh
```

### Q1: Image Captioning with Vanilla RNNs (25 points)
The Jupyter notebook `RNN_Captioning.ipynb` will walk you through the implementation of an image captioning system on MS-COCO using vanilla recurrent networks.
参考链接:
[循环神经网络(RNN)模型与前向反向传播算法]{https://www.cnblogs.com/pinard/p/6509630.html}
[np.ufunc.at]{https://docs.scipy.org/doc/numpy/reference/generated/numpy.ufunc.at.html}

### Q2: Image Captioning with LSTMs (30 points)
The Jupyter notebook `LSTM_Captioning.ipynb` will walk you through the implementation of Long-Short Term Memory (LSTM) RNNs, and apply them to image captioning on MS-COCO.

### Q3: Network Visualization: Saliency maps, Class Visualization, and Fooling Images (15 points)
The Jupyter notebooks `NetworkVisualization-TensorFlow.ipynb /NetworkVisualization-PyTorch.ipynb` will introduce the pretrained SqueezeNet model, compute gradients with respect to images, and use them to produce saliency maps and fooling images. Please complete only one of the notebooks (TensorFlow or PyTorch). No extra credit will be awardeded if you complete both notebooks.

### Q4: Style Transfer (15 points)
In the Jupyter notebooks `StyleTransfer-TensorFlow.ipynb/StyleTransfer-PyTorch.ipynb` you will learn how to create images with the content of one image but the style of another. Please complete only one of the notebooks (TensorFlow or PyTorch). No extra credit will be awardeded if you complete both notebooks.

### Q5: Generative Adversarial Networks (15 points)
In the Jupyter notebooks `GANs-TensorFlow.ipynb/GANs-PyTorch.ipynb` you will learn how to generate images that match a training dataset, and use these models to improve classifier performance when training on a large amount of unlabeled data and a small amount of labeled data. Please complete only one of the notebooks (TensorFlow or PyTorch). No extra credit will be awarded if you complete both notebooks.

