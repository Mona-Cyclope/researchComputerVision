# Model acceleration compression

## Methodologies

| Pruning                                                                                                                                     |YEAR|
|---------------------------------------------------------------------------------------------------------------------------------------------|----|
|[Biased Weigth Decay](https://proceedings.neurips.cc/paper/1988/file/1c9ac0159c94d8d0cbedc973445af2da-Paper.pdf)                             |1988|
|[Optimal Brain Damage](https://proceedings.neurips.cc/paper/1989/file/6c9882bbac1c7093bd25041881277658-Paper.pdf)                            |1989|
|[Optimal Brain Surgeon](https://www.researchgate.net/publication/2501411_Second_Order_Derivatives_for_Network_Pruning_Optimal_Brain_Surgeon) |1992|
|[Train Connectivity](https://arxiv.org/pdf/1506.02626.pdf)                                                                                   |2015|
|[Hashed Nets](https://proceedings.mlr.press/v37/chenc15.html)                                                                                |2015|
|[Deep Compression](https://arxiv.org/pdf/1510.00149.pdf)                                                                                     |2015|
|[Group Wise Brain Damage](https://arxiv.org/abs/1506.02515)                                                                                  |2015|  
|[Rethinking Pruning](https://arxiv.org/abs/1810.05270#:~:text=Network%20pruning%20is%20widely%20used,%2C%20pruning%20and%20fine%2Dtuning.)   |2019|

| Quantization                                                   |YEAR|
|----------------------------------------------------------------|----|
|[K-means Vector Quantization](https://arxiv.org/abs/1512.06473) |2015|
|[Hessian Weighted kVQ](https://arxiv.org/abs/1612.01543)        |2017|
|[Deep Compression](https://arxiv.org/pdf/1510.00149.pdf)        |2017|
|[Binary Nets](https://arxiv.org/abs/1602.02830)                 |2016|

| Knowledge Distillation                                                                                                                         |YEAR|
|------------------------------------------------------------------------------------------------------------------------------------------------|----|
|[Model Compression](https://www.semanticscholar.org/paper/Model-compression-Bucila-Caruana/30c9bb327b7f2b9f1d1e5b69b9d0c97b410948d9)            |2006|
|[Deep?](https://arxiv.org/abs/1312.6184)                                                                                                        |2014|
|[Knowledge Distillation](https://arxiv.org/abs/1503.02531)                                                                                      |2015|
|[Bayesian Dark Knowledge](https://arxiv.org/abs/1506.04416)                                                                                     |2015|
|[Fit Nets](https://arxiv.org/abs/1412.6550)                                                                                                     |2015|
|[Att Nets](https://arxiv.org/abs/1612.03928)                                                                                                    |2017|
|[Contrastive Representation Distillation](https://arxiv.org/abs/1910.10699)                                                                     |2019|
|[Efficient Object Detection](https://proceedings.neurips.cc/paper/2017/file/e1e32e235eee1f970470a3a6658dfdd5-Paper.pdf)                         |2017|
|[DIODE](https://openaccess.thecvf.com/content/WACV2021/papers/Chawla_Data-Free_Knowledge_Distillation_for_Object_Detection_WACV_2021_paper.pdf) |2021|

| Relevant Works                                                                                               | YEAR |
|--------------------------------------------------------------------------------------------------------------|------|
|[Accelerater NMS in Yolo](https://quadric.io/2022/01/19/yolo-detection-accelerating-non-maximal-suppression/) | 2022 |

## Benchmark Evaluation and Databases

| Networks |
|----------|
| AlexNet |
| Le-Net |
| All-CNN-nets |
| VGG |
| ResNet |

| Metrics           |
|------------------ |
| comp ratio        |
| saved space index |
| speed ratio       |

| Datasets |
|----------|
| PASCAL   |
| KITTI    |
| ILSRVRC  |
| MS-COCO  |