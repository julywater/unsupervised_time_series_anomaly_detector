# unsupervised time series anomaly detector
1 train bi-directional LSTM auto encoder with normal timeseries only
2 pass a time series to the autoencoder, for an abnormal time series with a different pattern the reconstruction error
will be larger. We can use the reconstruction error to identify an anomaly.