## Learning Generalized Deep Feature Representation for Face Anti-Spoofing

In this paper, we propose a novel framework
leveraging the advantages of the representational ability of deep
learning and domain generalization for face spoofing detection.
In particular, the generalized deep feature representation is
achieved by taking both spatial and temporal information into
consideration, and a 3D convolutional neural network architecture tailored for the spatial-temporal input is proposed. The
network is first initialized by training with augmented facial
samples based on cross-entropy loss and further enhanced with
a specifically designed generalization loss, which coherently
serves as the regularization term. The training samples from
different domains can seamlessly work together for learning
the generalized feature representation by manipulating their
feature distribution distances. We evaluate the proposed framework with different experimental setups using various databases.
Experimental results indicate that our method can learn more
discriminative and generalized information compared with the
state-of-the-art methods.

- we apply a 3D CNN network which take both spatial and temporal information into consideration with a specifically designed data augmentation method for face spoofing detection.
- To further improve the generalization performance, we employ a generalization regularization by minimizing the Maximum Mean Discrepancy distance among different domains.
- We conduct extensive experimental analysis on four different datasets as well as our proposed cross-camera based protocol. The results show that our proposed framework can achieve significantly better performance compared with other state-of-the-art methods.
