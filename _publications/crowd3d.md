---
title: "Crowd3D: Towards Hundreds of People Reconstruction from a Single Image"
collection: publications
category: conferences
permalink: /publication/crowd3d
excerpt: "CVPR 2023"
date: 2023-06-01
venue: "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2023)"
paperurl: "asserts/main_paper.pdf"
codeurl: "https://github.com/1020244018/Crowd3D"
---

**Hao Wen**<sup>†</sup>, **Jing Huang**<sup>†</sup>, Huili Cui, Haozhe Lin, Yu-Kun Lai, Lu Fang, Kun Li<sup>*</sup>  
<sup>†</sup> Equal contribution. <sup>*</sup> Corresponding author.

---

## Abstract

Image-based multi-person reconstruction in wide-field large scenes is critical for crowd analysis and security alert.
However, existing methods cannot deal with large scenes containing hundreds of people, which encounter the challenges
of large number of people, large variations in human scale, and complex spatial distribution.

We propose **Crowd3D**, the first framework to reconstruct the **3D poses, shapes and locations of hundreds of people**
with **global consistency** from a single large-scene image. The core of our approach is to convert the problem of complex
crowd localization into pixel localization with the help of our newly defined concept, **Human-scene Virtual Interaction Point (HVIP)**.
To reconstruct the crowd with global consistency, we propose a progressive reconstruction network based on HVIP by pre-estimating
a scene-level camera and a ground plane. To deal with a large number of persons and various human sizes, we also design an adaptive
human-centric cropping scheme. Besides, we contribute a benchmark dataset, **LargeCrowd**, for crowd reconstruction in a large scene.

---

## Links

- [Paper](/assets/docs/crowd3d/main_paper.pdf)
- [Supplemental](/assets/docs/crowd3d/supp.pdf)
- [Code](https://github.com/1020244018/Crowd3D)

---

## Figures

<img src="/images/crowd3d/figure2_v60.png" width="900" alt="Overview of Crowd3D framework."/>
<p><em>Overview of Crowd3D framework.</em></p>



---

## Citation

```bibtex
@inproceedings{Crowd3D,
  author = {Wen, Hao and Huang, Jing and Cui, Huili and Lin, Haozhe and Lai, Yu-Kun and Fang, Lu and Li, Kun},
  title = {Crowd3D: Towards Hundreds of People Reconstruction from a Single Image},
  booktitle = {CVPR},
  year = {2023},
  pages = {8937--8946}
}
```