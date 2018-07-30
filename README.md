# installCaffeJTX2
This repository is forked from https://github.com/jetsonhacks/installCaffeJTX2. The change done is to make the build link point to a caffe source that has support for darknet conversion. Instructions to build caffe remain same as original repo. Details as follows:

Install Caffe on the NVIDIA Jetson TX2 Development Kit.

Caffe: a fast open framework for deep learning. http://caffe.berkeleyvision.org/
Caffe source code is here: https://github.com/BVLC/caffe

Scripts to install Caffe and dependencies on the NVIDIA Jetson TX2 Development Kit.
This script is for L4T 27.1, an Ubuntu 16.04 variant. 

To maximize the performance of the Jetson TX2, you can use the jetson_clocks.sh script which enables all CPU cores, and maximizes clock speeds on the CPUs and GPU. JetPack 3 installs jetson_clocks.sh in the home directory.

For best results on the Jetson TX2 install:

<ul>
<li>L4T 27.1 (Ubuntu 16.04)</li>
<li>OpenCV4Tegra</li>
<li>CUDA 8.0</li>
<li>cuDNN v5.1</li>
</ul>

These can all be installed with JetPack 3.

To install, run the installCaffe.sh script:

$ ./installCaffe.sh

