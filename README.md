In this project I applied a Generative Adversarial Network (GAN) to generate images of cats based on some training samples.
 The referenced architecture, DCGAN, was from a paper titled “UNSUPERVISED REPRESENTATION LEARNING WITH DEEP CONVOLUTIONAL
 GENERATIVE ADVERSARIAL NETWORKS”. The training was done on approximately 4600 images of size 64x64, the generated images 
were impressive and were really close to the real ones.

Another method referenced from the paper "FCC-GAN: A Fully Connected and Convolutional Net Architecture for GANs" was 
applied and gave similar results. An important note to take into consideration was that adding average pooling layers 
in the discriminator did not produce good results, and no features resembling cats were caught. So, I only implemented 
fully connected layers at the start of the generator and at the end of the discriminator.
