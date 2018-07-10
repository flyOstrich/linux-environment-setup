cuda version : cuda8.0 ga1
tensorflow gpu : 1.4
cudnn : cuDNN v6.0 (April 27, 2017), for CUDA 8.0
# Q: cat not enter linux system desktop after install nvidia driver ?
## A: disable uefi mode on bios
# Q: cuda kernel function do not launch ?
## A: remove the "arch" compile option for "nvcc"
# Q: 安装tensorflow，pycharm中出现libcudart.so.8.0: can't open shared object file: No such file or directory
## A: [answer link](https://blog.csdn.net/luoru/article/details/69773201)