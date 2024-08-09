# topo_gan
Train a 1D DCGAN based on StyleGAN (https://arxiv.org/abs/1812.04948) on 2D heightmaps of the European Alps from the ASTER Global Digital Elevation Model V003 (https://www.earthdata.nasa.gov/) following the basic TensorFlow DCGAN tutorial (https://www.tensorflow.org/tutorials/generative/dcgan).

Heightmap dataset: Alps (N44E006-N48E015).

The latest snapshot was taken after 68 epochs, and much longer training is likely required (my GPU does not like this though). However, some heightmaps start to be acceptable:

![Last training snapshot]([http://url/to/img.png](https://github.com/erikweiand/topo_gan/blob/main/last_training_output.png))

Further visualizations of single 256x256 tiles using Blender 3D will follow.
