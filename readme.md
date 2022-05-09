Run deep learning job in HPC using SLURM
1. download MINIST dataset  `$ wget https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz`
1. git clone this repo to your path
1. update data path in MNIST.py
1. submit job `$ sbatch MNIST.sh`
1. check status `$ squeue`
1. check output file `$ ls`

Reference:
- https://github.com/jorditorresBCN/Fundamentals-DL-CTE-POWER
- https://towardsdatascience.com/deep-learning-on-supercomputers-96319056c61f
- https://stackoverflow.com/questions/55883018/how-to-install-python-package-module-in-slurm


