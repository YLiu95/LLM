# LLM

Building with Instruction-Tuned LLMs: A Step-by-Step Guide

https://www.youtube.com/live/eTieetk2dSw?feature=share

## Colab local runtime setup commands

pip install --upgrade jupyter_http_over_ws>=0.0.7 && jupyter serverextension enable --py jupyter_http_over_ws

jupyter notebook --NotebookApp.allow_origin='https://colab.research.google.com' --port=8888 --NotebookApp.port_retries=0


## CUDA setup notes

### version requirements check logical flow:
tensorflow/tensorflow_gpu -> Python -> CUDA, cuDNN -> visual studio -> NVIDIA GPU Driver

### installation flow:
Python -> NVIDIA GPU Driver -> visual studio 2019 -> CUDA -> cuDNN -> tensorflow/tensorflow_gpu

### version checking:
The version of the CUDA Toolkit can be checked by running `nvcc -V` in a Command Prompt window.

### installation guides
Tensorflow guide for latest version:

https://www.tensorflow.org/install/pip

Tensorflow guide for windows:

https://www.tensorflow.org/install/source_windows

NVIDIA support matrix:

https://docs.nvidia.com/deeplearning/cudnn/support-matrix/index.html#abstract

cuDNN installation guide:

https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html#install-windows

### installation pages:
NVIDIA drivers installation page:

https://www.nvidia.com/Download/index.aspx?lang=en-us

CUDA installation page:

https://developer.nvidia.com/cuda-toolkit-archive

cuDNN installation page:

https://developer.nvidia.com/cudnn 
