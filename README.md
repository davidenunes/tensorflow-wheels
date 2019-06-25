# Tensorflow Wheels
Tensorflow wheels I've been building and using over time. Unless specified, these are built for **skylake** CPUs or equivalent instruction sets.

| TF | HW |Python | CUDA | cuDNN | Support | OS | Download |
|:------:|:------:|:------:|:----:|:-------:|:-----:|:------------:|:------:|
| 1.14 |GPU|   3.7  |10.0| 7.4 | XLA,SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.14.cp37.gpu.xla/tensorflow-1.14.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.1 |GPU|   3.7  |10.0| 7.4 | XLA,SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp37.gpu.xla/tensorflow-1.13.1-cp37-cp37m-linux_x86_64.whl)|
| 1.13.1 |CPU|   3.6  |_| _ | _ | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp36.cpu/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.1 |CPU|   3.6  |_| _ | _ | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp26.cpu.ubuntu1804/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.0 |GPU|   3.7  |10.0| 7.4 | XLA,SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37.gpu.xla/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.0 |GPU|   3.7  |10.0| 7.4 | SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37.gpu/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.13.0 |CPU|   3.7  | _ |  _ | SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.0.cp37/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl)|
| 1.12.0 |GPU|   3.6  | 10.0 |  7.4  | SSE,AVX,FMA | Arch Linux x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.12.0.cp36/tensorflow-1.12.0-cp36-cp36m-linux_x86_64.whl)|

## Other builds

| TF | HW |Python | CUDA | cuDNN | Support | OS | Download |
|:------:|:------:|:------:|:----:|:-------:|:-----:|:------------:|:------:|
| 1.13.1 |CPU / amdfam10 |   3.6  |_| _ | _ | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp36.cpu.amdfam10/tensorflow-1.13.1-cp36-cp36m-linux_x86_64.whl)|
| 1.13.1 |CPU / skylake-512 |   3.7  | _ | _ | AVX2, FMA, AVX512F | Ubuntu 18.04 x86_64 |[**Download**](https://github.com/davidenunes/tensorflow-wheels/releases/download/r1.13.1.cp37.cpu.skylake-512/tensorflow-1.13.1-cp37-cp37m-linux_x86_64.whl)|


## Using Arch Linux?
This is a rolling distro, so you might be tempted to always upgrade everything (nvidia drivers, linux kernel, etc). One thing to take into account is that different CUDA versions have different nvidia driver requirements (and certain driver versions depend on specific kernel versions). Before upgrading the kernel or drivers, consider checking the CUDA toolkit release notes: https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html


## Need a different build?
I'm using this as a repository of TF wheels I'll be using in various projects, if you want a particular build and don't have the reasources to build from sources yourself, open an issue and I'll see if I can help.

You can also drop me a line at [@davidelnunes](https://twitter.com/davidelnunes)

## Get me some coffee. Coffee is the best!
If you find any of this useful, consider getting me some coffee, coffee is great!
<br/><br/>
<a href='https://ko-fi.com/Y8Y0RZO6' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
