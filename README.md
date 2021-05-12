# TF2_DeepLearning_GenerativeModel
Here are some code examples of generative models, which are implemented with Tensorflow 2.4.0, results are shown as below: 

## Neural Style Transfer
| content image | style image | style transfer without variation loss | style transfer with variation loss|
|:-------------:|:-----------:|:-------------------------------------:|:--------------------------------:|
|![style_transfer](img/hamster.jpg | width=200)|![style_transfer](img/style%20transfer/candy.jpg)|![style_transfer](result/style%20transfer/img_without_vl.jpg)|![style_transfer](result/style%20transfer/img_with_vl.jpg)|

## Deep Dream
<div class="table_div">

| original image | dreamt image | dreamt image with octave | dreamt image with scaling tiled and octave|
|:--------------:|:------------:|:------------------------:|:--------------------------------:|
|![deep_dream](img/hamster.jpg)|![deep_dream](result/deep%20dream/deep_dream.jpg)|![deep_dream](result/deep%20dream/deep_dream_octave.jpg)|![deep_dream](result/deep%20dream/deep_dream_tiled.jpg)|
</div>

## GAN
| DCGAN | WGAN | WGAN_GP |
|:-----:|:----:|:-------:|
|![GAN](result/DCGAN_CelebA/final%20result/image_epoch_%20500.png)|![GAN](result/WGAN_CelebA/final%20result/image_epoch_%20500.png)|![GAN](result/WGAN_GP_CelebA/final%20result/image_epoch_%20500.png)|

## Pix2Pix
| Input Images  | Predicted Image |
|:-------------:|:---------------:|
|![Pix2Pix](result/Pix2Pix/input_img_1.jpg)|![Pix2Pix](result/Pix2Pix/pred_img_1.jpg)
|![Pix2Pix](result/Pix2Pix/input_img_2.jpg)|![Pix2Pix](result/Pix2Pix/pred_img_2.jpg)
|![Pix2Pix](result/Pix2Pix/input_img_3.jpg)|![Pix2Pix](result/Pix2Pix/pred_img_3.jpg)

## Main References
* **Neural Style Transfer**
  * https://www.tensorflow.org/tutorials/generative/style_transfer

* **Deep Dream**
  * https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html
  * https://www.tensorflow.org/tutorials/generative/deepdream

* **GAN**
  * https://medium.com/coinmonks/celebrity-face-generation-using-gans-tensorflow-implementation-eaa2001eef86
  * https://nthu-datalab.github.io/ml/labs/14-2_GAN/14-2_GAN.html

* **Pix2Pix**
  * https://www.tensorflow.org/tutorials/generative/pix2pix
