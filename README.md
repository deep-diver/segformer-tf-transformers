# Usage of TensorFlow based SegFormer in 🤗 transformers

This repository demonstrates how to use TensorFlow based SegFormer model [1] in 🤗 `transformers` package with Jupyter Notebook and Gradio application which is hosted on 🤗 Spaces.

SegFormer achieves good performance on various high-resolution semantic segmentation datasets along with better efficiency.

_One of the objectives of this repository is to allow TensorFlow users train high-quality semantic segmentation models that benefit from
higher resolutions._

## Notice

As of 07/14/2022, the TensorFlow based SegFormer model is [under Pull Request](https://github.com/huggingface/transformers/pull/17910), so you should install `transformers` from source. In particular, you should checkout `tf-segformer` branch from [this repository](https://github.com/sayakpaul/transformers/tree/tf-segformer). The instruction how to install it from source is as follows:

```shell
$ git clone https://github.com/sayakpaul/transformers

$ cd transformers
$ git checkout tf-segformer

$ pip install -e . 
```

However, once the Pull Request is merged, you will no longer need to install `transformers` from source, and this notice will be removed.

## About the notebooks

* [`notebooks/TFSegFormer_Inference.ipynb`]: Shows how to run inference with a pre-trained semantic segmentation model. 
* [`notebooks/TFSegFormer_Finetune.ipynb`]: Shows how to fine-tune a pre-trained SegFormer model.

## Demo on Hugging Face Space

Visit [this link](https://huggingface.co/spaces/chansung/segformer-tf-transformers).

## References

[1] SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers; Enze Xie, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, Ping Luo; https://arxiv.org/abs/2105.15203 (2021).