# Conda Environment

1. Create and Activate Environment.
```
conda create -n py1.1 python=3.7 -y
conda activate py1.1
```

2. Install PyTorch on CPU Devices.
```
conda install pytorch=1.1 torchvision=0.3 -c pytorch -y
```

3. Install PyTorch on GPU Devices.
```
nvidia-smi
conda install pytorch=1.1 torchvision=0.3 cudatoolkit=9.0 -c pytorch -y
```

4. Install and Launch Jupyter Notebook.
```
conda install jupyter -y
jupyter notebook
```
