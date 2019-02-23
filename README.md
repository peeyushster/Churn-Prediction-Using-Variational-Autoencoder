# Churn-Prediction-Using-Variational-Autoencoder

Introducing Convolutional Neural Networks

Convolutional neural networks (CNNs) are a specific type of neural network that have seen exceptional success in image recognition over the past five years. CNNs are unique because they make use of convolutional layers, which are neural network layers that use convolutions. Convolution is an operation in which a filter function is applied to a signal function to produce a third related function.

Convolution has been extremely useful in computer vision for decades. In this context, both the signal function and filter function are matrices. When certain filter matrices are convolved over an input image matrix, interesting results such as edge detection are produced. In convolutional neural networks, each convolutional layer contains at least one filter. In deep networks, there may be hundreds of different filters. These filters are updated as the network trains.

Although the majority of work with CNNs has been in the field of image recognition, they are an excellent fit for the problem of churn prediction and prevention as well. First, they work well for temporal data – the convolution operation has been used extensively in fields heavily based in time series, such as signal processing. Traditional machine learning models struggle to model and leverage temporal information directly. By using CNNs, we can represent each user as a time series of behavioral events, rather than an aggregation over an arbitrary window. Typically when predicting user churn we have at our disposal a time series of events.

In addition to their suitability for time series, CNNs are significantly more interpretable than other neural network architectures. In fact, the convolutional filters in the network are often described as “feature extractors”, as they identify the most important features to pull from an input before making a prediction. After a model has been trained, the filters can be studied to understand what features they are looking for. Examples of trained filters from an image recognition model are shown below. The network learns to extract the features that are most unique to the different classes it needs to identify.

