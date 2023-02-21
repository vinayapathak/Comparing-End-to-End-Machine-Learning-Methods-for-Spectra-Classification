# Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification
This study aims to develop deep learning (DL) classification frameworks for one-dimensional (1D) spectral time series. In this work, we deal with the spectra classification problem from two different perspectives, one is a general two-dimensional (2D) space segmentation problem, and the other is a common 1D time series classification problem. We focused on the two proposed classification models under these two settings, the namely the end-to-end binned Fully Connected Neural Network (FCNN) with the automatically capturing weighting factors model and the convolutional SCT attention model. Under the setting of 1D time series classification, several other end-to-end structures based on FCNN, Convolutional Neural Network (CNN), ResNets, Long Short-Term Memory (LSTM), and Transformer were explored. Finally, we evaluated and compared the performance of these classification models based on the High Energy Density (HED) spectra dataset from multiple perspectives, and further performed the feature importance analysis to explore their interpretability. The results show that all the applied models can achieve 100% classification confidence, but the models applied under the 1D time series classification setting are superior. Among them, Transformer-based methods consume the least training time (0.449 s). Our proposed convolutional Spatial-Channel-Temporal (SCT) attention model uses 1.269 s, but its self-attention mechanism performed across spatial, channel, and temporal dimensions can suppress indistinguishable features better than others, and selectively focus on obvious features with high separability.
