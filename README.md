This is a try to generate new molecules by learning latent space structure using VAE
I used as the decoder output a batch of idependent categorical distribution describing each 37 possible character in each position of the 50 chars long smile string.
I used a standard normal distribution as prior with a small weight(0.01) and without computing the exact KL divergence formula. Otherwise the result will not be satisfactory
I've correctly generated 24 new molecules using 10000 samples from the prior
