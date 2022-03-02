# SwinTransformer for Tensorflow2

This is an implementation of "SwinTransformer v1" on Keras and Tensorflow.

The implementation is based on paper[[1](https://arxiv.org/abs/2103.14030v2)] and official implementation[[2](https://github.com/microsoft/Swin-Transformer)].

## Model

- Model
  * SwinTransformer-Tiny
  * SwinTransformer-Small
  * SwinTransformer-Base
  * SwinTransformer-Large
- Pre-trained weight(The pre-trained weights are converted from [official weight](https://github.com/microsoft/Swin-Transformer).)
  * imagenet (Tiny, Small, Base)
  * imagenet_22kto1k (Base, Large)
  * imagenet_22k (Base, Large)

## Requirements

- Python 3
- tensorflow 2
- torch 1.1▲

## Reference

 1. Swin Transformer: Hierarchical Vision Transformer using Shifted Windows,
    Ze Liu, Yutong Lin, Yue Cao, Han Hu, Yixuan Wei, Zheng Zhang, Stephen Lin, Baining Guo,
    https://arxiv.org/abs/2103.14030v2
   
 2. Swin Transformer,
    microsoft,
    https://github.com/microsoft/Swin-Transformer
   
## Contributor

 * Hyungjin Kim(flslzk@gmail.com)