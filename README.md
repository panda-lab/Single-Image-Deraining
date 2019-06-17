## Single Image Deraining: A Comprehensive Benchmark Analysis (CVPR19)

[[Paper Link](https://arxiv.org/abs/1903.08558)]  

Siyuan Li, Iago Breno Araujo, Wenqi Ren, Zhangyang Wang, Eric K. Tokuda, Roberto Hirata Junior, Roberto Cesar-Junior, Jiawan Zhang, Xiaojie Guo, Xiaochun Cao

Abstract: We present a comprehensive study and evaluation of existing single image deraining algorithms, using a new large-scale benchmark consisting of both synthetic and real-world rainy images.This dataset highlights diverse data sources and image contents, and is divided into three subsets (rain streak, rain drop, rain and mist), each serving different training or evaluation purposes. We further provide a rich variety of criteria for dehazing algorithm evaluation, ranging from full-reference metrics, to no-reference metrics, to subjective evaluation and the novel task-driven evaluation. Experiments on the dataset shed light on the comparisons and limitations of state-of-the-art deraining algorithms, and suggest promising future directions.


#### If you find the resource useful, please cite the following

```
@article{Li2019DerainBenchmark,		
title={Single Image Deraining: A Comprehensive Benchmark Analysis},
author={Siyuan Li, Iago Breno Araujo, Wenqi Ren, Zhangyang Wang, Eric K. Tokuda, Roberto Hirata Junior, Roberto Cesar-Junior, Jiawan Zhang, Xiaojie Guo and Xiaochun Cao},
journal={IEEE Conference on Computer Vision and Pattern Recognition},
year={2019}
}

```

#### 1. Derain Code Test by Our Paper.


| Algorithms | Paper Link | Projects Link |  
| ------------------- | ------------------------------------------------------- | ------------------- |
|   GMM    | [Paper Link](http://openaccess.thecvf.com/content_cvpr_2016/papers/Li_Rain_Streak_Removal_CVPR_2016_paper.pdf)         | [Code Link](https://drive.google.com/file/d/0B5QI9xdWo2K6a2xvWGZGeUVoRlhUQmg1SGtqdjhYdXV1UC1j)   |  
|   DDN    | [Paper Link](http://openaccess.thecvf.com/content_cvpr_2017/papers/Fu_Removing_Rain_From_CVPR_2017_paper.pdf)   |[Code Link](https://github.com/XMU-smartdsp/Removing_Rain)                 |  
|   JORDER | [Paper Link](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf)    | [Code Link](http://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)             |   
|  ID-CGAN | [Paper Link](https://arxiv.org/abs/1701.05957)    |  [Code Link](https://github.com/TrinhQuocNguyen/Edited_Original_IDCGAN)  | 
| DerainDrop | [Paper Link](https://arxiv.org/abs/1711.10098)       | [Code Link](https://github.com/rui1996/DeRaindrop)     |   
| DID-MDN    | [Paper Link](https://arxiv.org/abs/1802.07412)    | [Code Link](https://github.com/hezhangsprinter/DID-MDN)    |  



#### 2. Detection Code and Model Test by Our Paper. 


| Algorithms | Code Link | Pretrain Model Link |  
| ------------------- | ------------------------------------------------------- | ------------------- |
|   Faster-RCNN       | [Code Link](https://github.com/rbgirshick/py-faster-rcnn)     |  sh./data/scripts/fetch_faster_rcnn_models.sh   |  
|   RetinaNet         | [Code Link](https://github.com/fizyr/keras-retinanet)   |  MSCOCO pretrain model    |  
|   YoloV3            | [Code Link](https://github.com/pjreddie/darknet)    | https://pjreddie.com/media/files/yolov3.weights   |   
|   SSD-512           | [Code Link](https://github.com/FreeApe/VGG-or-MobileNet-SSD)    | https://drive.google.com/file/d/0BzKzrI_SkD1_NVVNdWdYNEh1WTA/view  | 


#### 3. Synthetic Data and Real Data Adopt in Our Paper. 

| Data Type | Download Link |  Download Link |  
| ------------------- | ------------------------------------------------------- | ------------------- |
| Our RID Dataset ( Rain in Driving with Objects Label) | [BaiduYun](https://pan.baidu.com/s/1wdrmTHf5ewNXHZABQ--ftQ) Access Code:sgf9| [GoogleDrive]|  
| Our RIS Dataset ( Rain in Surveillance with Objects Label) | [BaiduYun] | [GoogleDrive] |
| Rain Mist        | [Real]  | [Synthetic]     |  
| Rain Drop        | [Real]  | [Synthetic]     |   
| Rain Streak      | [Real]  | [Synthetic]     | 



#### 4. Special thanks to my teammates @[JackYu](https://github.com/szad670401)


