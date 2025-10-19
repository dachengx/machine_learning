# Installation of packages for different GPUs

Note: TensorFlow and PyTorch might not co-exist in the same environment

## NVIDIA GeForce RTX 3090 w/ CUDA 12.1

## PyTorch

```
pip install torch==2.5.1 --index-url https://download.pytorch.org/whl/cu121
pip install torchdiffeq==0.2.5
```

## TensorFlow

```
pip install tensorflow[and-cuda]==2.20.0
```


## NVIDIA GeForce RTX 1080 w/ CUDA 11.8

```
pip install torch==2.7.1 --index-url https://download.pytorch.org/whl/cu118
pip install torchdiffeq==0.2.5
```
