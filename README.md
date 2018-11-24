# Domain generalization

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

-----

## Table of contents

* [Research papers](#Research-papers)

* [Datasets](#Datasets)

* [References](#References)

* [License](#License)

-----

## Research papers

### Pathfinder

- [Generalizing from several related classification tasks to a new unlabeled sample](http://papers.nips.cc/paper/4312-generalizing-from-several-related-classification-tasks-to-a-new-unlabeled-sample.pdf)  
Blanchard, Gilles, Gyemin Lee, and Clayton Scott.  
In Advances in neural information processing systems (**NIPS**), pp. 2178-2186. 2011.

### Machine learning perspective

#### Kernel-based methods

- (**CIDG**) [Domain Generalization via Conditional Invariant Representation](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16595/16558)  
Li, Ya, Mingming Gong, Xinmei Tian, Tongliang Liu, and Dacheng Tao.  
AAAI Conference on Artificial Intelligence (**AAAI**), North America, apr. 2018.  
[[code]](https://mgong2.github.io/papers/CIDG.zip)

- (**SCA**) [Scatter component analysis: A unified framework for domain adaptation and domain generalization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7542175)  
Ghifary, Muhammad, David Balduzzi, W. Bastiaan Kleijn, and Mengjie Zhang.  
IEEE Transactions on Pattern Analysis & Machine Intelligence (**TPAMI**) 1 (2017): 1-1.

- (**DICA**) [Domain generalization via invariant feature representation](http://proceedings.mlr.press/v28/muandet13.pdf)  
Muandet, Krikamol, David Balduzzi, and Bernhard Schölkopf.  
In International Conference on Machine Learning (**ICML**), pp. 10-18. 2013.  
[[code]](http://krikamol.org/research/codes/dica.zip)

#### Support vector machine (SVM)-based methods

- (**LRE-SVM**) [Exploiting low-rank structure from latent domains for domain generalization](https://link.springer.com/chapter/10.1007/978-3-319-10578-9_41)  
Xu, Zheng, Wen Li, Li Niu, and Dong Xu.  
In European Conference on Computer Vision (**ECCV**), pp. 628-643. Springer, Cham, 2014.  
[[code]](http://www.vision.ee.ethz.ch/~liwenw/papers/Xu_ECCV2014_codes.zip)

- (**Undo-Bias**) [Undoing the damage of dataset bias](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_12)  
Khosla, Aditya, Tinghui Zhou, Tomasz Malisiewicz, Alexei A. Efros, and Antonio Torralba.  
In European Conference on Computer Vision (**ECCV**), pp. 158-171. Springer, Berlin, Heidelberg, 2012.  
[[code]](https://github.com/adikhosla/undoing-bias/archive/master.zip)

#### Autoencoder-based methods

- (**MMD-AAE**) [Domain generalization with adversarial feature learning](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2932.pdf)  
Li, Haoliang, Sinno Jialin Pan, Shiqi Wang, and Alex C. Kot.  
In Proc. IEEE Conf. Comput. Vis. Pattern Recognit.(**CVPR**). 2018.

- (**MTAE**) [Domain generalization for object recognition with multi-task autoencoders](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Ghifary_Domain_Generalization_for_ICCV_2015_paper.pdf)  
Ghifary, Muhammad, W. Bastiaan Kleijn, Mengjie Zhang, and David Balduzzi.  
In Proceedings of the IEEE international conference on computer vision (**ICCV**), pp. 2551-2559. 2015.  
[[code]](https://github.com/ghif/mtae)

#### Deep neural network-based methods

- [Deep Domain Generalization With Structured Low-Rank Constraint](https://ieeexplore.ieee.org/document/8053784)  
Ding, Zhengming, and Yun Fu.  
IEEE Transactions on Image Processing (**TIP**) 27, no. 1 (2018): 304-313.

### Computer vision perspective

- (**CIDDG**) [Deep Domain Generalization via Conditional Invariant Adversarial Networks](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf)  
Li, Ya, Xinmei Tian, Mingming Gong, Yajing Liu, Tongliang Liu, Kun Zhang, and Dacheng Tao.  
In Proceedings of the European Conference on Computer Vision (**ECCV**), pp. 624-639. 2018.

- (**CCSA**) [Unified deep supervised domain adaptation and generalization](http://openaccess.thecvf.com/content_ICCV_2017/papers/Motiian_Unified_Deep_Supervised_ICCV_2017_paper.pdf)  
Motiian, Saeid, Marco Piccirilli, Donald A. Adjeroh, and Gianfranco Doretto.  
In Proceedings of the IEEE International Conference on Computer Vision (**ICCV**), vol. 2, p. 3. 2017.  
[[code]](https://github.com/samotiian/CCSA)

- [Deeper, broader and artier domain generalization](https://ieeexplore.ieee.org/abstract/document/8237853)  
Li, Da, Yongxin Yang, Yi-Zhe Song, and Timothy M. Hospedales.  
In Proceedings of the IEEE International Conference on Computer Vision (**ICCV**), pp. 5543-5551. IEEE, 2017.  
[[code]](http://www.eecs.qmul.ac.uk/~dl307/project_iccv2017)

- (**MVDG**) [Multi-view domain generalization for visual recognition](https://ieeexplore.ieee.org/document/7410834)  
Niu, Li, Wen Li, and Dong Xu.  
In Proceedings of the IEEE International Conference on Computer Vision (**ICCV**), pp. 4193-4201. 2015.

- (**UML**) [Unbiased metric learning: On the utilization of multiple datasets and web images for softening bias](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Fang_Unbiased_Metric_Learning_2013_ICCV_paper.pdf)  
Fang, Chen, Ye Xu, and Daniel N. Rockmore.  
In Proceedings of the IEEE International Conference on Computer Vision (**ICCV**), pp. 1657-1664. 2013.

-----

## Datasets

|     Dataset    |        #Sample |       #Feature      | #Class |   Subdomain  | Reference |
|:--------------:|:-------:|:-------------------:|:------:|:------------:|:--------:|
| [Office+Caltech](#Office+Caltech) |    2533  | SURF: 800, DeCAF: 4096 |   10   |  A, W, D, C  |   [[1]](#1)       |
|     [VOC2007](#vlcs)    |          3376  |      DeCAF: 4096     |    5   |       V      |    [[2]](#2)      |
|     [LabelMe](#vlcs)    |          2656  |      DeCAF: 4096     |    5   |       L      |    [[3]](#3)      |
|   [Caltech101](#vlcs)   |          1415  |      DeCAF: 4096     |    5   |       C      |    [[4]](#4)      |
|      [SUN09](#vlcs)     |          3282  |      DeCAF: 4096     |    5   |       S      |    [[5]](#5)      |

### Office+Caltech

#### Introduction

This dataset is constructed by collecting common classes in two datasets: Office-31 (which contains A, W and D) and Caltech-256 (which is C).  
Four domains: A(Amazon, 958 instances), W(Webcam, 295 instances), D(DSLR, 157 instances), and C(Caltech, 1123 instances).  
Ten common classes: back pack, bike, calculator, headphones, keyboard, laptop_computer, monitor, mouse, mug, and projector.

#### Download

Download Office+Caltech original images [[Google Drive](https://drive.google.com/file/d/14OIlzWFmi5455AjeBZLak2Ku-cFUrfEo/view?usp=sharing)]  
Download Office+Caltech SURF dataset [[Google Drive](https://drive.google.com/file/d/1TKot-lmTy5h797YaAeydkOD6kWqii5fa/view?usp=sharing)]  
Download Office+Caltech DeCAF dataset [[Google Drive](https://drive.google.com/file/d/1mgEyml0ZoZjUlUQfWNfr-Srxmlot3yq6/view?usp=sharing)]

### VLCS

#### Introduction

Four domains: V(VOC2007), L(LabelMe), C(Caltech), and S(SUN09).  
Five common classes: bird, car, chair, dog, and person. 

#### Download

Download the VLCS DeCAF dataset [[Google Drive](https://drive.google.com/drive/folders/1yvIpp0kg8e-GHESF6jJjCO4M7mjOJHLS?usp=sharing)]

-----

## References
1. <a name="1"></a> Gong, Boqing, Yuan Shi, Fei Sha, and Kristen Grauman. "Geodesic flow kernel for unsupervised domain adaptation." In Computer Vision and Pattern Recognition (CVPR), 2012 IEEE Conference on, pp. 2066-2073. IEEE, 2012.

2. <a name="2"></a> Everingham, Mark, Luc Van Gool, Christopher KI Williams, John Winn, and Andrew Zisserman. "The pascal visual object classes (voc) challenge." International journal of computer vision 88, no. 2 (2010): 303-338.

3. <a name="3"></a> Russell, Bryan C., Antonio Torralba, Kevin P. Murphy, and William T. Freeman. "LabelMe: a database and web-based tool for image annotation." International journal of computer vision 77, no. 1-3 (2008): 157-173.

4. <a name="4"></a> Griffin, Gregory, Alex Holub, and Pietro Perona. "Caltech-256 object category dataset." (2007).

5. <a name="5"></a> Choi, Myung Jin, Joseph J. Lim, Antonio Torralba, and Alan S. Willsky. "Exploiting hierarchical context on a large database of object categories." (2010).

-----

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.