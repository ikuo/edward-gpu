## About

A Dockerfile for [Edward](http://edwardlib.org/) with GPU.

## Requirements

- [nvidia-docker](https://github.com/NVIDIA/nvidia-docker)

## Running

```
sudo nvidia-docker run -it --rm -p 8888:8888 ikuo/edward-gpu
```
