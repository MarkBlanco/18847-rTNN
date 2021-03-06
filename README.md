# 18847-rTNN
This repository is an archive of work done in exploring recurrent temporal neural networks (rTNNs) in 18847-Neuromorphic Computing Architecture.

The top-level directories are:
* SpykeTorch - scripts used for Lab1 in TNN column implementation
* bindsnet_reference - contains slightly modified reservoir reference template from BindsNET
* recurrent_only_scripts - contains variants of recurrent-only architecture

Additional top level files are:
* seq_mnist_pix.py - pixel by pixel sequential MNIST template using reservoirs
* seq_mnist_row.py - row by row sequential MNIST template using reservoirs
* TNN.py - implementations of our extensions to BindsNET for TNN simulation
* TNN_utils.py - utilities used in implementations of recurrent-only rTNN architecture
* rc_template-seq.py - reservoir computing template on sequential mnist
* rc_template.py - general reservoir computing template
* rc_template_buff_seq.py - reservoir computing template using TNN neurons and buffer nodes
* stateful_tnn.py - implementation of stateful rTNN architecture
* test_TNN.py
* test_TNN_2layer.py - implementation of 2-layer rTNN architecture
* test_TNN_lr_readout.py - implementation of TNN column with logistic regression readout
* test_TNN_w_on_off.py
* test_buffer_nodes.py
* tnn_inhibt_recur_TNN.py

Running these codes requires an installation of BindsNET. More details on that can be found here: <https://github.com/BindsNET/bindsnet>.
