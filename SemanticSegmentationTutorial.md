---
sort: 6
---

# Semantic Segmentation Tutorial

Below we provide more detailed instructions of utilizing MCD dataset for semantic segmentation. 

## 1. Data organization and pre-processing
We mainly follow the data organization of SemanticKITTI so that most existing backbones tested on SemanticKITTI can be easily adopted on MCD. After downloading the annotated lidar, we suggest users to follow the detailed organization instruction as in [this tutorial](https://github.com/mcdviral/mcdviral.github.io/blob/master/pcd_to_bin.ipynb) to pre-process the data.

## 2. Training/Testing with Different Backbones
In the following section, we provide the implementation details of training/testing different 3D semantic segmentation methods with MCD dataset. For all methods, we provide their corresponding [Docker](https://www.docker.com/) images to facilitate their implementations. For each repo, you can either build the corresponding Docker image by ```docker build -t IMAGE_NAME .``` in each repo with the Dockerfile we provided, or pull the images we built in advance from Dockerhub.

### [MinkowskiNet (MK-Net)][MKNet_link] and [SPVCNN][SPVCNN_link]

For both MK-Net and SPVCNN, we leverage the re-implementation of from [2DPass](https://github.com/yanx27/2DPASS) with some minor modifications on configs and data I/O. 

* Repo: [https://github.com/AronCao49/2DPASS](https://github.com/AronCao49/2DPASS).
* To pull built image, run ```docker pull aroncao49/2dpass:latest```.
* To train MK-Net/SPVCNN with MCD dataset, please follow the train/test instruction of ```README.md``` in the [repo](https://github.com/AronCao49/2DPASS).

### [SalsaNext][SalsaNext_link]

For SalsaNext, our implementation is mostly based on the official code.

* Repo: [https://github.com/AronCao49/SalsaNext](https://github.com/AronCao49/SalsaNext).
* To pull built image, run ```docker pull aroncao49/salsanext:latest```.
* Follow the updated ```README.md``` to train/test with MCD dataset.
* For training configuration, we made the following changes to adapt SalsaNext to MCD:
    * LiDAR fov, updated to -35.2 to 35.2 degree.
    * Range image resolution, updated to 256x256.
    * Range image standardization, with mean & std computed from MCD dataset.

### [Cylinder3D][Cylinder3d_link]

TBD

### [SDSeg3D][SDSeg3D_link]

TBD

### [WaffleIron][WaffleIron_link]

TBD

### [S-Former][S-Former_link]

TBD


[MKNet_link]: https://arxiv.org/pdf/1904.08755
[SPVCNN_link]: https://arxiv.org/pdf/2007.16100
[SalsaNext_link]: https://arxiv.org/pdf/2003.03653
[Cylinder3d_link]: https://arxiv.org/pdf/2008.01550
[SDSeg3D_link]: https://link.springer.com/chapter/10.1007/978-3-031-19815-1_38
[WaffleIron_link]: https://arxiv.org/pdf/2301.10100
[S-Former_link]: https://openaccess.thecvf.com/content/CVPR2023/papers/Lai_Spherical_Transformer_for_LiDAR-Based_3D_Recognition_CVPR_2023_paper.pdf