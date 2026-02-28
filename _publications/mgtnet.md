---
title: "Image-Guided Human Reconstruction via Multi-Scale Graph Transformation Networks"
collection: publications
category: conferences
permalink: /publication/mgtnet
date: 2021-01-01
venue: "IEEE Transactions on Image Processing (TIP), 2021"
redirect_to: "https://cic.tju.edu.cn/faculty/likun/projects/MGTnet/index.html"
---

Kun Li, Hao Wen, Qiao Feng, Yuxiang Zhang, Xiongzheng Li, **Jing Huang**, Cunkuan Yuan, Yu-Kun Lai, Yebin Liu  

---

## Abstract

3D human reconstruction from a single image is a challenging problem. Existing methods have difficulties to infer 3D clothed human models with consistent topologies for various poses. In this paper, we propose an efficient and effective method using a hierarchical graph transformation network. To deal with large deformations and avoid distorted geometries, rather than using Euclidean coordinates directly, 3D human shapes are represented by a vertex-based deformation representation that effectively encodes the deformation and copes well with large deformations. To infer a 3D human mesh consistent with the input real image, we also use a perspective projection layer to incorporate perceptual image features into the deformation representation. Our model is easy to train and fast to converge with short test time. Besides, we present the D^2Human (Dynamic Detailed Human) dataset, including variously posed 3D human meshes with consistent topologies and rich geometry details, together with the captured color images and SMPL parameters, which is useful for training and evaluation of deep frameworks, particularly for graph neural networks. Experimental results demonstrate that our method achieves more plausible and complete 3D human reconstruction from a single image, compared with several state-of-the-art methods.

---

## Links

- [Project Page](https://cic.tju.edu.cn/faculty/likun/projects/MGTnet/index.html)
- [Paper PDF](https://cic.tju.edu.cn/faculty/likun/projects/MGTnet/assets/MGTnet.pdf)
- [Code and Dataset](https://github.com/1020244018/MGTnet)

---

## Citation

```bibtex
@article{MGTnet,
  author = {Kun Li and Hao Wen and Qiao Feng and Yuxiang Zhang and Xiongzheng Li and Jing Huang and Cunkuan Yuan and Yu-Kun Lai and Yebin Liu},
  title = {Image-Guided Human Reconstruction via Multi-Scale Graph Transformation Networks},
  booktitle = {IEEE Transactions on Image Processing (IEEE TIP)},
  year = {2021}
}
```
