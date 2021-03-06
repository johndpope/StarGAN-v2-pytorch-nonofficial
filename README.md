## StarGANv2 - Not Official PyTorch Implementation

**\*\*\*\*\* StarGAN v2 official implementation will be available soon at https://github.com/clovaai/stargan-v2 \*\*\*\*\***

# Caution!
Now, my implementation do not work well...  
The implementation of models is same as the original ones, maybe.
So, if you help me, please check the training loop in  `solver.py` .



## Dependencies
* [Python 3.6+](https://www.continuum.io/downloads)
* [PyTorch 0.4.0+](http://pytorch.org/)

# Usage
1. Please download the Animal Faces-HQ dataset (AFHQ). And please move root.
```bash
bash scritpts/download_afhq.sh afhq
```
2. `bash scripts/train_starganv2.sh`

# Generated results.
+ 2000 iterations.
<p><img src="./imgs/2000-images_running.jpg"/></p> 


+ 10000 iterations.
<p><img src="./imgs/10000-images_running.jpg"/></p> 


## Citation
If you find this work useful for your research, please cite official [paper](https://arxiv.org/abs/1912.01865):

> **StarGAN v2: Diverse Image Synthesis for Multiple Domains**<br>
> Yunjey Choi*, Youngjung Uh*, Jaejun Yoo*, Jung-Woo Ha<sup>1,2</sup>    <br/>
> Clova AI Research, NAVER Corp. (* indicates equal contribution) <br>
> https://arxiv.org/abs/1912.01865 <br>

```
@article{choi2019starganv2,
  title={StarGAN v2: Diverse Image Synthesis for Multiple Domains},
  author={Yunjey Choi and Youngjung Uh and Jaejun Yoo and Jung-Woo Ha},
  journal={arXiv preprint arXiv:1912.01865},
  year={2019}
}
```

## Acknowledgements
This repository is based on [stargan official repository](https://github.com/yunjey/stargan).
Thanks.
