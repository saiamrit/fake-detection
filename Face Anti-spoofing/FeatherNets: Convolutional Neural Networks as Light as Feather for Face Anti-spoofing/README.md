## FeatherNets: Convolutional Neural Networks as Light as Feather for Face Anti-spoofing

- To address the issues of computational and storage costs, a lightweight CNN architecture is proposed.FeatherNets have a thin CNN stem so computational cost is less.
- A new architecture (named as Streaming Module) is proposed, which has better performance in terms of accuracy than the Global Average Pooling (GAP) approach.
- A new fusion classifier architecture is proposed which assembles and cascades several models learned from multimodal data, i.e., the depth and IR data, to generate better prediction accuracy than single depth models.
- 3 special types of blocks are designed and combination of blocks is used to design FeatherNet A and B architecture.
- A cascaded structure of networks is used which has 2 stages:
    - Stage 1 - An ensemble classifier, consisting of multiple models , is employed to generate the predictions. These models are trained on depth data and from several checkpoints of different networks, including FeatherNets. If the weighted average of scores from these models is near 0 or 1, input sample will be classified as fake or real respectively. Otherwise, the uncertain samples will go through the second stage.
    - FeatherNetB learned from IR data will be used to classify the uncertain samples from stage 1. The fake judgement of IR model is respected as the final result. For the real judgement, the final scores are decided by both stage 1 and IR models.
- Datasets Used - CASIA-SURF and the proposed Multi-Modal Face Dataset (MMFD)
