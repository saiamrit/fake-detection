---
# FACE SPOOFING

Acquiring someone else’s privileges and access rights by using substitutes to an authorised human face.

Some spoofing attacks are :

* **Print Attack** : A 2D picture of the face is used. It is either printed or displayed on a digital device. The printed picture is bended and moved in different directions to simulate facial motions.

* **Replay / Video Attack** : A looped video of the victim’s face is used to fool the system. This method makes facial expressions and motion look more natural. It’s a more sophisticated way of attack than print method.

* **3D mask attack** :  A facial mask of the victim is used to fool the system. This is even more sophisticated than playing a video because in addition to facial expressions and motion, it can also fool special protection tools like depth sensors.

### Anti-Spoofing State-of-the-art techniques

- **Face Liveness Test** : It is based on analysis of how alive the test face is. It is done by checking eye movements like blinking and face movements.

- **Contextual Information techniques** : By investigating image surrounding, we can identify if there is a printed image or digital device.

- **User Interaction** :  The recognition system interacts with the user and asks to perform specific tasks lie moving the face or blinking and identifying if the test face does that in real time.

#### Anti-spoofing Datasets

| Datasets          | \# of subj. / \# of sess. | Links                                                        | Year | Spoof attacks attacks | Publish Time |
| ----------------- | :-----------------------: | ------------------------------------------------------------ | ---- | --------------------- | ------------ |
| **NUAA**          |           15/3            | [Download](http://parnec.nuaa.edu.cn/xtan/data/nuaaimposterdb.html) | 2010 | **Print**             | 2010         |
| **CASIA-MFSD**    |           50/3            | Download(link failed)                                        | 2012 | **Print, Replay**     | 2012         |
| **Replay-Attack** |           50/1            | [Download](https://www.idiap.ch/dataset/replayattack)        | 2012 | **Print, 2 Replay**   | 2012         |
| **MSU-MFSD**      |           35/1            | [Download](https://www.cse.msu.edu/rgroups/biometrics/Publications/Databases/MSUMobileFaceSpoofing/index.htm) | 2015 | **Print, 2 Replay**   | 2015         |
| **MSU-USSA**      |          1140/1           | [Download](http://biometrics.cse.msu.edu/Publications/Databases/MSU_USSA/) | 2016 | **2 Print, 6 Replay** | 2016         |
| **Oulu-NPU**      |           55/3            | [Download](https://sites.google.com/site/oulunpudatabase/)   | 2017 | **2 Print, 6 Replay** | 2017         |
| **Siw**           |           165/4           | [Download](http://cvlab.cse.msu.edu/spoof-in-the-wild-siw-face-anti-spoofing-database.html) | 2018 | **2 Print, 4 Replay** | 2018         |

## Face Anti-Spoofing Papers

- Jianwei Yang, Zhen Lei, Stan Z. Li .[Learn Convolutional Neural Network for Face Anti-Spoofing](https://arxiv.org/pdf/1408.05601) .[J] arXiv preprint arXiv:1408.05601.
- Zinelabidine Boulkenafet, Jukka Komulainen, Abdenour Hadid .[face anti-spoofing based on color texture analysis](https://arxiv.org/pdf/1511.06316) .[J] arXiv preprint arXiv:1511.06316.
- Yaojie Liu, Amin Jourabloo, Xiaoming Liu .[Learning Deep Models for Face Anti-Spoofing: Binary or Auxiliary  Supervision](https://arxiv.org/pdf/1803.11097) .[J] arXiv preprint arXiv:1803.11097.
- Amin Jourabloo, Yaojie Liu, Xiaoming Liu .[Face De-Spoofing: Anti-Spoofing via Noise Modeling](https://arxiv.org/pdf/1807.09968) .[J] arXiv preprint arXiv:1807.09968.
- Jiaxu Zuo, Tom Gedeon, Zhenyue Qin .[Your Eyes Say You're Lying: An Eye Movement Pattern Analysis for Face Familiarity and Deceptive Cognition](https://arxiv.org/pdf/1811.03401) .[J] arXiv preprint arXiv:1811.03401.
- Zezheng Wang, Chenxu Zhao, Yunxiao Qin, Qiusheng Zhou, Zhen Lei .[Exploiting temporal and depth information for multi-frame face anti-spoofing](https://arxiv.org/pdf/1811.05118) .[J] arXiv preprint arXiv:1811.05118.
- Wei Hu, Gusi Te, Ju He, Dong Chen, Zongming Guo .[Exploring Hypergraph Representation on Face Anti-spoofing Beyond 2D Attacks](https://arxiv.org/pdf/1811.11594) .[J] arXiv preprint arXiv:1811.11594.
- Qing Song, Yingqi Wu, Lu Yang .[Attacks on State-of-the-Art Face Recognition using Attentional Adversarial Attack Generative Network](https://arxiv.org/pdf/1811.12026) .[J] arXiv preprint arXiv:1811.12026.
- 【Dataset】Shifeng Zhang, Xiaobo Wang, Ajian Liu, Chenxu Zhao, Jun Wan, Sergio Escalera, Hailin Shi, Zezheng Wang, Stan Z. Li .[CASIA-SURF: A Dataset and Benchmark for Large-scale Multi-modal Face Anti-spoofing](https://arxiv.org/pdf/1812.00408) .[J] arXiv preprint arXiv:1812.00408.
- Jianzhu Guo, Xiangyu Zhu, Jinchuan Xiao, Zhen Lei, Genxun Wan, Stan Z. Li .[Improving Face Anti-Spoofing by 3D Virtual Synthesis](https://arxiv.org/pdf/1901.00488) .[J] arXiv preprint arXiv:1901.00488.
- Xiaoguang Tu, Jian Zhao, Mei Xie, Guodong Du, Hengsheng Zhang, Jianshu Li, Zheng Ma, Jiashi Feng .[Learning Generalizable and Identity-Discriminative Representations for Face Anti-Spoofing](https://arxiv.org/pdf/1901.05602) .[J] arXiv preprint arXiv:1901.05602.
- Xiaoguang Tu, Hengsheng Zhang, Mei Xie, Yao Luo, Yuefei Zhang, Zheng Ma .[Deep Transfer Across Domains for Face Anti-spoofing](https://arxiv.org/pdf/1901.05633) .[J] arXiv preprint arXiv:1901.05633.
- Xiaoguang Tu, Hengsheng Zhang, Mei Xie, Yao Luo, Yuefei Zhang, Zheng Ma .[Enhance the Motion Cues for Face Anti-Spoofing using CNN-LSTM Architecture](https://arxiv.org/pdf/1901.05635) .[J] arXiv preprint arXiv:1901.05635.
- Rodrigo Bresan, Allan Pinto, Anderson Rocha, Carlos Beluzo, Tiago Carvalho .[FaceSpoof Buster: a Presentation Attack Detector Based on Intrinsic Image Properties and Deep Learning](https://arxiv.org/pdf/1902.02845) .[J] arXiv preprint arXiv:1902.02845.
- Yao Liu, Ying Tai, Jilin Li, Shouhong Ding, Chengjie Wang, Feiyue Huang, Dongyang Li, Wenshuai Qi, Rongrong Ji .[Aurora Guard: Real-Time Face Anti-Spoofing via Light Reflection](https://arxiv.org/pdf/1902.10311) .[J] arXiv preprint arXiv:1902.10311.
- Zuheng Ming, Junshi Xia, Muhammad Muzzamil Luqman, Jean-Christophe Burie, Kaixing Zhao .[FaceLiveNet+: A Holistic Networks For Face Authentication Based On Dynamic Multi-task Convolutional Neural Networks](https://arxiv.org/pdf/1902.11179) .[J] arXiv preprint arXiv:1902.11179.
- Huiling Hao, Mingtao Pei .[Face Liveness Detection Based on Client Identity Using Siamese Network](https://arxiv.org/pdf/1903.05369) .[J] arXiv preprint arXiv:1903.05369.
- Lei Li, Zhaoqiang Xia, Xiaoyue Jiang, Yupeng Ma, Fabio Roli, Xiaoyi Feng .[3D Face Mask Presentation Attack Detection Based on Intrinsic Image Analysis](https://arxiv.org/pdf/1903.11303) .[J] arXiv preprint arXiv:1903.11303.
- Yaojie Liu, Joel Stehouwer, Amin Jourabloo, Xiaoming Liu .[Deep Tree Learning for Zero-shot Face Anti-Spoofing](https://arxiv.org/pdf/1904.02860) .[J] arXiv preprint arXiv:1904.02860.
- Yinpeng Dong, Hang Su, Baoyuan Wu, Zhifeng Li, Wei Liu, Tong Zhang, Jun Zhu .[Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/pdf/1904.04433) .[J] arXiv preprint arXiv:1904.04433.
- Artur Costa-Pazo, David Jimenez-Cabello, Esteban Vazquez-Fernandez, Jose L. Alba-Castro, Roberto J. López-Sastre .[Generalized Presentation Attack Detection: a face anti-spoofing evaluation proposal](https://arxiv.org/pdf/1904.06213) .[J] arXiv preprint arXiv:1904.06213.
- Daniel Pérez-Cabo, David Jiménez-Cabello, Artur Costa-Pazo, Roberto J. López-Sastre .[Deep Anomaly Detection for Generalized Face Anti-Spoofing](https://arxiv.org/pdf/1904.08241) .[J] arXiv preprint arXiv:1904.08241.
- Peng Zhang, Fuhao Zou, Zhiwen Wu, Nengli Dai, Skarpness Mark, Michael Fu, Juan Zhao, Kai Li .[FeatherNets: Convolutional Neural Networks as Light as Feather for Face Anti-spoofing](https://arxiv.org/pdf/1904.09290) .[J] arXiv preprint arXiv:1904.09290.
- Chenxu Zhao, Yunxiao Qin, Zezheng Wang, Tianyu Fu, Hailin Shi .[Meta Anti-spoofing: Learning to Learn in Face Anti-spoofing](https://arxiv.org/pdf/1904.12490) .[J] arXiv preprint arXiv:1904.12490.
