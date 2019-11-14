# Deep Residual-Dense Lattice Network for Speech Enhancement
Convolutional neural networks (CNNs) with residual links (ResNets) and causal dilated convolutional units have been the network of choice for deep learning approaches to speech enhancement. While residual links improve gradient flow during training, feature diminution of shallow layer outputs can occur due to repetitive summations with deeper layer outputs. One strategy to improve feature re-usage is to fuse both ResNets and densely connected CNNs (DenseNets). DenseNets, however, over-allocate parameters for feature re-usage. Motivated by this, we propose the residual-dense lattice network (RDL-Net), which is a new CNN for speech enhancement that employs both residual and dense aggregations without over-allocating parameters for feature re-usage. This is managed through the topology of the RDL blocks, which limit the number of outputs used for dense aggregations. Our extensive experimental investigation shows that RDL-Nets are able to achieve a higher speech enhancement performance than CNNs that employ residual and/or dense aggregations. RDL-Nets also use substantially fewer parameters and have a lower
computational requirement. Furthermore, we demonstrate that RDL-Nets outperform many state-of-the-art deep learning approaches to speech enhancement.

## Contact
Please send email to m.nikzaddehaji@griffithuni.edu.au

## Citation
Mohammad Nikzad, Aaron Nicolson,Yongsheng Gao, Jun Zhou, Kuldip K. Paliwal, Fanhua Shang. Deep Residual-Dense Lattice Network for Speech Enhancement. To appear in Proceedings of the Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI), 2020.
