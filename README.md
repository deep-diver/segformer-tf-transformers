# Usage of TensorFlow based SegFormer in 🤗 transformers

This repository demonstrates how to use TensorFlow based SegFormer model in 🤗 transformers package with Jupyter Notebook and Gradio application which eventually will be hosted in 🤗 Hub's Space.

## Notice

As of 07/01/2022, the TensorFlow based SegFormer model is under Pull Request, so you should install `transformers` from source. In particular, you should checkout `tf-segformer` branch from [this repository](https://github.com/sayakpaul/transformers/tree/tf-segformer). The instruction how to install it from source is as follows:

```shell
$ git clone https://github.com/sayakpaul/transformers

$ cd transformers
$ git checkout tf-segformer

$ pip install -e . 
```

However, once the Pull Request is merged, you will no longer need to install `transformers` from source, and this notice will be removed.