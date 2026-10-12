# paper-reading
My research focuses on time series forecasting and brain-inspired intelligence, so the paper I read is primarily centered around these two fields.

## Time Series Forecasting
| Method Name | Code | Source | Comment |
| ----------- | ---- | ------ | ------- |
| [LightGTS: A Lightweight General Time Series Forecasting Model](https://arxiv.org/abs/2506.06005) | [Code](https://github.com/decisionintelligence/LightGTS) | ICML 2025 | a light model, rely on know period of dataset |
| [Online time-series forecasting using spiking reservoir](https://www.sciencedirect.com/science/article/pii/S0925231222013479) | [Code]() | Neurocomputing 2023 | Transfer input to spike, and use reservoir and FORCE learning to reduce the paramaters |
## Brain-inspired Intelligence
| Method Name | Code | Source | Comment |
| ----------- | ---- | ------ | ------- |
| [Synaptic Plasticity Models and Bio-Inspired Unsupervised Deep Learning: A Survey](https://arxiv.org/abs/2307.16236) |  | CoRR 2023 | List some methods that how people use Synaptic Plasticity in DL  |
| [Unsupervised representation learning with Hebbian synaptic and structural plasticity in brain-like feedforward neural networks](https://www.sciencedirect.com/science/article/pii/S0925231225001122) |  | Neurocomputing 2025 |  Combining synaptic plasticity and structural plasticity with Bayesian neural networks |
| [Neural circuits for dynamics-based segmentation of time series](https://www.biorxiv.org/content/biorxiv/early/2021/09/29/2021.04.23.441218.full.pdf) |[Code](https://github.com/ttesileanu/bio-time-series)   | Neural computation 2022 | The method is to simulate the brain, it's not bio-inspired. Use different model to predict diff series can be took  |
| [Local plasticity rules can learn deep representations using self-supervised contrastive predictions](https://proceedings.neurips.cc/paper_files/paper/2021/hash/feade1d2047977cd0cefdafc40175a99-Abstract.html) | [Code](https://github.com/EPFL-LCN/pub-illing2021-neurips) | NeurIPS 2021 | Pure bio-inspired, it is a brilliant idea to connect the saccade and learning |
| [What Should a Neuron Aim For? Designing Local Objective Functions Based on Information Theory](https://proceedings.iclr.cc/paper_files/paper/2025/hash/87d8ed41d250c401a68f05100e0a4ef0-Abstract-Conference.html) | [Code](https://github.com/Priesemann-Group/Infomorphic_Networks) | ICLR 2025 | Take out three inputs neuron, use PID to seperate the signal |
| [Reshaping reservoirs with unsupervised Hebbian adaptation](https://www.nature.com/articles/s41467-025-67137-1) | [Code](https://doi.org/10.24433/CO.3241639.v1) | Nature Communications 2025 | Build a non-connection network first and then add or cut the connection |
| [Differentiable plasticity: training plastic neural networks with backpropagation](https://proceedings.mlr.press/v80/miconi18a.html?ref=https://githubhelp.com) | [Code](https://github.com/uber-common/differentiable-plasticity) | ICML 2018 | Simply change the BP base on stable paras add the plasiticity part make huge improvement |
