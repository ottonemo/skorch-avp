### Alien vs. Predator using skorch

This is an adoption of the code used in a [side-by-side comparison of PyTorch and Keras by deepsense.ai](https://deepsense.ai/keras-vs-pytorch-avp-transfer-learning/).

Since PyTorch and Keras have very different levels of abstraction,
this example uses [skorch](https://github.com/dnouri/skorch)
instead which still offers the flexibility of PyTorch but offers
an abstraction level that is similar to Keras.

#### Running

The simplest way is to use `conda` to install the dependencies:

    conda env create -f environment.yml -n avp
    source activate avp
    pip install git+https://github.com/dnouri/skorch
    jupyter-notebook skorch-resnet50.ipynb

After that you should be able to navigate to the notebook URL.
