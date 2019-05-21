# Faceswap-Resources
Faceswap Tutorial Resources

This include two useful link

Faceswap (without GAN): 
https://github.com/deepfakes/faceswap

Faceswap_GAN:
https://github.com/shaoanlu/faceswap-GAN


**How to check the CUDA and CUDNN version?**

1. Check the CUDA version: 

Input the following command into the terminal:  
`cat /usr/local/cuda/version.txt`

The output will be like this:  
`CUDA Version 9.0.176`

Or input: 
`nvcc --version`

The output will be:  
`nvcc: NVIDIA (R) Cuda compiler driver`  
`Copyright (c) 2005-2017 NVIDIA Corporation`  
`Built on Fri_Sep__1_21:08:03_CDT_2017`  
`Cuda compilation tools, release 9.0, V9.0.176`  

2. Check the CUDNN version:

Input the following command into the terminal:  
`cat /usr/local/cuda/include/cudnn.h | grep CUDNN_MAJOR -A 2`

The output will be: 
`#define CUDNN_MAJOR 7`  
`#define CUDNN_MINOR 5`  
`#define CUDNN_PATCHLEVEL 0`  
`--`  
`#define CUDNN_VERSION (CUDNN_MAJOR * 1000 + CUDNN_MINOR * 100 + CUDNN_PATCHLEVEL)`  
`#include "driver_types.h"`

**Install dlib in the Ubuntu**

These links will be helpful (Here I need a gpu support edition):  

with GPU and cuda support  
https://laddiexu.github.io/tech/2018/08/10/face-recognition-library-with-python.html  

with no GPU and no cuda support  
http://www.cnblogs.com/whenyd/p/7721989.html  
https://www.jianshu.com/p/44469d7d86b3  
http://einverne.github.io/markdown-style-guide/zh.html#option-wrap-inner-sentence  

https://chtseng.wordpress.com/2016/12/23/dlib-%E5%A5%BD%E7%94%A8%E7%9A%84%E7%9A%84machine-learning%E5%B7%A5%E5%85%B7-%E4%B8%80/

How to use the ffmpeg to combine the face images in a video
http://hamelot.io/visualization/using-ffmpeg-to-convert-a-set-of-images-into-a-video/

Changing a face in a  windows enviroment 
https://zhuanlan.zhihu.com/p/46810764
