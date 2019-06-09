## FaceSpoof Buster: a Presentation Attack Detector Based on Intrinsic Image Properties and Deep Learning

- A new face anti-spoofing method is proposed that combines intrinsic image properties(saliency,depth and illumination maps) and features extracted using DCNNs.
- First Intrinsic properties map are extracted from the video frames, then ResNet is used a feature extractor to encode features from the earlier feature maps.
- These features are then classified using an SVM classifier which gives confidence scores to frames. These scores are finally combined with information from the earlier extracted feature maps and classified using a new SVM classifier.
- Datasets used - Replay-Attack, CASIA-FASD, NUAA Photograph Imposter Dataset.
