## Find any of this useful?
If you find any of this useful, consider being my [sponsor](https://github.com/sponsors/davidenunes). I really appreciate it, or get me some coffee, coffee is great! Check out the sponsor tiers or the external links on the sidebar for one time donations.

# Tensorflow Wheels
Tensorflow wheels I've been building and using over time. Unless specified, these are built for **skylake** CPUs or equivalent instruction sets. This means they support SSE4.2 and AVX2 and all the other instructions supported by skylake microarchitecture. Most builds have a minimum of CUDA compute capability of 6.1. 

Although builds are made in Arch Linux, the latest wheel is fully compatible with Ubuntu 20.04 or 20.10 (depending on your glibc version), other wheels are compatible with 18.04, which comes with older nvidia drivers. You can see the compatibility between drivers and CUDA in the [CUDA Driver section](https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html#cuda-major-component-versions)


<!--
| 2.4 |CPU|   3.9  | 11.1 | 8 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.4.cp39.gpu/tensorflow-2.4.0-cp39-cp39-linux_x86_64.whl)| 
-->

| TF | HW |Python | CUDA | cuDNN | Support | OS | Download |
|:------:|:------:|:------:|:----:|:-------:|:-----:|:------------:|:------:|
| 2.4.1 |CPU|   3.8  | 11.1 | 8 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.4.1.cp38.gpu/tensorflow-2.4.1-cp38-cp38-linux_x86_64.whl)|
| 2.4 |CPU|   3.8  | 11.1 | 8 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.4.cp38.gpu/tensorflow-2.4.0-cp38-cp38-linux_x86_64.whl)|
| 2.4rc4 |CPU|   3.8  | 11.1 | 8 | TensorRT, XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.4.rc4.cp38/tensorflow-2.4.0rc4-cp38-cp38-linux_x86_64.whl)|
| 2.3 |GPU|   3.8  |11 | 8 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.3.cp38.gpu/tensorflow-2.3.0-cp38-cp38-linux_x86_64.whl)|
| 2.2 |GPU|   3.8  |10.2| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.2.cp38.gpu/tensorflow-2.2.0-cp38-cp38-linux_x86_64.whl)|
| 2.2rc2 |GPU|   3.7  |10.2| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.2.0.rc2.cp37.c72.gpu/tensorflow-2.2.0rc2-cp37-cp37m-linux_x86_64.whl)|
| 2.1 |GPU|   3.7  |10.2| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.1.cp37.c72.gpu/tensorflow-2.1.0-cp37-cp37m-linux_x86_64.whl)|
| 2.1 |GPU|   3.7  |10.1| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.1.cp37.gpu/tensorflow-2.1.0-cp37-cp37m-linux_x86_64.whl)|
| 2.0 |GPU|   3.7  |10.1| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.0.cp37.gpu.xla/tensorflow-2.0.0-cp37-cp37m-linux_x86_64.whl)|
| 2.0rc2 |GPU|   3.7  |10.1| 7.6 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.0rc2.cp37.gpu.xla/tensorflow-2.0.0rc2-cp37-cp37m-linux_x86_64.whl)|
| 2.0rc2 |GPU|   3.7  |10.1| 7.6 | SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.0rc2.cp37.gpu/tensorflow-2.0.0rc2-cp37-cp37m-linux_x86_64.whl)|
| 1.14 |GPU|   3.7  |10.0| 7.4 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.14.cp37.gpu.xla/tensorflow-1.14.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.1 |GPU|   3.7  |10.0| 7.4 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp37.gpu.xla/tensorflow-1.13.1-cp37-cp37m-linux_x86_64.whl)|
| 1.13.1 |CPU|   3.6  |_| _ | _ | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp36.cpu/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.1 |CPU|   3.6  |_| _ | SSE4.X,AVX,AVX2,FMA | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp26.cpu.ubuntu1804/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.0 |GPU|   3.7  |10.0| 7.4 | XLA,SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37.gpu.xla/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.0 |GPU|   3.7  |10.0| 7.4 | SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37.gpu/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.0 |CPU|   3.7  | _ |  _ | SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.12.0 |GPU|   3.6  | 10.0 |  7.4  | SSE4.X,AVX,AVX2,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.12.0.cp36/tensorflow-1.12.0-cp36-cp36m-linux_x86_64.whl)|

## Other builds



| TF | HW |Python | CUDA | cuDNN | Support | OS | Download |
|:------:|:------:|:------:|:----:|:-------:|:-----:|:------------:|:------:|
| 2.3 |GPU CUDA Compute 5.0 |   3.8  | 11 | 8 | SSE4.X,AVX,AVX2, FMA, XLA | Arch Linux x86_64 / Ubuntu 20.04 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.3.cp38.gpu.compute.5/tensorflow-2.3.0-cp38-cp38-linux_x86_64.whl)|
| 2.2 |GPU CUDA Compute 5.0 |   3.8  | 10.2 | 7.6 | SSE4.X,AVX,AVX2, FMA, XLA | Arch Linux x86_64 / Ubuntu 20.04 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.2.cp38.gpu.cuda5/tensorflow-2.2.0-cp38-cp38-linux_x86_64.whl)|
| 2.1 |CPU / amdfam10 |   3.7  | _ | _ | SSE4.X,AVX,AVX2, FMA, XLA | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r2.1.cp37.cpu.amdfam10/tensorflow-2.1.0-cp37-cp37m-linux_x86_64.whl)|
| 1.14.1 |CPU / amdfam10 |   3.6  |_| _ | XLA | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.14.1.cp36.cpu.amdfam10/tensorflow-1.14.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.1 |CPU / amdfam10 |   3.6  |_| _ | _ | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp36.cpu.amdfam10/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.1 |CPU / skylake-512 |   3.7  | _ | _ | SSE4.X, FMA, AVX512F | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp37.cpu.skylake-512/tensorflow-1.13.1-cp37-cp37m-linux_x86_64.whl)|


## Using Arch Linux?
This is a rolling distro, so you might be tempted to always upgrade everything (nvidia drivers, linux kernel, etc). One thing to take into account is that different CUDA versions have different nvidia driver requirements (and certain driver versions depend on specific kernel versions). Before upgrading the kernel or drivers, consider checking the CUDA toolkit release notes: https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html


## Need a different build?
I'm using this as a repository of TF wheels I'll be using in various projects, if you want a particular build and don't have the reasources to build from sources yourself, open an issue and I'll see if I can help.

You can also drop me a line at [@davidelnunes](https://twitter.com/davidelnunes)

### Note 
Since I'm building on a machine with ArchLinux, which is a rolling distro. This means wheels might be compiled with e.g. glibc on a newer version than your current system. To speed-up the process, if you are requesting a custom build, providing a docker image I can use with your exact system requirements is most appreciated 👍


## Buy me a coffee
If you find any of this useful, consider being my [sponsor](https://github.com/sponsors/davidenunes). I really appreciate it, or get me some coffee, coffee is great!
<br/><br/>
<a href='https://ko-fi.com/Y8Y0RZO6' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
