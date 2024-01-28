Here I dived into AutoEncoders world , we have 3 trials...
- I noised the Encoder input and ask the AE to encode the noised image then decode it and of course without the noise.
- I noised the Encoder output and ask the Decoder to decode the embedded image with the noise removed.
- I noised the images then used PCA to work as an Encoder then ask the Decoder to learn how to decode images without noise.  

About datasets we used 525 Birds species dataset.