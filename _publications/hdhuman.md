---
title: "HDhuman: High-quality Human Novel-view Rendering from Sparse Views"
collection: publications
category: conferences
permalink: /publication/hdhuman
date: 2024-08-14
venue: "IEEE Transactions on Visualization and Computer Graphics (TVCG), 2024"
codeurl: "https://github.com/OpenTiansong/HDhuman"
---

Tiansong Zhou<sup>&dagger;</sup>, **Jing Huang**<sup>&dagger;</sup>, Tao Yu, Ruizhi Shao, Kun Li<sup>*</sup>  
<sup>&dagger;</sup> Equal contribution.

## Links

- [More Video Visualization](https://cic.tju.edu.cn/faculty/likun/projects/HDhuman/index.html)
- [Paper](/assets/docs/hdhuman/main_paper.pdf)
- [Code](https://github.com/OpenTiansong/HDhuman)

---

## Abstract

In this paper, we aim to address the challenge of novel view rendering of human performers that wear clothes with complex texture patterns using a sparse set of camera views. Although some recent works have achieved remarkable rendering quality on humans with relatively uniform textures using sparse views, the rendering quality remains limited when dealing with complex texture patterns as they are unable to recover the high-frequency geometry details that are observed in the input views. To this end, we propose HDhuman, which uses a human reconstruction network with a pixel-aligned spatial transformer and a rendering network with geometry-guided pixel-wise feature integration to achieve high-quality human reconstruction and rendering. The designed pixel-aligned spatial transformer calculates the correlations between the input views and generates human reconstruction results with high-frequency details. Based on the surface reconstruction results, the geometry-guided pixel-wise visibility reasoning provides guidance for multi-view feature integration, enabling the rendering network to render high-quality images at 2k resolution on novel views. Unlike previous neural rendering works that always need to train or fine-tune an independent network for a different scene, our method is a general framework that is able to generalize to novel subjects. Experiments show that our approach outperforms all the prior generic or specific methods on both synthetic data and real-world data.

---

## Figures

<img src="/images/hdhuman/method_recon.png" width="900" alt="Reconstruction stage."/>
<p><em>Reconstruction stage.</em></p>

<img src="/images/hdhuman/method_render.png" width="900" alt="Rendering stage."/>
<p><em>Rendering stage.</em></p>

---

## Citation

```bibtex
@article{HDhuman2024tvcg,
  author  = {Zhou, Tiansong and Huang, Jing and Yu, Tao and Shao, Ruizhi and Li, Kun},
  title   = {HDhuman: High-Quality Human Novel-View Rendering From Sparse Views},
  journal = {IEEE Transactions on Visualization and Computer Graphics},
  year    = {2024},
  volume  = {30},
  number  = {8},
  pages   = {5328--5338}
}
```
