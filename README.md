# LWENet
A lightweight neural network for hard exudate segmentation of fundus image

Please read our [paper]() for more details!
### Introduction:
Fundus image is an important indicator for diagnosing diabetic retinopathy (DR), which is a leading cause of blindness in adults. Moreover, hard exudate, a special kind of lesion in the fundus image, is treated as the basis to evaluate the severity level of DR. Therefore, it is crucial to segment hard exudate exactly. However, the segmentation results of existing deep learning-based segmentation methods are rather coarse due to successive pooling operations. In this paper, we propose a lightweight segmentation network with only one down-sampling operation and 1.9M parameters. Further, we propose a two-stage training algorithm to train our network from scratch. We conduct experiments on the IDRiD and e-ophtha EX datasets. Experimental results show that our network achieves superior performance with the fewest parameters and the fastest speed compared with baseline methods on the IDRiD dataset. Specially, with 1/20 parameters and 1/3 inference time, our method is over 10% higher than DeepLab v3+ in terms of F1-score on the IDRiD dataset.

## Dataset
DDR can be download [here.](https://github.com/nkicsl/DDR-dataset)

## License
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![Badge](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu/#/zh_CN)
