# FViT Implementation

## Environment Setup
Please set up the environment following `env.yaml` by using conda. After that, please clone https://github.com/openai/guided-diffusion and put it in the same directory as this repo. Note that we leverage the pre trained diffusion model of `256x256 diffusion (not class conditional): 256x256_diffusion_uncond.pt`. 


## Playing with examples
We provide some examples in `fig` folder. You can run the corresponding experiments to see different explanation results in the `fvit-demo.ipynb` notebook.

### Ours

![image-20230126150942852](https://s2.loli.net/2023/01/27/Z8fzDcptxs4LUB3.png)

### VTA

![image-20230126151007281](https://s2.loli.net/2023/01/27/gCKXEsMIrPbFS86.png)

## References

Our code implementation is based on the following awesome material:

1. https://github.com/jacobgil/vit-explain
2. https://jacobgil.github.io/deeplearning/vision-transformer-explainability
3. https://arxiv.org/abs/2005.00928
4. https://github.com/hila-chefer/Transformer-Explainability
5. https://github.com/openai/guided-diffusion

## Citation

All rights belong to the authors. Suggest cite:

@inproceedings{huimproving,title={Improving Interpretation Faithfulness for Vision Transformers},author={Hu, Lijie and Liu, Yixin and Liu, Ninghao and Huai, Mengdi and Sun, Lichao and Wang, Di},booktitle={Forty-first International Conference on Machine Learning}}
