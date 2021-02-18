# Stock Prediction AI - Replication Work

This Repo is a try to replicate version of the [original repository](https://github.com/borisbanushev/stockpredictionai) by [Boris Banushev](https://github.com/borisbanushev). I try my best to replicate the same result with fully working project. PRs are welcomed.

Notebook File: [notebook.ipynb](./notebook.ipynb)

## Replicated topics

1. [x] Introduction
2. [x] Acknowledgement
3. The Data
   1. Correlated assets
   2. [x] Technical indicators
   3. Fundamental analysis
      1. Bidirectional Embedding Representations from Transformers - BERT
   4. [x] Fourier transforms for trend analysis
   5. [x] ARIMA as a feature
   6. Statistical checks
      1. Heteroskedasticity, multicollinearity, serial correlation
   7. Feature Engineering
      1. Feature importance with XGBoost
   8. Extracting high-level features with Stacked Autoencoders
      1. Activation function - GELU (Gaussian Error)
      2. Eigen portfolio with PCA
   9. Deep Unsupervised Learning for anomaly detection in derivatives pricing
4. Generative Adversarial Network (GAN)
   1. Why GAN for stock market prediction?
   2. Metropolis-Hastings GAN and Wasserstein GAN
      1. Metropolis-Hastings GAN
      2. Wasserstein GAN
   3. [x] <!-- markdownlint-capture -->
   4. The Generator - One layer RNN
      1. LSTM or GRU
      2. The LSTM architecture
      3. Learning rate scheduler
      4. How to prevent overfitting and the bias-variance trade-off
      5. Custom weights initializers and custom loss metric
   5. The Discriminator - One Dimentional CNN
      1. Why CNN as a discriminator?
      2. The CNN Architecture
   6. Hyperparameters
5. Hyperparameters optimization
   1. Reinforcement learning for hyperparameters optimization
      1. Reinforcement Learning Theory
         1. Rainbow
         2. PPO
      2. Further work on Reinforcement learning
   2. Bayesian optimization
      1. Gaussian process
6. The result
