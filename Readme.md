# Reade Me

## Combining Contextual Neural Networks for Time Series Classification


Ten years ago, linear models were applied in various domains. Before application of the algorithms, several current studies extracted features presumed to represent parochial markings from the data using engineering techniques. Recently the deep learning domain offered opportunities to directly feed data into the model without any extensive hand-crafted feature engineering techniques. In this paper, the proposed framework does the feature extraction in a non-supervised (i.e. self-supervised) manner using both Contextual Long Short-Term Memory (CLSTM) and Contextual Convolutional Neural Networks (CCNN). We can then concatenate data obtained from the CLSTM and CCNN blocks, feed it into the Attention block, pass it through the Multilayer Perceptron (MLP) block, ultimately passing it through a terminal layer for classification.



![pdf](./model2.png)



