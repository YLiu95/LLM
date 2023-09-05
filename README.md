# LLM
Large language models


https://www.youtube.com/live/eTieetk2dSw?feature=share

## Colab local runtime setup commands

pip install --upgrade jupyter_http_over_ws>=0.0.7 && jupyter serverextension enable --py jupyter_http_over_ws

jupyter notebook --NotebookApp.allow_origin='https://colab.research.google.com' --port=8888 --NotebookApp.port_retries=0


## CUDA setup notes

### requirements check logical flow:
tensorflow-2.13.0 -> CUDA 11.8 -> visual studio 2019

### installation flow:
NVIDIA Driver >=452.39 -> visual studio 2019 -> CUDA 11.8 -> cuDNN 8.6 -> tensorflow-2.13.0

### version checking:
The version of the CUDA Toolkit can be checked by running `nvcc -V` in a Command Prompt window.

### installation guides
Tensorflow guide:

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
