## Learning Generalizable and Identity-Discriminative Representations for Face Anti-Spoofing

- CNN based methods generally fail or tend to overfit in situations when the test data environment is quite different from training environment so generalisability is an important thing in such anti-spoofing model design.
- DIfferent from previous approaches where anti-spoof detection is considered a preliminary step to face recognition, the proposed method performs both tasks simultaneously. The CNN layers in both the tasks share the same parameter so the model works with high efficiency.
- A Total Pairwise Confusion(TPC) Loss  is proposed which relieves the overfitting problem of CNN based face anti-spoofing models on dataset specific spoof patterns which improves generalisability.
- The TPC loss, through the way it is formulated, tries to minimise the distribution distance between any random sample pair.
- Considering face anti-spoofing as a binary classification problem, introducing a confusion in the feature representation would make the distribution quite compact and homogenise the feature distribution.
- A Fast Domain Adaptation model is proposed which reduces domain shift in feature space and helps the model to learn more robust Presentation Attacks.
- The FDA consists of a image transformation network that creates a synthetic image from the given image and has a loss network that computes content reconstruction loss and domain reconstruction loss for the reconstructed image.So the original image x is converted to y having same content as x and domain as in the target domain image.target domain images are sampled from training data.
- Datasets used  -  CASIA-FASD, Replay-Attack, MSU-MFSD, Oulu-NPU and SiW
