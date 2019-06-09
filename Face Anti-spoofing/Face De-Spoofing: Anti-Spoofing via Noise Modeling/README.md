## Face De-Spoofing: Anti-Spoofing via Noise Modeling

- A spoof image is being decomposed into a spoof noise and live face and then utilising the spoof noise for classification.
- The extracted spoof signal also gives a visualisation which helps to understand the spoof noise added by each spoof medium.
- In this paper they try to open the black box assumption of a spoof image by considering a spoof image to be a re-rendering of a live image with some special noise added by the spoof medium and environment.
- This paper considers anti-spoofing as a de-X problem like de-noising or de-blurring and call it de-spoofing.A spoof image is decomposed to a live image and a spoof noise signal.
- The network has 3 parts : DS Net(De-spoofing), DQ Net(Discriminative Quality), VQ Net(Visual Quality)
    * The DQ Net is responsible to estimate noise pattern from the input image.
    * DQ Net is a state of art anti-spoofing network which ensures the generated image can be considered live.
    * The VQ Net is a GAN which ensures that the generated real face is photorealistic.
- Datasets used : Oulu-NPU, CASIA-MFSD and Replay-Attack

