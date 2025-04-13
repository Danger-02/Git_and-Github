# Complete Understanding about GIT and GITHUB : 
This repository provides a comprehensive guide about what is Git and Github. What are the comands associated with it and everything.

---

# Git :
Version Control System is a tool that helps to track changes in code. Git is a Version Control System. It is popular, free and open source, fast and scalable.   

Uses :
1. Track our history.
2. Collaboration

# Github :
Github is a website that allows developers to store and manage their code using Git. We can upload our progress in folder(repository)
- [Github Website](https://github.com)

---

## ✅ Step-by-Step Procedure :

### STEP 01 : NVIDIA Driver  

We should install the latest version of our GPU's driver. It can be downloaded from:   
- [NVIDIA GPU Driver Download](https://www.nvidia.com/en-us/drivers/)

### STEP 02 : Visual Studio C++

We need Visual Studio, with C++ installed. By default, C++ is not available with Visual Studio, so make sure to select all C++ options.  
- [Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/vs/community/)

### STEP 03 : Anaconda/ Miniconda

We will need Ananconda or Miniconda to install deep learning packages.  
- [Anaconda Download Site](https://www.anaconda.com/download)

### STEP 04 : CUDA Toolkit

We also need to install CUDA-Toolkit.  
- [Download CUDA Toolkit ](https://developer.nvidia.com/cuda-toolkit-archive)

### STEP 05 : cuDNN

We also need to install cuDNN.  
- [Download cuDNN](https://developer.nvidia.com/rdp/cudnn-archive)

### STEP 06 : Install PyTorch
We need to install PyTorch-Cuda supported. 
- [Install PyTorch](https://pytorch.org/get-started/locally/)

### Finally run the following script to test your GPU
```bash
import torch

print("Number of GPU :",torch.cuda.device_count())
print("GPU Name :",torch.cuda.get_device_name())

device = torch.device('cuda' if torch.cuda.is_available() else 'cpu')
print("Using Device",device)
```
--- 
### 🖥️ For Reference Youtube Video : 
- [How to Setup NVIDIA GPU for Deep Learning](https://youtu.be/nATRPPZ5dGE?feature=shared)
