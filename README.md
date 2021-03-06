<img src="./Dataset/rptango_logo1.png" width="264" height="70" align="left"/>

# Anomaly Detection
Anomaly Detection using LSTM autoencoders.

Anomaly detection (also outlier detection) is the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data.Typically the anomalous items will translate to some kind of problem. Anomalies are also referred to as outliers, novelties, noise, deviations and exceptions.

Three broad categories of anomaly detection techniques exist. 
- Unsupervised anomaly detection techniques detect anomalies in an unlabeled test data set under the assumption that the majority of the instances in the data set are normal by looking for instances that seem to fit least to the remainder of the data set. 
- Supervised anomaly detection techniques require a data set that has been labeled as "normal" and "abnormal" and involves training a classifier. 
- Semi-supervised anomaly detection techniques construct a model representing normal behavior from a given normal training data set, and then test the likelihood of a test instance to be generated by the learnt model.

Anomaly detection refers to the task of finding/identifying rare events/data points. Some applications include - bank fraud detection, tumor detection in medical imaging, and errors in written text.


## LSTM Autoencoders
Autoencoders Neural Networks try to learn data representation of its input. So the input of the Autoencoder is the same as the output? Not quite. Usually, we want to learn an efficient encoding that uses fewer parameters/memory.

The encoding should allow for output similar to the original input. In a sense, we’re forcing the model to learn the most important features of the data using as few parameters as possible.
