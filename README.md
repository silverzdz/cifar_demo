# cifar_demo
A pytorch demo on cifar-10



### Environment Configuration

Before you run the demo, you need to configure following environments:

* Anaconda
* PyTorch
* torchvision
* Jupyter Notebook

**Anaconda**

To download, [click here](https://www.anaconda.com/products/individual).

You'd better create a new environment in anaconda to install pytorch. Don't remember to install python 3.

**PyTorch & torchvision**

At first, check [official website](pytorch.org) to get install command. For instance, I have a NVIDIA graphics card, so that my install command is:

```
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
```

If the download speed is too slow, you can use Tsinghua Open Source Mirror.

**Jupyter Notebook**

To install:

```
pip install jupyter notebook
```



### Dataset Download

[Click here](http://www.cs.toronto.edu/~kriz/cifar.html) to download cifar-10. Then put it in directory "dataset", unzipping it.