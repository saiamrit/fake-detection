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

## Anti-spoofing Datasets

| Datasets                                           | Associated Paper                                             | Year Published | #subjects | #live/attack | Data modality | Spoof attacks |
| -------------------------------------------------- | ------------------------------------------------------------ | -------------- | ----------- | ---------- | ------------- | --------------- |
| [**NUAA**](http://parnec.nuaa.edu.cn/xtan/data/NUAAImposterDB.html) | [PDF](http://parnec.nuaa.edu.cn/xtan/paper/eccv10r1.pdf) | 2010 | 15 | 5105/7509 | RGB | **Print**             |
| **CASIA-MFSD**                                     | [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6199754)                                        | 2012 | 50 | 150/450 | RGB | **Print(wrapped,cut photo), Replay**     |
| [**Replay-Attack**](https://www.idiap.ch/dataset/replayattack) | [PDF](https://publications.idiap.ch/downloads/papers/2012/Chingovska_IEEEBIOSIG2012_2012.pdf)        | 2012 | 50 | 200/1000 | RGB | **Print, 2 Replay**   |
| [**MSU-MFSD**](http://biometrics.cse.msu.edu/Publications/Databases/MSUMobileFaceSpoofing/index.htm)      |[PDF](http://vipl.ict.ac.cn/uploadfile/upload/2017020711092984.pdf) | 2014 | 35 | 110/330 | RGB | **Print, 2 Replay**   |
| [**MSU-USSA**](http://biometrics.cse.msu.edu/Publications/Databases/MSU_USSA/)      | [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7487030) | 2016 | 1140 | 1140/9120 | RGB | **2 Print, 6 Replay** |
| [**Replay-Mobile**](https://www.idiap.ch/dataset/replay-mobile)      | [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7736936) | 2016 | 40 | 390/640 | RGB | **Print, 2 Replay** |
| [**Oulu-NPU**](https://sites.google.com/site/oulunpudatabase/)      |[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7961798)   | 2017 | 55 | 1980/3960 | RGB | **2 Print, 2 Replay** |
| [**Siw**](http://cvlab.cse.msu.edu/siw-spoof-in-the-wild-database.html)           | [PDF](https://arxiv.org/pdf/1803.11097.pdf) | 2018 | 165 | 1320/3300 | RGB |  **2 Print, 4 Replay** |
| [**Siw-M**](http://cvlab.cse.msu.edu/siw-m-spoof-in-the-wild-with-multiple-attacks-database.html)           | [PDF](https://arxiv.org/pdf/1904.02860.pdf) | 2018 | 493 | 660/970 | RGB | **Print, Replay,5 mask, 3 makeup, 3 Partial** |
| [**CASIS-SURF**](https://sites.google.com/qq.com/chalearnfacespoofingattackdete/dataset?authuser=0)           | [PDF](https://arxiv.org/pdf/1812.00408v3.pdf) | 2019 | 1000 | 3500/17500 | RGB/Depth/IR | **Print, Mask** |

**A detailed analysis of the various public datasets released can be found [here](https://docs.google.com/spreadsheets/d/1rH-SkrbvFpKxcUM7dcZOsyihrr30g16HFy2m1sQobGo/edit?usp=sharing)**

## Face Anti-Spoofing Papers

- Yaojie Liu, Amin Jourabloo, Xiaoming Liu [Learning Deep Models for Face Anti-Spoofing: Binary or Auxiliary  Supervision](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Learning%20Deep%20models%20for%20face%20anti%20spoofing%20-%20binary%20or%20auxiliary%20supervision)

- Amin Jourabloo, Yaojie Liu, Xiaoming Liu [Face De-Spoofing: Anti-Spoofing via Noise Modeling](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Face%20De-Spoofing:%20Anti-Spoofing%20via%20Noise%20Modeling)

- Zezheng Wang, Chenxu Zhao, Yunxiao Qin, Qiusheng Zhou, Zhen Lei [Exploiting temporal and depth information for multi-frame face anti-spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Exploiting%20temporal%20and%20depth%20information%20for%20multi-frame%20face%20anti-spoofing)

- Wei Hu, Gusi Te, Ju He, Dong Chen, Zongming Guo [Exploring Hypergraph Representation on Face Anti-spoofing Beyond 2D Attacks](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Exploring%20Hypergraph%20Representation%20on%20Face%20Anti-spoofing%20Beyond%202D%20Attacks)

- Jianzhu Guo, Xiangyu Zhu, Jinchuan Xiao, Zhen Lei, Genxun Wan, Stan Z. Li [Improving Face Anti-Spoofing by 3D Virtual Synthesis](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Improving%20Face%20Anti-Spoofing%20by%203D%20Virtual%20Synthesis)

- Xiaoguang Tu, Jian Zhao, Mei Xie, Guodong Du, Hengsheng Zhang, Jianshu Li, Zheng Ma, Jiashi Feng [Learning Generalizable and Identity-Discriminative Representations for Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Learning%20Generalizable%20and%20Identity-Discriminative%20Representations%20for%20Face%20Anti-Spoofing)

- Xiaoguang Tu, Hengsheng Zhang, Mei Xie, Yao Luo, Yuefei Zhang, Zheng Ma [Deep Transfer Across Domains for Face Anti-spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Deep%20Transfer%20Across%20Domains%20for%20Face%20Anti-spoofing)

- Xiaoguang Tu, Hengsheng Zhang, Mei Xie, Yao Luo, Yuefei Zhang, Zheng Ma [Enhance the Motion Cues for Face Anti-Spoofing using CNN-LSTM Architecture](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Enhance%20the%20Motion%20Cues%20for%20Face%20Anti-Spoofing%20using%20CNN-LSTM%20Architecture)

- Rodrigo Bresan, Allan Pinto, Anderson Rocha, Carlos Beluzo, Tiago Carvalho [FaceSpoof Buster: a Presentation Attack Detector Based on Intrinsic Image Properties and Deep Learning](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/FaceSpoof%20Buster:%20a%20Presentation%20Attack%20Detector%20Based%20on%20Intrinsic%20Image%20Properties%20and%20Deep%20Learning)

- Zuheng Ming, Junshi Xia, Muhammad Muzzamil Luqman, Jean-Christophe Burie, Kaixing Zhao [FaceLiveNet+: A Holistic Networks For Face Authentication Based On Dynamic Multi-task Convolutional Neural Networks](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/FaceLiveNet%2B:%20A%20Holistic%20Networks%20For%20Face%20Authentication%20Based%20On%20Dynamic%20Multi-task%20Convolutional%20Neural%20Networks)

- Huiling Hao, Mingtao Pei [Face Liveness Detection Based on Client Identity Using Siamese Network](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Face%20Liveness%20Detection%20Based%20on%20Client%20Identity%20Using%20Siamese%09Network)

- Yaojie Liu, Joel Stehouwer, Amin Jourabloo, Xiaoming Liu [Deep Tree Learning for Zero-shot Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Deep%20Tree%20Learning%20for%20Zero-shot%20Face%20Anti-Spoofing)

- Artur Costa-Pazo, David Jimenez-Cabello, Esteban Vazquez-Fernandez, Jose L. Alba-Castro, Roberto J. López-Sastre [Generalized Presentation Attack Detection: a face anti-spoofing evaluation proposal](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Generalized%20Presentation%20Attack%20Detection:%20a%20face%20anti-spoofing%20evaluation%20proposal)

- Daniel Pérez-Cabo, David Jiménez-Cabello, Artur Costa-Pazo, Roberto J. López-Sastre [Deep Anomaly Detection for Generalized Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Deep%20Anomaly%20Detection%20for%20Generalized%20Face%20Anti-Spoofing)

- Peng Zhang, Fuhao Zou, Zhiwen Wu, Nengli Dai, Skarpness Mark, Michael Fu, Juan Zhao, Kai Li [FeatherNets: Convolutional Neural Networks as Light as Feather for Face Anti-spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/FeatherNets:%20Convolutional%20Neural%20Networks%20as%20Light%20as%20Feather%20for%20Face%20Anti-spoofing)

- Chenxu Zhao, Yunxiao Qin, Zezheng Wang, Tianyu Fu, Hailin Shi [Meta Anti-spoofing: Learning to Learn in Face Anti-spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Learning%20Generalized%20Deep%20Feature%20Representation%20for%20Face%20Anti-Spoofing)

- Haoliang Li, Peisong He, Shiqi Wang, Anderson Rocha, Xinghao Jiang, and Alex C. Kot [Learning Generalized Deep Feature Representation for Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Learning%20Generalized%20Deep%20Feature%20Representation%20for%20Face%20Anti-Spoofing)

- Olegs Nikisins, Anjith George, Sebastien Marcel [Domain Adaptation in Multi-Channel Autoencoder based Features for Robust
Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Domain%20Adaptation%20in%20Multi-Channel%20Autoencoder%20based%20Features%20for%20Robust%20Face%20Anti-Spoofing)

- Rui Shao , Xiangyuan Lan , and Pong C. Yuen [Joint Discriminative Learning of Deep Dynamic Textures for 3D Mask Face Anti-Spoofing](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Joint%20Discriminative%20Learning%20of%20Deep%20Dynamic%20Textures%20for%203D%20Mask%20Face%20Anti-Spoofing)

- Javier Hernandez-Ortega, Julian Fierrez, Aythami Morales, Pedro Tome [Time Analysis of Pulse-based Face Anti-Spoofing in Visible and NIR](https://github.com/saiamrit/fake-detection/tree/master/Face%20Anti-spoofing/Time%20Analysis%20of%20Pulse-based%20Face%20Anti-Spoofing%20in%20Visible%20and%20NIR)
