# online-retail-dist-prediction
> Dataset: [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

## Model Architecture
Model consists of CNN, LSTM and FFN with Softmax. Idea of CNN part is from [WaveNet](https://arxiv.org/pdf/1609.03499.pdf). LSTM is basically many-to-one architecture and uses the last output of LSTM.

## Reference
- [Foret, P., Kleiner, A., Mobahi, H., & Neyshabur, B. (2020). Sharpness-aware minimization for efficiently improving generalization. arXiv preprint arXiv:2010.01412.](https://arxiv.org/abs/2010.01412)
- [Oord, A. V. D., Dieleman, S., Zen, H., Simonyan, K., Vinyals, O., Graves, A., ... & Kavukcuoglu, K. (2016). Wavenet: A generative model for raw audio. arXiv preprint arXiv:1609.03499.](https://arxiv.org/abs/1609.03499)
