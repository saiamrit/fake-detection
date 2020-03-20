## Deep Anomaly Detection for Generalized Face Anti-Spoofing [[PDF](https://arxiv.org/pdf/1904.08241)]

### Authors - Daniel Pérez-Cabo, David Jiménez-Cabello, Artur Costa-Pazo, Roberto J. López-Sastre 

#### Published in - CVPR 2019 Workshop

- Recent methods  are not able to correctly generalise the face presentation attack problem because most models overfit on the training data domain and fail to give promising results on a completely different test domain.
- The Face Anti-spoofing problem is approached as an anomaly detection problem based on deep metric learning with a Triplet Focal loss using just still images.
- In deep metric based learning approaches, objective is to learn a deep model that generates a feature representation in which samples from same classes are closer in the embedding space than samples from different categories.
- The triplet loss is modified to incorporate focal attention.The triplet loss automatically up-weights hard examples by mapping euclidean distance to an exponential kernel penalising them much more than easy ones.
- A new softmax function is proposed called as metric softmax that accumulates probability distribution of each pair within a triplet to be highly separated in an euclidean space thus preventing the learning process towards binary classification.
- To make the system dynamic and adopt to new environments that doesn’t require a classifier to be trained on the learned features for decision making, the probability of being genuine is computed as the accumulated posterior probability of input sample, given two reference sets in target domain.

**Dataset used** - GRAD-GPAD framework

**Evalation metric used** - 
