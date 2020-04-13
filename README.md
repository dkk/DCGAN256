# DCGAN256

A DCGAN used to train a hand generator that outputs 256 x 256 RGB images using the 11K hands Dataset.

For more details, see the [jupyter notebook](Hand%20Generator.ipynb).

# Environment

The jupyter notebook was implemented to run in Google Colab, but it would be easy to change it to use a local or remote instance instead.

# Result

The following GIF shows the output of the model in about the first 1000 epochs:

![](hands_out.gif)

# References

Losely based on

1. [DCGAN256 by t0nberryking](https://github.com/t0nberryking/DCGAN256)
1. [DCGAN256 by manicman1999](https://github.com/manicman1999/GAN256) 
1. [DCGAN image generator by gsurma](https://github.com/gsurma/image_generator)
1. [Tensorflow DCGAN](https://www.tensorflow.org/tutorials/generative/dcgan)
1. [Tensorflow Image Preprocessing](https://keras.io/preprocessing/image/)
1. [Dataset](https://sites.google.com/view/11khands): Mahmoud Afifi, "11K Hands: Gender recognition and biometric identification using a large dataset of hand images." Multimedia Tools and Applications, 2019.
1. [Medium: 10 Lessons I Learned Training GANs for one Year](https://towardsdatascience.com/10-lessons-i-learned-training-generative-adversarial-networks-gans-for-a-year-c9071159628)
1. [How to Train a GAN? Tips and tricks to make GANs work](https://github.com/soumith/ganhacks)
1. [Medium - GAN — Ways to improve GAN performance](https://towardsdatascience.com/gan-ways-to-improve-gan-performance-acf37f9f59b)
1. [Medium - Generating High-Resolution Images Using Deep Autoregressive Models](https://towardsdatascience.com/generating-high-resolution-images-using-autoregressive-models-3683f9af0db4)
