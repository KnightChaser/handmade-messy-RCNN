# `handmade-messy-RCNN`

> My futile and cute struggle to make RCNN(Regional Convolutional Neural Network) from scratch. I burned more than 30+ hours to do. The result was catastrophically tragic. Help received from ![@GAP-dev](https://github.com/GAP-dev). And failed together, again.

1. Set up
```sh
python3 -m venv rcnn_venv
source ./rcnn_venv/bin/activate
pip3 install -r ./requirements.txt
sudo apt update
sudo apt install nvidia-cuda-toolkit
```
(This project assumes you use CUDA 12.)

2. Download the data
```sh
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtrainval_06-Nov-2007.tar
tar -xvf ./VOCtrainval_06-Nov-2007.tar
```
