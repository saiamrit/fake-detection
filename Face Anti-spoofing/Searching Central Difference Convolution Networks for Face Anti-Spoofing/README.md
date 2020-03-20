## Searching Central Difference Convolution Networks for Face Anti-Spoofing [[PDF](https://arxiv.org/pdf/2003.04092.pdf)]

### Authors - Zitong Yu, Chenxu Zhao, Zezheng Wang, Yunxiao Qin, Zhuo Su, Xiaobai Li, Feng Zhou, Guoying Zhao

#### Published  - Computer Vision and Pattern Recognition (CVPR), 2020

**Description** 

- Most state-of-the-art FAS methods :

  - rely on stacked convolutions and expert-designed network, which is weak in describing detailed fine-grained information and easily being ineffective when the environment varies (e.g., different 		illumination), and 
  - prefer to use long sequence as input to extract dynamic features, making them difficult to deploy into scenarios which need quick response

- This paper proposes a novel convolution operator called Central Difference Convolution (CDC), which is suitable for FAS task due to its remarkable representation ability for invariant fine-grained features in diverse environments. Without introducing any extra parameters, CDC can replace the vanilla convolution and plug and play in existing neural networks to form Central Difference Convolutional Networks (CDCN) with more robust modeling capacity.

- They propose CDCN++, an extended version of CDCN, consisting of the searched backbone network and Multiscale Attention Fusion Module (MAFM) for aggregating the multi-level CDC features effectively.

- State of the art results is reported on 6 benchmark datasets with both intra as well as cross-dataset testing.

- **Dataset used** - OULU-NPU, SiW, CASIA-MFSD, Replay-Attack, MSU-MFSD and SiW-M

- **Evaluation Metric used** - APCER, BPCER, ACER, HTER and AUC
