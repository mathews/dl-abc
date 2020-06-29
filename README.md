
# Deep Learning Basic

## choosing activation fuction
1. While logistic sigmoid neurons are more bi-ologically plausible than hyperbolic tangent neurons, the latter work better for train-ing multi-layer neural networks. [Deep Sparse Rectifier Neural Networks](http://proceedings.mlr.press/v15/glorot11a/glorot11a.pdf) 
2. [tanh vs ReLU](https://www.zhihu.com/question/61265076/answer/1136216727)

## average pooling
1. this blog gives a clear explanation, [Global average pooling--<Network In Network>](https://zhuanlan.zhihu.com/p/37683646)
2. [alexisbcook's professional explanation](https://alexisbcook.github.io/2017/global-average-pooling-layers-for-object-localization/)
3. [an explanation of average pooling with tensorflow codes](https://adventuresinmachinelearning.com/global-average-pooling-convolutional-neural-networks/)
4. [What are Max Pooling, Average Pooling, Global Max Pooling and Global Average Pooling?](https://www.machinecurve.com/index.php/2020/01/30/what-are-max-pooling-average-pooling-global-max-pooling-and-global-average-pooling/)


## Batch Normalization
1. [Batch Normalization: Accelerating Deep Network Training byReducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167.pdf)

2. [深入理解Batch Normalization批标准化](https://www.cnblogs.com/guoyaohua/p/8724433.html)

## droupout
1. dropout layer is used to overcome overfitting, refer to:[Improving neural networks by preventing co-adaptation of feature detectors](https://arxiv.org/pdf/1207.0580.pdf) by Hinton

## Sample/Shuffle
1. In pytorch, the use of WeightedRandomSampler makes the learning more smoothly quicker  but the test dataset cannot be used with WeightedRandomSampler(TODO why ) 
 Note: shuffe should be False when using WeightedRandomSampler  

## Attension
1. [Attension in Neural Networks](https://buomsoo-kim.github.io/attention/2020/01/01/Attention-mechanism-1.md/)
2. [Attention-mechanism](https://blog.floydhub.com/attention-mechanism/)
3. [Attention based model 是什么，它解决了什么问题？](https://www.zhihu.com/question/36591394)

# Time Series forecasting

## Time Series in General
1. [Financial Time Series Forecasting with Deep Learning -ASystematic Literature Review- 2005-2019](https://arxiv.org/abs/1911.13288)
2. [Comparison between DeepESNs and gated RNNs on multivariate time-series prediction](https://arxiv.org/abs/1812.11527)
3. [Multivariate Temporal Convolutional Network--A Deep Neural Networks Approach for Multivariate Time Series Forecasting](https://www.mdpi.com/2079-9292/8/8/876/pdf)

## LTSM
1. [LSTM-MSNet: Leveraging Forecasts on Sets of Related Time Series with Multiple Seasonal Patterns](https://arxiv.org/abs/1909.04293)
2. [Tensorized LSTM with Adaptive Shared Memory for Learning Trends in Multivariate Time Series](https://www.semanticscholar.org/paper/Tensorized-LSTM-with-Adaptive-Shared-Memory-for-in-Xu-Cheng/e058959c717fd68674f3df02d7bf2627ff815a56)
3. [DSANet: Dual Self-Attention Network for Multivariate Time Series Forecasting](https://dl.acm.org/doi/pdf/10.1145/3357384.3358132)



## Dataset

1. [public bicycle sharing data](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
