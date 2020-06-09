# Image Classification (CIFAR-10) on Kaggle
- Built Wide ResNet model to achieve image classification and get score 0.95 which is top 10 %
ranking.
- Used Tesla K80 GPU to increase computing performance.
- Conducted image augmentation, performed normalization for the three RGB channels which ensure
the certainty of the output.
- Tuned Parameters, use Nesterov momentum, weight decay and batchnorm layer to increase the
convergence speed, reduce overfitting and prevent gradient explosion.