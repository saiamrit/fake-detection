## Face Liveness Detection Based on Client Identity Using Siamese	Network

- A client identity information based anti-spoofing method is proposed in which unlike other anti-spoofing methods, face verification is done before detection of face liveliness and a siamese network is used.
- The siamese network is trained with 2 real or one real one fake face from the same client, so the network knows to identify 2 real faces and on every test image.
- Initially face is identified and then the real face image of the identified person is retrieved and is checked by the siamese network.
- The subnetworks of the siamese are alexnet architectures modified to fit the data.
- Datasets used - NUAA, Replay-Attack
