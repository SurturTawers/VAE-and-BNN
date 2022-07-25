# VAE-and-BNN
Imlementation of a VAE (Variational AutoEncoder) and a BNN (Bayesian Neural Network) in Tensorflow Keras. (The VAE doesn't work :( )

## Data
Data consists of four sets of images:
* Science 
* Template (subtracted to science)
* Difference (result of science minus template)
* SNR(Signal to Noise Ratio, pixel noise estimation of difference).
\
\
Each set has 5026 21x21 real/artifact images of HiTS (High Cadence Transient Survey), divided in 4026 images for training and 1000 images for testing.
