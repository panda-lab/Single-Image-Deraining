### Single Image Deraining: A Comprehensive Benchmark Analysis (CVPR19)

Paper Link: 

Abstract: We present a comprehensive study and evaluation of existing single image deraining algorithms, using a new large-scale benchmark consisting of both synthetic and real-world rainy images.This dataset highlights diverse data sources and image contents, and is divided into three subsets (rain streak, rain drop, rain and mist), each serving different training or evaluation purposes. We further provide a rich variety of criteria for dehazing algorithm evaluation, ranging from full-reference metrics, to no-reference metrics, to subjective evaluation and the novel task-driven evaluation. Experiments on the dataset shed light on the comparisons and limitations of state-of-the-art deraining algorithms, and suggest promising future directions.

#### derain model and code ：JORDER , DDN ,DID-MDN,ID-CGAN,GMM,DerainDrop

#### detection algorithm and model : 

Faster-RCNN: https://github.com/rbgirshick/py-faster-rcnn (sh./data/scripts/fetch_faster_rcnn_models.sh download the model)

RetinaNet:https://github.com/fizyr/keras-retinanet (with MSCOCO pretrain model)

YOLOv3: https://github.com/pjreddie/darknet

(Model: wget https://pjreddie.com/media/files/yolov3.weights)

MobileNet-VGG-512:SSD : https://github.com/FreeApe/VGG-or-MobileNet-SSD
(Model : https://drive.google.com/file/d/0BzKzrI_SkD1_NVVNdWdYNEh1WTA/view )

#### data : baiduyun or google drive(Rain in Drive) ：链接:https://pan.baidu.com/s/1CnPO9m5t6E98ssuTimNpdA 密码:qy5s

#### Metric :PSNR,SSIM,NIQE,BLINDS-II,SSEQ

#### rain_mist(real + synthetic)

#### rain_streak(real + synthetic)

#### rain_drop(real + synthetic)
