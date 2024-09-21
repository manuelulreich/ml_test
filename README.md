# ml_test
Python code for testing correct installation of dependencies for Pytorch cifar10 training.

# Installation

1) Install Python `sudo apt install python`  
 pip3 `sudo apt install -y python3-pip`  
 and venv `sudo apt install -y python3.12-venv`

2) Create a venv `python3 -m venv env_name`

3) Navigate to the directory `cd env_name`

4) Activate the venv `source bin/activate`

5) Install PyTorch by following https://pytorch.org/get-started/locally/ You should use the latest CUDA version supported by your system (likely just the latest available). This will look something like the following:  
'''
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
'''

6) Run `python3 cifartest.py` and see if there are any packages missing and/or cuda is available.