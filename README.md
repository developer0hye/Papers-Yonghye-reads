# Papers-Yonghye-read

1. [License Plate Detection and Recognition in Unconstrained Scenarios](http://openaccess.thecvf.com/content_ECCV_2018/papers/Sergio_Silva_License_Plate_Detection_ECCV_2018_paper.pdf)

S´ergio Montazzolli Silva et al. 2018 ECCV

2. [What makes ImageNet good for transfer learning?](https://arxiv.org/abs/1608.08614)

Under submission to CVPR 2017 
Minyoung Huh, Pulkit Agrawal, Alexei A. Efros, NIPS LSCVS 2016 Workshop (Oral)

3. [Path Aggregation Network for Instance Segmentation](https://arxiv.org/abs/1803.01534v4)

Shu Liu, Lu Qi, Haifang Qin, Jianping Shi, Jiaya Jia, CVPR 2018

4. [Feature-Fused SSD: Fast Detection for Small Objects ](https://arxiv.org/abs/1709.05054)

Proceedings Volume 10615, Ninth International Conference on Graphic and Image Processing (ICGIP 2017); 106151E (2018) https://doi.org/10.1117/12.2304811
Event: Ninth International Conference on Graphic and Image Processing, 2017, Qingdao, China

Guimei Cao; Xuemei Xie; Wenzhe Yang; Quan Liao; Guangming Shi; Jinjian Wu

5. [Small Object Detection with Multiscale Features](https://www.researchgate.net/publication/327986927_Small_Object_Detection_with_Multiscale_Features)

 Guo X. Hu, Zhong Yang, Lei Hu, Li Huang, and Jia M. Han1,  International Journal of Digital Multimedia Broadcasting 2018
 
 6. [R^2-CNN: Fast Tiny Object Detection in Large-Scale Remote Sensing Images](https://arxiv.org/abs/1902.06042)
 
 Jiangmiao Pang, Cong Li, Jianping Shi, Zhihai Xu, Huajun Feng, IEEE Transactions on Geoscience and Remote Sensing 2019

 7. [DSOD: Learning Deeply Supervised Object Detectors From Scratch](http://openaccess.thecvf.com/content_iccv_2017/html/Shen_DSOD_Learning_Deeply_ICCV_2017_paper.html)
 
Zhiqiang Shen, Zhuang Liu, Jianguo Li, Yu-Gang Jiang, Yurong Chen, Xiangyang Xue; The IEEE International Conference on Computer Vision (ICCV), 2017, pp. 1919-1927

```
Object Detection 을 위해 제안된 대부분의 모델은 해당 모델의 Backbone network 을 Imagenet 데이터셋을 이용하여 Pretrain 시킨 후 

Object Detection 데이터셋을 이용하여 finetuning 을 하는 형태로 학습을 진행했다.

저자들은 이를 문제점으로 제기하고 scratch(pretrain 되어 있지 않은 randomly 초기화된)부터 학습 가능한 네트워크 구조를 제안했다.
```

 8. [DetNet: A Backbone network for Object Detection](https://arxiv.org/abs/1804.06215)
 Zeming Li, Chao Peng, Gang Yu, Xiangyu Zhang, Yangdong Deng, Jian Sun, Published in ArXiv 2018
```
Object Detection 에 적합한 BackBone Network 제안.

feature map 이 convolution or pooling 을 거치며 downsampling 될 수록 classification 에는 좋은 feature 가 취득 될 수는 있으나, 

localization 에는 부적합할 수 있다. 저자들은 feature map 이 downsampling 되는 정도를 줄임. 그러나 downsampling 이 덜 된 feature map 상에서

convolution layer 가 증가될 경우 연산량의 증가량이 크게 높음. 

이런 문제를 해결하기 위해 dilated convolution 을 적용하였고 이를 통해 large receptive field 를 확보하고 small object feature 의 missing 을 줄임.  
```
