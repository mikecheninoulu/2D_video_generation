# 2D Video Generation Papers

## STOTA methods

***-video level processing***

**[1] First Order Motion Model for Image Animation**
- intro: NeurIPS 2019, solid work, baseline, Aliaksandr
- dataset: VoxCeleb, Tai-Chi-HD, Fashion-Videos, MGif 
- paper: [https://papers.nips.cc/paper/2019/file/31c0b36aef265d9221af80872ceb62f9-Paper.pdf](https://papers.nips.cc/paper/2019/file/31c0b36aef265d9221af80872ceb62f9-Paper.pdf)
- github: [https://github.com/AliaksandrSiarohin/first-order-model](https://github.com/AliaksandrSiarohin/first-order-model)

**[2] DwNet: Dense warp-based network for pose-guided human video generation**
- intro: BMVC 2019, densepose, baseline, easy to reproduce
- dataset: taichi, fashion
- arxiv: [https://arxiv.org/abs/1910.09139](https://arxiv.org/abs/1910.09139)
- code: [https://github.com/zpolina/dwnet](https://github.com/zpolina/dwnet)

**[3] Video-to-Video Synthesis**
- intro: NeurIPS 2018, NVIDIA, baseline, hard to train
- arxiv: [https://arxiv.org/abs/1808.06601](https://arxiv.org/abs/1808.06601)
- github: [https://github.com/NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)

**[4] Few-shot Video-to-Video Synthesis**
- intro: NeurIPS 2019, NVIDIA, code hard, has bug..
- paper: [https://arxiv.org/abs/1910.12713](https://arxiv.org/abs/1910.12713)
- github: [https://github.com/NVlabs/few-shot-vid2vid](https://github.com/NVlabs/few-shot-vid2vid)
- project: https://nvlabs.github.io/few-shot-vid2vid/

**[5] One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing**
- intro: 2020 arxiv, NVIDIA, code hard
- paper: [https://nvlabs.github.io/face-vid2vid/main.pdf](https://nvlabs.github.io/face-vid2vid/main.pdf)
- github: [https://github.com/NVlabs/face-vid2vid](https://github.com/NVlabs/face-vid2vid)
- project: https://nvlabs.github.io/face-vid2vid/

**[6] Adaptive Compact Attention For Few-shot Video-to-video Translation**
- intro: 2020 arxiv
- paper: [https://arxiv.org/abs/2011.14695](https://arxiv.org/abs/2011.14695)
- project: https://www.youtube.com/watch?v=1OCFbUrypKQ


**[7] Single-Shot Freestyle Dance Reenactment**
- intro: 2020 arxiv, results are impressive, Facebook
- paper: [https://arxiv.org/abs/2012.01158v1](https://arxiv.org/abs/2012.01158v1)
- project: https://www.youtube.com/watch?v=Rq5U5Abj47I&feature=youtu.be


***-frame level processing***

**[1] XingGAN for Person Image Generation**
- intro: ECCV 2020, person image
- DATASET: Market-1501, DeepFashion
- paper: [https://arxiv.org/abs/2007.09278](https://arxiv.org/abs/2007.09278)
- github: [https://github.com/Ha0Tang/XingGAN](https://github.com/Ha0Tang/XingGAN)

**[2] Bipartite Graph Reasoning GANs for Person Image Generation**
- intro: BMVC 2020 Oral, person image
- DATASET: Market-1501, DeepFashion
- paper: [https://arxiv.org/abs/2008.04381](https://arxiv.org/abs/2008.04381)
- github: [https://github.com/Ha0Tang/BiGraphGAN](https://github.com/Ha0Tang/BiGraphGAN)

**[3] High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs**
- intro: CVPR 2018, father of vid2vid
- DATASET: Cityscapes
- paper: [https://arxiv.org/pdf/1711.11585.pdf](https://arxiv.org/pdf/1711.11585.pdf)
- github: [https://github.com/NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD)

**[4] Reposing Humans by Warping 3D Features**
- intro: CVPR 2020 workshop, 3D component
- DATASET: iPER, deep fashion
- paper: [https://arxiv.org/pdf/2006.04898.pdf](https://arxiv.org/pdf/2006.04898.pdf)
- github: [https://github.com/MKnoche/warp3d_reposing](https://github.com/MKnoche/warp3d_reposing)

**Other summary about 2D pose image transfer**
- https://github.com/Zhangjinso/Awesome-pose-transfer


***-Still image animation***

**[1] Animating Pictures with Eulerian Motion Fields**
- intro: arxiv 2020, code coming soon
- paper: [https://eulerian.cs.washington.edu/animating_pictures_2020.pdf](https://eulerian.cs.washington.edu/animating_pictures_2020.pdf)
- project: https://eulerian.cs.washington.edu/

**[2] SinGAN: Learning a Generative Model from a Single Natural Image**
- intro: ICCV 2019, Best paper
- paper: [https://arxiv.org/pdf/1905.01164.pdf](https://arxiv.org/pdf/1905.01164.pdf)
- code: https://github.com/tamarott/SinGAN


## DATASET

**[1] Voxceleb1,2**
- intro: face dataset, with audio
- processing: https://github.com/AliaksandrSiarohin/video-preprocessing#preprocessing-voxceleb-dataset
- project: [https://www.robots.ox.ac.uk/~vgg/data/voxceleb/](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

**[2] Taichi**
- intro: taichi action
- project: [https://vision.cs.ubc.ca/datasets/fashion/](https://vision.cs.ubc.ca/datasets/fashion/)
- source: https://github.com/AliaksandrSiarohin/first-order-model/blob/master/data/taichi-loading/README.md

**[3] Nemo face dataset**
- intro: face dataset
- processing: https://github.com/AliaksandrSiarohin/video-preprocessing#preprocessing-nemo-dataset
- source: https://www.uva-nemo.org/

**[4] Moving GIF**
- intro: moving gif relatively simple
- source: [https://yadi.sk/d/5VdqLARizmnj3Q](https://yadi.sk/d/5VdqLARizmnj3Q)

**[5] BAIR robot pushing dataset**
- intro: robot arm moving dataset
- project: [http://rail.eecs.berkeley.edu/models/savp/tables/bair_all/](http://rail.eecs.berkeley.edu/models/savp/tables/bair_all/)

**[6] Deep fasion**
- intro: person with cloth, dressing dataset 
- project: [http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
- prepare: https://github.com/Ha0Tang/SelectionGAN/tree/master/person_transfer#data-preperation

**[7] Market-1501 Dataset**
- intro: person on the streest, orinigally ReID dataset, 
- project: [https://deepai.org/dataset/market-1501](https://deepai.org/dataset/market-1501)
- prepare: https://github.com/Ha0Tang/SelectionGAN/tree/master/person_transfer#data-preperation



## 3D generation

**[1] : We are More than Our Joints: Predicting how 3D Bodies Move**
- intro: maxplanc, 3D action generation
- paper: [https://arxiv.org/pdf/2012.00619.pdf](https://arxiv.org/pdf/2012.00619.pdf)
- code: https://yz-cnsdqz.github.io/MOJO/MOJO.html

**[2] : Point2Skeleton: Learning Skeletal Representations from Point Clouds**
- intro: point to skeleton
- paper: [https://arxiv.org/pdf/2012.00230.pdf](https://arxiv.org/pdf/2012.00230.pdf)


## Video Generation Theory Without Code

**[1] : DIVERSE VIDEO GENERATION USING A GAUSSIAN PROCESS TRIGGER**
- intro: ICLR 2021, score 6,6,6,
- project: [https://openreview.net/pdf?id=Qm7R_SdqTpT](https://openreview.net/pdf?id=Qm7R_SdqTpT)

**[2] : DISENTANGLED RECURRENT WASSERSTEIN AUTOENCODER**
- intro: ICLR 2021, score 7,7,7
- project: [https://openreview.net/pdf?id=O7ms4LFdsX](https://openreview.net/pdf?id=O7ms4LFdsX)

**[3] : A Good Image Generator Is What You Need for High-Resolution Video Synthesis**
- intro: ICLR 2021, score 8,6,8,6
- project: [https://openreview.net/pdf?id=6puCSjH3hwA](https://openreview.net/pdf?id=6puCSjH3hwA)

| Updated: 2020/12/03|
| :---------: |

