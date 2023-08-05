# Domain generalization

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

-----

## Table of contents

* [Survey papers](#Survey-papers)

* [Research papers 2023](#Research-papers-2023)
    * [Computer vision venues](#cv2023)

* [Research papers 2021](#Research-papers-2021)
    * [Machine learning venues](#ml2021)
    * [Computer vision venues](#cv2021)
    * [arXiv](#arxiv2021)

* [Research papers before 2021](#Research-papers-before-2021)
    * [Pathfinder](#pathfinder)
    * [Machine learning venues](#mlbf2021)
    * [Computer vision venues](#cvbf2021)
    * [arXiv](#arxivbf2021)

* [Datasets](#Datasets)
    * [Office+Caltech](#Office-Caltech)
    * [VLCS](#VLCS)
    * [ImageNet-C](#ImageNet-C)
    * [ImageNet-R](#ImageNet-R)
    * [PACS](#PACS)
    * [Geo-YFCC](#Geo-YFCC)

* [DG variants](#DG-variants)

* [References](#References)

* [Contact](#Contact)

* [License](#License)

-----

## Survey papers

- [Domain Generalization: A Survey](https://arxiv.org/abs/2103.02503)  
Zhou, Kaiyang, Ziwei Liu, Yu Qiao, Tao Xiang, and Chen Change Loy.  
*arXiv preprint arXiv:2103.02503* (2021).  

- [Generalizing to Unseen Domains: A Survey on Domain Generalization](https://arxiv.org/abs/2103.03097)  
Wang, Jindong, Cuiling Lan, Chang Liu, Yidong Ouyang, Wenjun Zeng, and Tao Qin.  
*International Joint Conference on Artificial Intelligence* (**IJCAI**) (2021).  

## Research papers 2023

<h3 id="cv2023">Computer vision venues</h3>

- (**PromptStyler**) [PromptStyler: Prompt-driven Style Generation for Source-free Domain Generalization](https://arxiv.org/abs/2307.15199)  
Junhyeong Cho, Gilhyun Nam, Sungyeon Kim, Hunmin Yang, Suha Kwak.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2023.  
[[website]](https://PromptStyler.github.io/)

## Research papers 2021

<h3 id="ml2021">Machine learning venues</h3>

- (**IB-IRM**) [Invariance Principle Meets Information Bottleneck for Out-of-Distribution Generalization](https://arxiv.org/abs/2106.06607)  
Ahuja, Kartik, Ethan Caballero, Dinghuai Zhang, Jean-Christophe Gagnon-Audet, Yoshua Bengio, Ioannis Mitliagkas, and Irina Rish.  
*Neural Information Processing Systems* (**NeurIPS**) 2021.  
[[code]](https://github.com/ahujak/IB-IRM)

- (**MatchDG**) [Domain Generalization using Causal Matching](http://proceedings.mlr.press/v139/mahajan21b.html)  
Mahajan, Divyat, Shruti Tople, and Amit Sharma.  
*International Conference of Machine Learning* (**ICML**) (2021).  
[[code]](https://github.com/microsoft/robustdg)

- (**VBCLS**) [Domain Generalization under Conditional and Label Shifts via Variational Bayesian Inference](https://www.ijcai.org/proceedings/2021/122)  
Liu, Xiaofeng, Bo Hu, Linghao Jin, Xu Han, Fangxu Xing, Jinsong Ouyang, Jun Lu, Georges EL Fakhri, and Jonghye Woo.  
*International Joint Conference on Artificial Intelligence* (**IJCAI**) (2021).  

- (**MixStyle**) [Domain Generalization with MixStyle](https://openreview.net/forum?id=6xHJ37MVxxp)  
Zhou, Kaiyang, Yongxin Yang, Yu Qiao, and Tao Xiang.  
*International Conference on Learning Representations* (**ICLR**) 2021.  
[[code]](https://github.com/KaiyangZhou/mixstyle-release)

- [The Risks of Invariant Risk Minimization](https://openreview.net/forum?id=BbNIbVPJ-42)  
Rosenfeld, Elan, Pradeep Ravikumar, and Andrej Risteski.  
*International Conference on Learning Representations* (**ICLR**) 2021.  

- (**DomainBed**) [In Search of Lost Domain Generalization](https://openreview.net/forum?id=lQdXeXDoWtI)  
Gulrajani, Ishaan, and David Lopez-Paz.  
*International Conference on Learning Representations* (**ICLR**) 2021.  
[[code]](https://github.com/facebookresearch/DomainBed)

- [Domain Generalization by Marginal Transfer Learning](https://www.jmlr.org/papers/volume22/17-679/17-679.pdf)  
Blanchard, Gilles, Aniket Anand Deshmukh, Urun Dogan, Gyemin Lee, and Clayton Scott.  
*Journal of Machine Learning Research* (**JMLR**) (2021).

<h3 id="cv2021">Computer vision venues</h3>

- [Learning to Diversify for Single Domain Generalization](https://arxiv.org/abs/2108.11726)  
Wang, Zijian, Yadan Luo, Ruihong Qiu, Zi Huang, and Mahsa Baktashmotlagh.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2021.  
[[code]](https://github.com/BUserName/Learning_to_diversify)

- (**NSAE**) [Boosting the Generalization Capability in Cross-Domain Few-shot Learning via Noise-enhanced Supervised Autoencoder](https://arxiv.org/abs/2108.05028)  
Liang, Hanwen, Qiong Zhang, Peng Dai, and Juwei Lu.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2021.  

- (**Agr**) [Domain Generalization via Gradient Surgery](https://arxiv.org/abs/2108.01621)  
Mansilla, Lucas, Rodrigo Echeveste, Diego H. Milone, and Enzo Ferrante.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2021.  
[[code]](https://github.com/lucasmansilla/DGvGS)

- (**ASR-Norm**) [Adversarially Adaptive Normalization for Single Domain Generalization](https://arxiv.org/abs/2106.01899)  
Fan, Xinjie, Qifei Wang, Junjie Ke, Feng Yang, Boqing Gong, and Mingyuan Zhou.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

- [A Fourier-based Framework for Domain Generalization](https://arxiv.org/abs/2105.11120)  
Xu, Qinwei, Ruipeng Zhang, Ya Zhang, Yanfeng Wang, and Qi Tian.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

- (**semanticGAN**) [Semantic Segmentation with Generative Models: Semi-Supervised Learning and Strong Out-of-Domain Generalization](https://arxiv.org/abs/2104.05833)  
Li, Daiqing, Junlin Yang, Karsten Kreis, Antonio Torralba, and Sanja Fidler.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  
[[code]](https://nv-tlabs.github.io/semanticGAN/)

- (**RobustNet**) [RobustNet: Improving Domain Generalization in Urban-Scene Segmentation via Instance Selective Whitening](https://arxiv.org/abs/2103.15597)  
Choi, Sungha, Sanghun Jung, Huiwon Yun, Joanne Kim, Seungryong Kim, and Jaegul Choo.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  
[[code]](https://github.com/shachoi/RobustNet)

- (**PDEN**) [Progressive Domain Expansion Network for Single Domain Generalization](https://arxiv.org/abs/2103.16050)  
Li, Lei, Ke Gao, Juan Cao, Ziyao Huang, Yepeng Weng, Xiaoyue Mi, Zhengze Yu, and Xiaoya Li.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  
[[code]](https://github.com/lileicv/PDEN)

- (**ELCFS**) [FedDG: Federated Domain Generalization on Medical Image Segmentation via Episodic Learning in Continuous Frequency Space](https://arxiv.org/abs/2103.06030)  
Liu, Quande, Cheng Chen, Jing Qin, Qi Dou, and Pheng-Ann Heng.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  
[[code]](https://github.com/liuquande/FedDG-ELCFS)

- (**FSDR**) [FSDR: Frequency Space Domain Randomization for Domain Generalization](https://arxiv.org/abs/2103.02370)  
Huang, Jiaxing, Dayan Guan, Aoran Xiao, and Shijian Lu.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

- [Domain Generalization via Inference-time Label-Preserving Target Projections](https://arxiv.org/abs/2103.01134)  
Pandey, Prashant, Mrigank Raman, Sumanth Varambally, and Prathosh AP.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

- [Adaptive Methods for Real-World Domain Generalization](https://arxiv.org/abs/2103.15796)  
Dubey, Abhimanyu, Vignesh Ramanathan, Alex Pentland, and Dhruv Mahajan.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

<h3 id="arxiv2021">arXiv</h3>

- [Iterative Feature Matching: Toward Provable Domain Generalization with Logarithmic Environments.](https://arxiv.org/abs/2106.09913)  
Chen, Yining, Elan Rosenfeld, Mark Sellke, Tengyu Ma, and Andrej Risteski.  
*arXiv preprint arXiv:2106.09913* (2021).  


## Research papers before 2021

<h3 id="pathfinder">Pathfinder</h3>

- [Generalizing from several related classification tasks to a new unlabeled sample](http://papers.nips.cc/paper/4312-generalizing-from-several-related-classification-tasks-to-a-new-unlabeled-sample.pdf)  
Blanchard, Gilles, Gyemin Lee, and Clayton Scott.  
*Advances in neural information processing systems.* (**NIPS**) 2011.

<h3 id="mlbf2021">Machine learning venues</h3>

#### Neural network-based methods

- [Domain Generalization via Entropy Regularization](https://proceedings.neurips.cc/paper/2020/hash/b98249b38337c5088bbc660d8f872d6a-Abstract.html)  
Zhao, Shanshan, Mingming Gong, Tongliang Liu, Huan Fu, and Dacheng Tao.  
*Neural Information Processing Systems* (**NeurIPS**) 2020.  
[[code]](https://github.com/sshan-zhao/DG_via_ER)

- (**LDDG**) [Domain Generalization for Medical Imaging Classification with Linear-Dependency Regularization](https://proceedings.neurips.cc/paper/2020/hash/201d7288b4c18a679e48b31c72c30ded-Abstract.html)  
Li, Haoliang, YuFei Wang, Renjie Wan, Shiqi Wang, Tie-Qiang Li, and Alex C. Kot.  
*Neural Information Processing Systems* (**NeurIPS**) 2020.  
[[code]](https://github.com/wyf0912/LDDG)

- (**CSD**) [Efficient Domain Generalization via Common-Specific Low-Rank Decomposition](https://arxiv.org/abs/2003.12815)  
Vihari Piratla, Praneeth Netrapalli, Sunita Sarawagi  
*International Conference on Machine Learning* (**ICML**) 2020.  
[[code]](https://github.com/vihari/CSD)

- (**GCFN**) [Generalized Convolutional Forest Networks for Domain Generalization and Visual Recognition.](https://openreview.net/pdf?id=H1lxVyStPH)  
Ryu, Jongbin, Gitaek Kwon, Ming-Hsuan Yang, and Jongwoo Lim.  
*International Conference on Learning Representations* (**ICLR**) 2020.

- (**MASF**) [Domain Generalization via Model-Agnostic Learning of Semantic Features.](https://arxiv.org/abs/1910.13580)  
Qi Dou, Daniel C. Castro, Konstantinos Kamnitsas, and Ben Glocker.  
*Advances in Neural Information Processing Systems* (**NeurIPS**) 2019.   
[[code]](https://github.com/biomedia-mira/masf)

- (**CAADA**) [Correlation-aware Adversarial Domain Adaptation and Generalization](https://www.sciencedirect.com/science/article/pii/S003132031930425X)  
Rahman, Mohammad Mahfujur, Clinton Fookes, Mahsa Baktashmotlagh, and Sridha Sridharan.  
*Pattern Recognition* (2019): 107124.

- (**CROSSGRAD**) [Generalizing Across Domains via Cross-Gradient Training](https://openreview.net/pdf?id=r1Dx7fbCW)  
Shankar, Shiv, Vihari Piratla, Soumen Chakrabarti, Siddhartha Chaudhuri, Preethi Jyothi, and Sunita Sarawagi.  
*International Conference on Learning Representations* (**ICLR**) 2018.

- (**MetaReg**) [MetaReg: Towards Domain Generalization using Meta-Regularization](http://papers.nips.cc/paper/7378-metareg-towards-domain-generalization-using-meta-regularization.pdf)  
Balaji, Yogesh, Swami Sankaranarayanan, and Rama Chellappa.  
*Advances in Neural Information Processing Systems* (**NeurIPS**) 2018.

- (**MLDG**) [Learning to generalize: Meta-learning for domain generalization](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16595/16558)  
Li, Da, Yongxin Yang, Yi-Zhe Song, and Timothy M. Hospedales.  
*AAAI Conference on Artificial Intelligence* (**AAAI**) 2018.  
[[code]](https://github.com/HAHA-DL/MLDG)

#### Kernel-based methods

- (**MDA**) [Domain Generalization via Multidomain Discriminant Analysis](http://auai.org/uai2019/proceedings/papers/101.pdf)  
Hu, Shoubo, Kun Zhang, Zhitang Chen, Laiwan Chan.  
*Conference on Uncertainty in Artificial Intelligence* (**UAI**) 2019.  
[[code]](https://github.com/amber0309/Multidomain-Discriminant-Analysis)

- (**CIDG**) [Domain Generalization via Conditional Invariant Representation](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16595/16558)  
Li, Ya, Mingming Gong, Xinmei Tian, Tongliang Liu, and Dacheng Tao.  
*AAAI Conference on Artificial Intelligence* (**AAAI**) 2018.  
[[code]](https://mingming-gong.github.io/papers/CIDG.zip)

- (**SCA**) [Scatter component analysis: A unified framework for domain adaptation and domain generalization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7542175)  
Ghifary, Muhammad, David Balduzzi, W. Bastiaan Kleijn, and Mengjie Zhang.  
*IEEE Transactions on Pattern Analysis & Machine Intelligence* (**TPAMI**) 39.7 (2016): 1414-1430.  
[[code(unofficial)]](https://github.com/amber0309/SCA)

- (**DICA**) [Domain generalization via invariant feature representation](http://proceedings.mlr.press/v28/muandet13.pdf)  
Muandet, Krikamol, David Balduzzi, and Bernhard Schölkopf.  
*International Conference on Machine Learning* (**ICML**) 2013.  
[[code]](http://krikamol.org/research/codes/dica.zip)

<h3 id="cvbf2021">Computer vision venues</h3>

#### Autoencoder-based methods

- (**MMD-AAE**) [Domain generalization with adversarial feature learning](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2932.pdf)  
Li, Haoliang, Sinno Jialin Pan, Shiqi Wang, and Alex C. Kot.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2018.

- (**MTAE**) [Domain generalization for object recognition with multi-task autoencoders](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Ghifary_Domain_Generalization_for_ICCV_2015_paper.pdf)  
Ghifary, Muhammad, W. Bastiaan Kleijn, Mengjie Zhang, and David Balduzzi.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2015.  
[[code]](https://github.com/ghif/mtae)

#### Deep neural network-based methods

- (**MetaVIB**) [Learning to Learn with Variational Information Bottleneck for Domain Generalization](https://arxiv.org/abs/2007.07645)  
Du, Yingjun, Jun Xu, Huan Xiong, Qiang Qiu, Xiantong Zhen, Cees GM Snoek, and Ling Shao.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.  

- (**DMG**) [Learning to Balance Specificity and Invariance for In and Out of Domain Generalization](https://arxiv.org/abs/2008.12839)  
Chattopadhyay, Prithvijit, Yogesh Balaji, and Judy Hoffman.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.  
[[code]](https://github.com/prithv1/DMG)

- (**DSON**) [Learning to Optimize Domain Specific Normalization for Domain Generalization](https://arxiv.org/abs/1907.04275)  
Seonguk Seo, Yumin Suh, Dongwan Kim, Geeho Kim, Jongwoo Han and ohyung Han.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.  

- (**EISNet**) [Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization](https://arxiv.org/abs/2007.09316)  
Wang, Shujun, Lequan Yu, Caizi Li, Chi-Wing Fu, and Pheng-Ann Heng.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.  
[[code]](https://github.com/EmmaW8/EISNet)

- (**MetaVIB**) [Learning to Learn with Variational Information Bottleneck for Domain Generalization](https://arxiv.org/abs/2007.07645)  
Du, Yingjun, Jun Xu, Huan Xiong, Qiang Qiu, Xiantong Zhen, Cees GM Snoek, and Ling Shao.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.

- (**RSC**) [Self-Challenging Improves Cross-Domain Generalization](https://arxiv.org/abs/2007.02454)  
Huang, Zeyi, Haohan Wang, Eric P. Xing, and Dong Huang.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.

- (**L2A-OT**) [Learning to Generate Novel Domains for Domain Generalization](https://arxiv.org/abs/2007.03304)  
Zhou, Kaiyang, Yongxin Yang, Timothy Hospedales, and Tao Xiang.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2020.

- (**SSDG**) [Single-Side Domain Generalization for Face Anti-Spoofing](https://arxiv.org/abs/2004.14043)  
Jia, Yunpei, Jie Zhang, Shiguang Shan, and Xilin Chen.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2020.  
[[code]](https://github.com/taylover-pei/SSDG-CVPR2020)

- (**Epi-FCR**) [Episodic Training for Domain Generalization](https://arxiv.org/abs/1902.00113)  
Li, Da, Jianshu Zhang, Yongxin Yang, Cong Liu, Yi-Zhe Song, and Timothy M. Hospedales.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2019.  
[[code]](https://github.com/HAHA-DL/Episodic-DG)

- (**JiGen**) [Domain Generalization by Solving Jigsaw Puzzles](https://arxiv.org/abs/1903.06864)  
Carlucci, Fabio Maria, Antonio D'Innocente, Silvia Bucci, Barbara Caputo, and Tatiana Tommasi.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2019.  
[[code]](https://github.com/fmcarlucci/JigenDG)

- (**CIDDG**) [Deep Domain Generalization via Conditional Invariant Adversarial Networks](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf)  
Li, Ya, Xinmei Tian, Mingming Gong, Yajing Liu, Tongliang Liu, Kun Zhang, and Dacheng Tao.  
*Proceedings of the European Conference on Computer Vision* (**ECCV**) 2018.

- [Deep Domain Generalization With Structured Low-Rank Constraint](https://ieeexplore.ieee.org/document/8053784)  
Ding, Zhengming, and Yun Fu.  
*IEEE Transactions on Image Processing* (**TIP**) 27.1 (2017): 304-313.

- (**CCSA**) [Unified deep supervised domain adaptation and generalization](http://openaccess.thecvf.com/content_ICCV_2017/papers/Motiian_Unified_Deep_Supervised_ICCV_2017_paper.pdf)  
Motiian, Saeid, Marco Piccirilli, Donald A. Adjeroh, and Gianfranco Doretto.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2017.  
[[code]](https://github.com/samotiian/CCSA)

- [Deeper, broader and artier domain generalization](https://ieeexplore.ieee.org/abstract/document/8237853)  
Li, Da, Yongxin Yang, Yi-Zhe Song, and Timothy M. Hospedales.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2017.  
[[code]](http://www.eecs.qmul.ac.uk/~dl307/project_iccv2017)

#### Metric learning-based methods

- (**UML**) [Unbiased metric learning: On the utilization of multiple datasets and web images for softening bias](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Fang_Unbiased_Metric_Learning_2013_ICCV_paper.pdf)  
Fang, Chen, Ye Xu, and Daniel N. Rockmore.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2013.

#### Support vector machine (SVM)-based methods

- (**MVDG**) [Multi-view domain generalization for visual recognition](https://ieeexplore.ieee.org/document/7410834)  
Niu, Li, Wen Li, and Dong Xu.  
*Proceedings of the IEEE International Conference on Computer Vision* (**ICCV**) 2015.

- (**LRE-SVM**) [Exploiting low-rank structure from latent domains for domain generalization](https://link.springer.com/chapter/10.1007/978-3-319-10578-9_41)  
Xu, Zheng, Wen Li, Li Niu, and Dong Xu.  
*European Conference on Computer Vision* (**ECCV**) 2014.  
[[code]](http://www.vision.ee.ethz.ch/~liwenw/papers/Xu_ECCV2014_codes.zip)

- (**Undo-Bias**) [Undoing the damage of dataset bias](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_12)  
Khosla, Aditya, Tinghui Zhou, Tomasz Malisiewicz, Alexei A. Efros, and Antonio Torralba.  
*European Conference on Computer Vision* (**ECCV**) 2012.  
[[code]](https://github.com/adikhosla/undoing-bias/archive/master.zip)

<h3 id="arxivbf2021">arXiv</h3>

- (**NILE**) [A causal framework for distribution generalization](https://arxiv.org/abs/2006.07433)    
Christiansen, Rune, Niklas Pfister, Martin Emil Jakobsen, Nicola Gnecco, and Jonas Peters.  
*arXiv preprint arXiv:2006.07433* (2020).  

- (**REx**) [Out-of-distribution generalization via risk extrapolation](https://arxiv.org/abs/2003.00688)    
Krueger, David, Ethan Caballero, Joern-Henrik Jacobsen, Amy Zhang, Jonathan Binas, Remi Le Priol, and Aaron Courville.  
*arXiv preprint arXiv:2003.00688* (2020).  

- (**RVP**) [Risk Variance Penalization: From Distributional Robustness to Causality](https://arxiv.org/abs/2006.07544)    
Xie, Chuanlong, Fei Chen, Yue Liu, and Zhenguo Li.    
*arXiv preprint arXiv:2006.07544* (2020).  

- [Generalization and Invariances in the Presence of Unobserved Confounding](https://arxiv.org/abs/2007.10653)  
Bellot, Alexis and van der Schaar, Mihaela.  
*arXiv preprint arXiv:2007.10653* (2020).  

- (**FAR**) [Feature Alignment and Restoration for Domain Generalization and Adaptation](https://arxiv.org/abs/2006.12009)  
Jin, Xin, Cuiling Lan, Wenjun Zeng, and Zhibo Chen.  
*arXiv preprint arXiv:2006.12009* (2020).  

- [Frustratingly Simple Domain Generalization via Image Stylization](https://arxiv.org/abs/2006.11207)  
Somavarapu, Nathan, Chih-Yao Ma, and Zsolt Kira.  
*arXiv preprint arXiv:2006.11207* (2020).  
[[code]](https://github.com/GT-RIPL/DomainGeneralization-Stylization)

- (**RVR**) [Representation via Representations: Domain Generalization via Adversarially Learned Invariant Representations](https://arxiv.org/abs/2006.11478)  
Deng, Zhun, Frances Ding, Cynthia Dwork, Rachel Hong, Giovanni Parmigiani, Prasad Patil, and Pragya Sur.  
*arXiv preprint arXiv:2006.11478* (2020).  

- (**G2DM**) [Generalizing to unseen Domains via Distribution Matching](https://arxiv.org/abs/1911.00804)  
Isabela Albuquerque, João Monteiro, Mohammad Darvishi, Tiago H. Falk, Ioannis Mitliagkas  
*arXiv preprint arXiv:1911.00804* (2019).  
[[code]](https://github.com/belaalb/TI-DG)

- [Invariant Risk Minimization](https://arxiv.org/abs/1907.02893)  
Arjovsky, Martin and Bottou, Leon and Gulrajani, Ishaan and Lopez-Paz, David.  
*arXiv preprint arXiv:1907.02893* (2019).  
[[code]](https://github.com/facebookresearch/InvariantRiskMinimization)

- [A Generalization Error Bound for Multi-class Domain Generalization](https://arxiv.org/abs/1905.10392)  
Deshmukh, Aniket Anand, Yunwen Lei, Srinagesh Sharma, Urun Dogan, James W. Cutler, and Clayton Scott.  
*arXiv preprint arXiv:1905.10392* (2019).  
[[code]](https://www.dropbox.com/sh/bls758ro5762mtf/AACbn3UXJItY9uwtmCAdi7E3a?dl=0)

- [Domain generalization by marginal transfer learning](https://arxiv.org/abs/1711.07910)  
Blanchard, Gilles, Aniket Anand Deshmukh, Urun Dogan, Gyemin Lee, and Clayton Scott.  
*arXiv preprint arXiv:1711.07910* (2017).  
[[code]](https://github.com/aniketde/DomainGeneralizationMarginal)

-----

## Datasets

|     Dataset    |        #Sample |       #Feature      | #Class |   Subdomain  | Reference |
|:--------------:|:-------:|:-------------------:|:------:|:------------:|:--------:|
| [Office+Caltech](#Office+Caltech) |    2533  | SURF: 800, DeCAF: 4096 |   10   |  A, W, D, C  |   [[1]](#1)       |
|     [VOC2007](#vlcs)    |          3376  |      DeCAF: 4096     |    5   |       V      |    [[2]](#2)      |
|     [LabelMe](#vlcs)    |          2656  |      DeCAF: 4096     |    5   |       L      |    [[3]](#3)      |
|   [Caltech101](#vlcs)   |          1415  |      DeCAF: 4096     |    5   |       C      |    [[4]](#4)      |
|      [SUN09](#vlcs)     |          3282  |      DeCAF: 4096     |    5   |       S      |    [[5]](#5)      |
| [PACS](#PACS) |    9991  | ResNet: 512, AlexNet: 4096 |   7   |  Photo, Art Painting, Cartoon, Sketch  |   [[6]](#6)       |

### Office-Caltech

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

### ImageNet-C

#### Introduction
Fifteen Corruptions spanning noise, blur, weather, and digital corruptions.
1000 common classes, the ImageNet-1K classes. The paper is [here](https://arxiv.org/abs/1903.12261).

#### Download
Download links are available at https://github.com/hendrycks/robustness/

### ImageNet-R

#### Introduction
ImageNet-R(endition) contains art, cartoons, deviantart, graffiti, embroidery, graphics, origami, paintings, patterns, plastic objects, plush objects, sculptures, sketches, tattoos, toys, and video game renditions of ImageNet classes.

ImageNet-R has renditions of 200 ImageNet classes resulting in 30,000 images. The paper is [here](https://arxiv.org/abs/2006.16241).

#### Download
Download links are available at https://github.com/hendrycks/imagenet-r

### PACS

#### Introduction

Four domains: photo, art painting, cartoon, and sketch.  
Seven common classes: dog, elephant, horse, giraffe, guitar, house, and person. 

#### Download

Download the PACS dataset [[Google Drive](https://drive.google.com/drive/folders/0B6x7gtvErXgfUU1WcGY5SzdwZVk)]

### Geo-YFCC

#### Introduction

This dataset contains a subset of the popular YFCC100M dataset, that are partitioned based on the images' country of origin. 

#### Download

The infomation of Geo-YFCC dataset is available at https://github.com/abhimanyudubey/GeoYFCC


-----

## DG variants

- (**RaMoE**) [Generalizable Person Re-identification with Relevance-aware Mixture of Experts](https://openaccess.thecvf.com/content/CVPR2021/papers/Dai_Generalizable_Person_Re-Identification_With_Relevance-Aware_Mixture_of_Experts_CVPR_2021_paper.pdf)  
Dai, Yongxing, Xiaotong Li, Jun Liu, Zekun Tong, and Ling-Yu Duan.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2021.  

- [Zero Shot Domain Generalization](https://arxiv.org/abs/2008.07443)  
Udit Maniyar, Joseph K J, Aniket Anand Deshmukh, Urun Dogan, Vineeth N Balasubramanian  
*British Machine Vision Conference* (**BMVC**) 2020.  

- [Exchanging Lessons Between Algorithmic Fairness and Domain Generalization](https://arxiv.org/abs/2010.07249)  
Creager, Elliot, Jörn-Henrik Jacobsen, and Richard Zemel.  
*arXiv preprint arXiv:2010.07249* 2020.  

- [Learning to Learn Single Domain Generalization](https://arxiv.org/abs/2003.13216)  
Fengchun Qiao, Long Zhao, Xi Peng.  
*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR**) 2020.  

- [Domain Generalization Using a Mixture of Multiple Latent Domains](https://aaai.org/Papers/AAAI/2020GB/AAAI-MatsuuraT.3100.pdf)  
Toshihiko Matsuura, Tatsuya Harada.  
*AAAI Conference on Artificial Intelligence* (**AAAI**) 2020.  
[[code]](https://github.com/mil-tokyo/dg_mmld)

- (**APN**) [Adversarial Pyramid Network for Video Domain Generalization](https://arxiv.org/abs/1912.03716)  
Zhiyu Yao, Yunbo Wang, Xingqiang Du, Mingsheng Long, Jianmin Wang  
*arXiv preprint arXiv:1912.03716* (2019).  

- (**FC**) [Feature-Critic Networks for Heterogeneous Domain Generalization](https://arxiv.org/abs/1901.11448)  
Li, Yiying, Yongxin Yang, Wei Zhou, and Timothy M. Hospedales  
*International Conference on Machine Learning* (**ICML**) 2019.  
[[code]](https://github.com/liyiying/Feature_Critic)

- [Learning Robust Representations by Projecting Superficial Statistics Out](https://openreview.net/pdf?id=rJEjjoR9K7)  
Wang, Haohan, Zexue He, Zachary C. Lipton, and Eric P. Xing.  
*International Conference on Learning Representations* (**ICLR**) 2019.

-----

## References
1. <a name="1"></a> Gong, Boqing, Yuan Shi, Fei Sha, and Kristen Grauman. "Geodesic flow kernel for unsupervised domain adaptation." In Computer Vision and Pattern Recognition (CVPR), 2012 IEEE Conference on, pp. 2066-2073. IEEE, 2012.

2. <a name="2"></a> Everingham, Mark, Luc Van Gool, Christopher KI Williams, John Winn, and Andrew Zisserman. "The pascal visual object classes (voc) challenge." International journal of computer vision 88, no. 2 (2010): 303-338.

3. <a name="3"></a> Russell, Bryan C., Antonio Torralba, Kevin P. Murphy, and William T. Freeman. "LabelMe: a database and web-based tool for image annotation." International journal of computer vision 77, no. 1-3 (2008): 157-173.

4. <a name="4"></a> Griffin, Gregory, Alex Holub, and Pietro Perona. "Caltech-256 object category dataset." (2007).

5. <a name="5"></a> Choi, Myung Jin, Joseph J. Lim, Antonio Torralba, and Alan S. Willsky. "Exploiting hierarchical context on a large database of object categories." (2010).

6. <a name="6"></a> Da Li, Yongxin Yang, Yi-Zhe Song, and Timothy M Hospedales.  "Deeper, broader and artier domaingeneralization." InProceedings of the IEEE international conference on computer vision, pages 5542–5550,2017.10. (2017).

-----

## Contact

* **Shoubo Hu** - shoubo.sub [at] gmail.com

See also the list of [contributors](https://github.com/amber0309/Domain-generalization/graphs/contributors) who participated in this project.

-----

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
