# Usage of TensorFlow based SegFormer in 🤗 transformers

![](https://i.ibb.co/StPyy3z/segformer-space.png)

This repository demonstrates how to use TensorFlow based SegFormer model [1] in 🤗 `transformers` package with Jupyter Notebook and Gradio application which is hosted on [🤗 Spaces](https://huggingface.co/spaces/chansung/segformer-tf-transformers).

SegFormer achieves good performance on various high-resolution semantic segmentation datasets along with better efficiency.

_One of the objectives of this repository is to allow TensorFlow users train high-quality semantic segmentation models that benefit from
higher resolutions._

## Notice

Since the TensorFlow variant of SegFormer hasn't been included in a `transformers` release yet you need to install it from the source:

```shell
pip install git+https://github.com/huggingface/transformers
```

## About the notebooks

* [`notebooks/TFSegFormer_Inference.ipynb`](https://github.com/deep-diver/segformer-tf-transformers/blob/main/notebooks/TFSegFormer_Inference.ipynb): Shows how to run inference with a pre-trained semantic segmentation model. 
* [`notebooks/TFSegFormer_Finetune.ipynb`](https://github.com/deep-diver/segformer-tf-transformers/blob/main/notebooks/TFSegFormer_Finetune.ipynb): Shows how to fine-tune a pre-trained SegFormer model.

## Demo on Hugging Face Space

Visit [this link](https://huggingface.co/spaces/chansung/segformer-tf-transformers).

## References

[1] SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers; Enze Xie, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, Ping Luo; https://arxiv.org/abs/2105.15203 (2021).

## Acknowledgements

Thanks to the [ML-GDE program (ML Developer Programs team)](https://developers.google.com/programs/experts/) for providing GCP credits that we used for experimentation. 
