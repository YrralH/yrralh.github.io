---
title: "DyCrowd: Towards Dynamic Crowd Reconstruction from a Large-scene Video"
collection: publications
category: conferences
permalink: /publication/dycrowd
date: 2025-08-18
venue: "IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025"
# paperurl: "https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/imgs/DyCrowd.pdf"
codeurl: "https://github.com/KHB1698/DyCrowd"
redirect_to: "https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/index.html"
# optional:
# doi: "10.1109/TPAMI.2025.3600465"
---

Hao Wen, Hongbo Kang, Jian Ma, **Jing Huang**, Yuanwang Yang, Haozhe Lin, Yu-Kun Lai, Kun Li<sup>*</sup>  

---

## Links

- [Project Page](https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/index.html) :contentReference[oaicite:2]{index=2}
- [Paper PDF (project site)](https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/imgs/DyCrowd.pdf) :contentReference[oaicite:3]{index=3}
- [ArXiv](https://arxiv.org/abs/2508.12644) :contentReference[oaicite:4]{index=4}
- [Supplementary PDF](https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/imgs/Supplementary.pdf) :contentReference[oaicite:5]{index=5}
- [Code](https://github.com/KHB1698/DyCrowd) :contentReference[oaicite:6]{index=6}

---

## Abstract

3D reconstruction of dynamic crowds in large scenes has become increasingly important for applications such as city surveillance and crowd analysis. However, current works attempt to reconstruct 3D crowds from a static image, causing a lack of temporal consistency and inability to alleviate the typical impact caused by occlusions. In this paper, we propose **DyCrowd**, the first framework for spatio-temporally consistent 3D reconstruction of hundreds of individuals' poses, positions and shapes from a large-scene video. We design a coarse-to-fine group-guided motion optimization strategy for occlusion-robust crowd reconstruction in large scenes. To address temporal instability and severe occlusions, we further incorporate a VAE-based human motion prior along with a segment-level group-guided optimization. The core of our strategy leverages collective crowd behavior to address long-term dynamic occlusions. By jointly optimizing the motion sequences of individuals with similar motion segments and combining this with the proposed Asynchronous Motion Consistency (AMC) loss, we enable high-quality unoccluded motion segments to guide the motion recovery of occluded ones, ensuring robust and plausible motion recovery even in the presence of temporal desynchronization and rhythmic inconsistencies. Additionally, we contribute a virtual benchmark dataset, **VirtualCrowd**, for evaluating dynamic crowd reconstruction from large-scene videos. :contentReference[oaicite:1]{index=1}

---

## Citation

Wen, H., Kang, H., Ma, J., Huang, J., Yang, Y., Lin, H., Lai, Y.-K., & Li, K.  
“DyCrowd: Towards Dynamic Crowd Reconstruction from a Large-scene Video.”  
*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 2025. (DOI: 10.1109/TPAMI.2025.3600465) :contentReference[oaicite:7]{index=7}

```bibtex
@article{wen2025dycrowd,
  title   = {DyCrowd: Towards Dynamic Crowd Reconstruction from a Large-scene Video},
  author  = {Wen, Hao and Kang, Hongbo and Ma, Jian and Huang, Jing and Yang, Yuanwang and Lin, Haozhe and Lai, Yu-Kun and Li, Kun},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year    = {2025},
  doi     = {10.1109/TPAMI.2025.3600465},
  url     = {https://arxiv.org/abs/2508.12644}
}