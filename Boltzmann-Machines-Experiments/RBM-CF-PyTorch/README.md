# Restricted Boltzmann Machines for Collaborative Filtering

This is my PyTorch implementation of the paper [Restricted Boltzmann Machines for Collaborative Filtering](https://www.cs.toronto.edu/~rsalakhu/papers/rbmcf.pdf) by Ruslan Salakhutdinov, Andriy Mnih, and Geoffrey Hinton (2007). In particular, I trained the RBM model with contrastive divergence on the public Movielens-1M dataset.

<img src="https://github.com/khanhnamle1994/transfer-rec/blob/master/Boltzmann-Machines-Experiments/RBM-CF-PyTorch/pics/Fig1.png" width="800">

## Requirements
```
PyTorch 1.3 & Python 3.6
Numpy
Pandas
Matplotlib
```

## Dataset
You can download the MovieLens-1M dataset from [this folder](https://github.com/khanhnamle1994/transfer-rec/tree/master/ml-1m).

## Scripts
* [rbm.py](https://github.com/khanhnamle1994/transfer-rec/blob/master/RBM-CF-PyTorch/rbm.py): This is the model script that defines the Restricted Boltzmann Machines model.
* [train.py](https://github.com/khanhnamle1994/transfer-rec/blob/master/RBM-CF-PyTorch/train.py): This is the main training script. You can simply run `python train.py` to execute it.

## Results
I obtained a reconstruction loss value of 0.403 after training the model for 200 epochs.

<img src="https://github.com/khanhnamle1994/transfer-rec/blob/master/Boltzmann-Machines-Experiments/RBM-CF-PyTorch/pics/result.png" width="650">
