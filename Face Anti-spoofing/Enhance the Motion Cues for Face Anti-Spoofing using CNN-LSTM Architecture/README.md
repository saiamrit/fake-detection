## Enhance the Motion Cues for Face Anti-Spoofing using CNN-LSTM Architecture

- A CNN-LSTM model is proposed to learn temporal features and make use of motion cues in video frames for anti spoofing.
- As a preprocessing step, eulerian motion magnification is used to enhance the facial expressions exhibited.
- To ensure generalisation, a confusion loss layer is created to balance learning level of the CNN and LSTM.
- Pre trained VGG-Face trained on 2.6M images is used to initialise parameters.The final FC layers are removed from the top of the VGG and are fed into an LSTM network
- The LSTM network uses an attention mechanism that helps the network decide which frames to pay attention to.
- Datasets used - MSU MSFD, Replay-Attack
