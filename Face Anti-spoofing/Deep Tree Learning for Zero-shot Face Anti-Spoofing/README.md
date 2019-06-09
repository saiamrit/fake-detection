## Deep Tree Learning for Zero-shot Face Anti-Spoofing [CVPR 2019 orals]

- A Zero-Shot Face Anti-spoofing method(ZSFA) is proposed.The ZSFA model works on 13 types of spoofing attack and a new database is created named Spoof In the Wild with Multiple attack types(SiW-M)
- Assuming there are both homogenous features in different spoof types and distinct features in same spoof types, a Deep Tree Network is proposed which learns to partition data in an unsupervised manner.
- At each tree node, partition is performed along the direction of largest data variation and at the leaf level, data is clustered to various sub groups independently.During testing, a sample data is routed to the most suitable leaf and is classified.
- The tree approach is proposed to unsupervisely learn semantic embedding for known spoof attack.During testing, the unknown attacks are projected to the learnt embedding to find the closest attributes.
- Each tree node of DTN consists of Convolutional Residual Units(CRU) and Tree Routing Unit(TRU) while leaf nodes consists of CRU and Supervised Feature Learning modules(SFL)
- Datasets Used - Spoof in the Wild with Multiple attack types(SiW-M)
