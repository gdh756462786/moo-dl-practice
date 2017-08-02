# Conditional GAN on MNIST

## Reference
http://wiseodd.github.io/techblog/2016/12/24/conditional-gan-tensorflow/

## Network at a glance

| **Generator**, **Discriminator** |
| --- |
| ![N](./assets/network_structure.png) |

### Training Losses

| tensorflow | pytorch |
| --- | --- |
| ![](./assets/losses_tf.png) | ![](./assets/losses_pytorch.png) |

### Generated samples via epochs

| epochs | tensorflow | pytorch |
| --- | --- | --- |
| 0 | ![](./assets/epoch_0_tf.png) | ![](./assets/epoch_0_pytorch.png) |
| 9 | ![](./assets/epoch_9_tf.png) | ![](./assets/epoch_9_pytorch.png) |
| 19 | ![](./assets/epoch_19_tf.png) | ![](./assets/epoch_19_pytorch.png) |
| 29 | ![](./assets/epoch_29_tf.png) | ![](./assets/epoch_29_pytorch.png) |
|  | ![](./assets/by_epochs_tf.gif) | ![](./assets/by_epochs_pytorch.gif) |

<!-- ## Training result 
Generated images on training

![by-epochs](./assets/cGAN-MNIST-result-by-epoch.PNG)

## Generator result
Generated images on final generator. Keeping the style (fix latent z-vector input to G)

![by-styles](./assets/cGAN-MNIST-result-by-style.PNG) -->
