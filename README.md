# A Fully Convolutional Neural Network for Speech Enhancement

Tensorflow 2.0 implementation of the paper [A Fully Convolutional Neural Network for Speech Enhancement](https://pdfs.semanticscholar.org/9ed8/e2f6c338f4e0d1ab0d8e6ab8b836ea66ae95.pdf)

This code is a standalone extension of [this code] (https://raw.githubusercontent.com/daitan-innovation/cnn-audio-denoiser/)
Which in turn is based on this blog post: [Practical Deep Learning Audio Denoising](https://medium.com/better-programming/practical-deep-learning-audio-denoising-79c1c1aea299)

## Dataset

Although a partial part of the dataset is said to be available on the above
github repo, it isn't there.  Therefore you need to download the two datasets
below. 

- [Mozilla Common Voice](https://voice.mozilla.org/)
- [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html)

You can then use ```create_dataset.py``` script to create the TFRecord files. 

You will then need to update the paths of these datasets in ```default_config.py```.

## Training

Use train.py to train an audio denoiser

## Testing

Use test.py to test the audio denoiser with one track

## Requirements

You need to install tensorflow and keras and some other bits and pieces.  It
would be best to follow the guidance on installing TF on it's website (i.e. use
within a virtual environment)

