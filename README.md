# network-intrusion-anomaly-detection-challenge
• Data Preprocessing: Collected 1 million rows &amp; 40 features network data, dropped uninformative columns/one-hot encoding/standardization/separated normal instances in training &amp; test set as autoencoder is trained to reconstruct normal  

• Data Modelling: Built autoencoder, reconstructed errors for normal &amp; attacks, detected attacks by prediction MSE and selected 0.995 quantile of reconstruction error for normal class and achieved 99% accuracy with 36% Cohen kappa score
