# Introdunction
This is the code of paper 'Pedestrian Attribute Recognition Algorithm Combining Semantic and Image Information'

## Abstract

In the actual combat of public security, video surveillance is an important clue and source of evidence for solving cases, and it has broad application scenarios for pedestrian attribute identification in video surveillance. In order to improve the recognition accuracy of pedestrian attributes, solve the problem of lack of use of natural semantic associations between pedestrian attributes and the poor extraction of image information related to different attributes, this paper proposes a pedestrian attribute recognition algorithm that combines semantic and image information. Firstly, the relationship modeling ability is mined through self-attention mechanism. The intrinsic relationship between pedestrian attributes is established by using cross self-attention to establish the relationship between semantic information between attributes and image feature information. Second, relying on convolution to fuse high-order and low-order features and add local feature information to the module to improve the robustness of the model. Due to the design of the attribute prediction module, it can be spliced with any backbone network and has good performance. The experimental results show that the mean precision of the algorithm on the PETA and PA-100K datasets is 89.04% and 84.04%, respectively. Compared with the existing methods, the algorithm can make full use of attribute semantics and image feature information, and has a significant improvement in multiple evaluation indicators.
![fig](images/1.png)

The rest code will coming soon.

# Acknowledgement
We thank the authors of[Q2L](https://github.com/SlongLiu/query2labels) [ASL](https://github.com/Alibaba-MIIL/ASL), [TResNet](https://github.com/Alibaba-MIIL/TResNet), [detr](https://github.com/facebookresearch/detr), [CvT](https://github.com/microsoft/CvT), and [Swin-Transformer](https://github.com/microsoft/Swin-Transformer) for their great works and codes.
