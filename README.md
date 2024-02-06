# mnist-autoencoders
Auto Encoders are a special type of Neural neworks architecture that can be utilized for various applications like simple compression of data(basic auto-encoder), de-noising of data(de-noising auto-encoder) and also generating new samples (Generative AI) of data similar to our dataset(Variational auto-encoders VAEs).

Here, I used the Fashion MNIST and Handwritten-digits MNIST data to implement the above mentioned applications of Auto-Encoders.

### Basic-AutoEncoder
Compression and Reconstruction

<img width="473" alt="image" src="https://github.com/tusharparimi/mnist-autoencoders/assets/93556280/897633d1-96ab-42c7-a4b7-d84ec39143de">

### De-Noising
Noise is intentionally added to the data but the model is trained to get the original de-noised image.

<img width="467" alt="image" src="https://github.com/tusharparimi/mnist-autoencoders/assets/93556280/c3d5f618-8bb5-4235-aa86-0dd698e7f775">

### Variational Auto-Encoder
Generate new samples from the end-to-end model by just getting a sample from the latent-space of the trained VAE.

- Generative results from VAE after 10th epoch

<img width="176" alt="image" src="https://github.com/tusharparimi/mnist-autoencoders/assets/93556280/12464d9c-d14d-4868-82f3-32750f4ca7da">

- The latent-space of the trained VAE

<img width="341" alt="image" src="https://github.com/tusharparimi/mnist-autoencoders/assets/93556280/8262143b-46f7-4ea1-89bc-1b2bd44d7d3b">

We can see a nice continuous space representing the distribution from one number to another.
