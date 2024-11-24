# Deep-Adaptive-Portfolio-Management(DAPM)
This repo serves to replicate the paper __A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem__
located in https://arxiv.org/abs/1706.10059

The __DAPM__ model utilizes Deep Deterministic Policy Gradient to solve the Portfolio Management Problem in the Kraken Exchange

This repo is originally created for Reinforcement Learning Project at Columbia University

__Note__
- The authors Zhengyao Jiang have actually published their code for the paper under the repo pgportfolio (policy gradient portfolio) which is a modification of the original paper
- Their implementation uses keras and tensorflow.
- This is different than my implementation which uses pytorch and gpu and data gathering is done asynchronously.
- Market that is used is Kraken Exchange

Tools Used:
- Python 3.11
- Pytorch
- aiohttp
