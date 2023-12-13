# Coarse-to-Fine Amodal Segmentation with Shape Prior (C2F-Seg)

[Jianxiong Gao](https://jianxgao.github.io/), [Xuelin Qian†](https://naiq.github.io/), [Yikai Wang](https://yikai-wang.github.io/), [Tianjun Xiao†](https://tianjunxiao.com/), [Tong He](https://hetong007.github.io/), [Zheng Zhang](https://www.amazon.science/author/zheng-zhang), [Yanwei Fu](https://yanweifu.github.io/)

# Introduction
<img src='imgs/C2F-Seg_arch.png' width="100%">

C2F-Seg is a framework designed for amodal segementation. It first generates a coarse mask from the visible mask and visual features via the mask-and-predict procedure with transformers. Then this coarse amodal mask is refined with a convolutional module guided by human-imitated attention on visual features of the amodal object. The learning of visible mask is used as an auxiliary task in training, while in inference we only provide an estimation of amodal mask.

# MOViD-Amodal
You can download the dataset from this [link](https://data.dgl.ai/dataset/MOVi-Amodal/MOViD-Amodal.tar)

# Code and Checkpoints
We will release it upon passing the review of Amazon.

# Citation
If you find our paper useful for your research and applications, please cite using this BibTeX:

```
@inproceedings{gao2023coarse,
  title={Coarse-to-Fine Amodal Segmentation with Shape Prior},
  author={Gao, Jianxiong and Qian, Xuelin and Wang, Yikai and Xiao, Tianjun and He, Tong and Zhang, Zheng and Fu, Yanwei},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={1262--1271},
  year={2023}
}
```
