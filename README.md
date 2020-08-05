# DeepDream
Visualising the hallucinations of a DNN

# DeepDream in TensorFlow

DeepDream is a **computer vision** algorithm which produces psychedelic images by enhancing patterns in existing images using a deep neural network. It works by performing **gradient ascent** with regard to a particular neuron so that that neuron becomes more confident of its classification as it alters the image. This helps to visualise what a network has learned, but more importantly the images it produces are awesome.

DeepDream was invented by Google, applied to the Inception network developed for ImageNet in 2014. The original algorithm is in Caffe. This repo is a TensorFlow implementation. It is, essentailly, exactly the same as the [TensorFlow guide](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/deepdream/deepdream.ipynb). Run it on Google Colab with the Tesla K80 GPU.
## References
* [Original Implementation in Caffe](https://github.com/google/deepdream/blob/master/dream.ipynb)
* [TensorFlow Tutorial](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/deepdream/deepdream.ipynb) (Refer for code)
* [Wikipedia on DeepDream](https://en.wikipedia.org/wiki/DeepDream)
* [Inception TensorFlow Code](https://github.com/tensorflow/models/tree/master/inception) 
* [A Nice Explanation of DeepDream](http://www.kpkaiser.com/machine-learning/diving-deeper-into-deep-dreams/)
* [A Nice Video on DeepDream](https://www.youtube.com/watch?v=MrBzgvUNr4w) 

