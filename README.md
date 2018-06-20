# Caffe for RPN+BF

Caffe fork that supports RPN+BF.

It is forked from [ShaoqingRen/caffe](https://github.com/ShaoqingRen/caffe/tree/faster-R-CNN), which support the usage for faster r-cnn.

This repo add "a trous" trick support, which is needed for the RPN+BF code.

# Usage
0. Follow the [instruction](http://caffe.berkeleyvision.org/installation.html) to set up the prerequisites for Caffe.
0. Use `make matcaffe` Build the mex file.
0. Copy `Caffe_DIR/matlab/+caffe/private/caffe_.mexa64`  to `RPN_BF_DIR/external/caffe/matlab/caffe_faster_rcnn/`.

