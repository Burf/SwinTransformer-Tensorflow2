# SwinTransformer for Tensorflow2

This is an implementation of "SwinTransformer V1 and V2" on Keras and Tensorflow.

The implementation is based on papers[[1](https://arxiv.org/abs/2103.14030v2), [2](https://arxiv.org/abs/2111.09883)] and official implementation[[3](https://github.com/microsoft/Swin-Transformer)].

## Model

- Model
  * SwinTransformer-Tiny
  * SwinTransformer-Small
  * SwinTransformer-Base
  * SwinTransformer-Large
  * SwinTransformerV2-Tiny
  * SwinTransformerV2-Small
  * SwinTransformerV2-Base
  * SwinTransformerV2-Large
- Pre-trained weight(The pre-trained weights are converted from [official weight](https://github.com/microsoft/Swin-Transformer).)
  * imagenet 1k (Tiny, Small, Base)
  * imagenet 22k (Base, Large)
  * imagenet 22kto1k (Base, Large)

## Requirements

- Python 3
- tensorflow 2
- torch 1.1▲ (Use the pre-trained weights)

## Reference

 1. Swin Transformer: Hierarchical Vision Transformer using Shifted Windows,
    Ze Liu, Yutong Lin, Yue Cao, Han Hu, Yixuan Wei, Zheng Zhang, Stephen Lin, Baining Guo,
    https://arxiv.org/abs/2103.14030v2
    
 2. Swin Transformer V2: Scaling Up Capacity and Resolution,
    Ze Liu, Han Hu, Yutong Lin, Zhuliang Yao, Zhenda Xie, Yixuan Wei, Jia Ning, Yue Cao, Zheng Zhang, Li Dong, Furu Wei, Baining Guo,
    https://arxiv.org/abs/2111.09883
   
 3. Swin Transformer,
    microsoft,
    https://github.com/microsoft/Swin-Transformer
   
## Contributor

 * Hyungjin Kim(flslzk@gmail.com)
