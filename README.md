The GPU enhanced Neuronal Networks (GeNN) software ecosystem [1,2] provides an environment for GPU accelerated spiking neural network simulations. Spiking neural network models are described using a simple model description API through which variables, parameters and C-like code snippets that describe various aspects of the model elements can be specified, e.g. neuron and synapse update equations or learning dynamics. Model elements of neuron and synapse types are combined into neuron and synapse populations to form a full spiking neural network model.
GeNN takes the model description and generates optimised code to simulate the model. Current code-generation backends include CUDA for NVIDIA GPUs and OpenCL for other accelerators.
In recent years the GeNN ecosystem has expanded rapidly with a Python wrapper, PyNN interface, the OpenCL backend and, most recently, mlGeNN [3], an interface to machine learning workflows. Furthermore, large strides have been made with concurrent initialisation methods [4], improved recording of results [5] and “procedural connectivity” [6].
In this software showcase we will give a brief overview of GeNN and then walk through the development of an insect mushroom body model capable of classifying MNIST digits. The aim of this session is to allow attendants to get a flavour of the capabilities of GeNN, of the user experience and, in principle, enable them to start using it for their own work.

## Video
* The video accompanying this tutorial is available on [YouTube](https://youtu.be/e9gHXuNDw8Q?t=5)

## Installation
* Checkout/download [master branch of GeNN](https://github.com/genn-team/genn)
* [Install PyGeNN](https://github.com/genn-team/genn/blob/master/pygenn/README.md)

## Additional Downloads
* [Training images](https://sussex.box.com/s/7aa3a7wuriif6nx8qdmg6soaq45robl5)
* [Training labels](https://sussex.box.com/s/lpqcbdftut8567p6l2sf41hs1nxfu9dp)
* [Testing images](https://sussex.box.com/s/32qyms9k2ophhgp0iivcmfw730ml4l7i)
* [Testing labels](https://sussex.box.com/s/3hdkgm5mx1dyh32q9k22eej01ukadtdm)
* [Pre-trained weights](https://sussex.box.com/s/uw9zcpft1d188dsjgu7kncem8d8jfye3)


## References
1. E. Yavuz, J. Turner and T. Nowotny (2016). GeNN: a code generation framework for accelerated brain simulations. Scientific Reports 6:18854. https://doi.org/10.1038/srep18854
2. GeNN, https://github.com/genn-team/genn
3. mlGeNN, https://github.com/genn-team/ml_genn
4. J. C. Knight, T. Nowotny (2018) GPUs outperform current HPC and neuromorphic solutions in terms of speed and energy when simulating a highly-connected cortical model. Front Neurosci 12:941. https://doi.org/10.3389/fnins.2018.00941
5. J. C. Knight, A. Komissariv, T. Nowotny (2021) PyGeNN: A Python Library for GPU-Enhanced Neural Networks. Frontiers in Neuroinformatics 15: 10. https://doi.org/10.3389/fninf.2021.659005
6. J. C. Knight and T. Nowotny (2021) Larger GPU-accelerated brain simulations with procedural connectivity. Nat Comput Sci 1(2): 136-42. https://doi.org/10.1038/s43588-020-00022-7
