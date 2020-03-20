## Learning Deep models for face anti spoofing - binary or auxiliary supervision [[PDF](https://arxiv.org/pdf/1803.11097)]

### Authors - Yaojie Liu, Amin Jourabloo, Xiaoming Liu

#### Published  - Computer Vision and Pattern Recognition (CVPR'18), 2018 (exhibit @CVPR Demo) 

**Description** 
- Most methods formulate anti  spoofing as a binary classification problem.
- They focus on the importance of auxiliary supervision to guide the learning towards generalisable and discriminative cues.
- CNN - RNN model is learnt to estimate face deepth with pixel wise supervision and estimate rPPG signals with sequence wise supervision.
- Depth estimate and rPPG are fused to distinguish live vs spoof.
- CNNs extract features which may not be very reliable to distinguish a real face from a spoof one, some auxiliary information can be acquired based on key difference between a  live and spoof face based on 2 perspectives : spatial and temporal.
- Spatial perspective includes depth information and from the temporal perspective, rPPG signals can be extracted from live faces only.
- rPPG - The rhythmic flow of arterial blood, results in periodic variation of skin color which are quantified to temporal signal for analysis. This method of remotely measuring heart heart rate from live videos is remote photoplethysmography(rPPG).

**Dataset used** - SiW, OULU , CASIA-MFSD, Replay - Attack

**Evaluation Metric used** - APCER, BPCER, ACER and HTER

**Type** - Temporal and Deep feature based
