​		个人比较关注视觉惯性组合方案，更细化一些，比较关注鲁棒快速初始化的方案和视觉重定位方案，有余力的情况下，希望接触struct slam

## My study plan:

1. #### se2lam（地面车辆位姿估计的视觉里程计）

   - **论文**：Zheng F, Liu Y H. [**Visual-Odometric Localization and Mapping for Ground Vehicles Using SE (2)-XYZ Constraints**](https://ieeexplore.ieee.org/abstract/document/8793928)[C]//2019 International Conference on Robotics and Automation (**ICRA**). IEEE, **2019**: 3556-3562.
   - **代码**：https://github.com/izhengfan/se2lam

2. #### . CPI（视惯融合的封闭式预积分）

   - **论文**：Eckenhoff K, Geneva P, Huang G. [**Closed-form preintegration methods for graph-based visual–inertial navigation**](http://sage.cnpereading.com/paragraph/article/10.1177/0278364919835021)[J]. The International Journal of Robotics Research, 2018.
   - **代码**：https://github.com/rpng/cpi ；[**Video**](https://www.youtube.com/watch?v=yIgQX2SH_pI)

3. ####  vilib（VIO前端库）

   - **论文**：Nagy B，Foehn P，Scaramuzza D. [**比FAST更快：用于高速VIO的GPU加速前端**](https://arxiv.org/pdf/2003.13493) [J]。预印本的arXiv的arXiv：2003.13493，**2020**。
   - **代码**：[https](https://github.com/uzh-rpg/vilib) : [//github.com/uzh-rpg/vilib](https://github.com/uzh-rpg/vilib)

4. #### TUM Basalt

   - **论文**：Usenko V, Demmel N, Schubert D, et al. [Visual-inertial mapping with non-linear factor recovery](https://link.zhihu.com/?target=https%3A//arxiv.org/pdf/1904.06504.pdf)[J]. IEEE Robotics and Automation Letters, **2019**.
   - **代码**：[https://github.com/VladyslavUsenko/basalt-mirror](https://link.zhihu.com/?target=https%3A//github.com/VladyslavUsenko/basalt-mirror) ；[Video](https://link.zhihu.com/?target=https%3A//www.youtube.com/watch%3Fv%3Dr3CJ2JP75Tc)；[Project Page](https://link.zhihu.com/?target=https%3A//vision.in.tum.de/research/vslam/basalt)

5.  Campos C, MM M J, Tardós J D. [**Fast and Robust Initialization for Visual-Inertial SLAM**](https://arxiv.org/pdf/1908.10653.pdf)[C]//2019 International Conference on Robotics and Automation (**ICRA**). IEEE, **2019**: 1288-1294.

   - 视惯 SLAM 快速鲁棒的初始化
   - 西班牙萨拉戈萨大学，ORB-SLAM 课题组

## 工具箱学习：

1. #### 初步优化库

   - **GTSAM**：[https](https://github.com/borglab/gtsam) : [//github.com/borglab/gtsam](https://github.com/borglab/gtsam)；[官网](https://gtsam.org/)
   - **g2o**：[https](https://github.com/RainerKuemmerle/g2o) : [//github.com/RainerKuemmerle/g2o](https://github.com/RainerKuemmerle/g2o)
   - **ceres**：[http](http://ceres-solver.org/) : [//ceres-solver.org/](http://ceres-solver.org/)

2. #### ICE-BA

   - **论文**：Liu H, Chen M, Zhang G, et al. [**Ice-ba: Incremental, consistent and efficient bundle adjustment for visual-inertial slam**](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_ICE-BA_Incremental_Consistent_CVPR_2018_paper.pdf)[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. **2018**: 1974-1982.
   - **代码**：https://github.com/baidu/ICE-BA

3. #### minisam（因子图最小二乘优化框架）

   - **论文**：Dong J, Lv Z. [**miniSAM: A Flexible Factor Graph Non-linear Least Squares Optimization Framework**](https://arxiv.org/pdf/1909.00903.pdf)[J]. arXiv preprint arXiv:1909.00903, **2019**.
   - **代码**：https://github.com/dongjing3309/minisam ； [文档](https://minisam.readthedocs.io/)

4. #### SA-SHAGO（几何基元图优化）

   - **论文**：Aloise I, Della Corte B, Nardi F, et al. [**Systematic Handling of Heterogeneous Geometric Primitives in Graph-SLAM Optimization**](http://rss2019.informatik.uni-freiburg.de/papers/0285_FI.pdf)[J]. IEEE Robotics and Automation Letters, **2019**, 4(3): 2738-2745.
   - **代码**：https://srrg.gitlab.io/sashago-website/index.html#

5. ####  MH-iSAM2（SLAM 优化器）

   - **论文**：Hsiao M, Kaess M. [**MH-iSAM2: Multi-hypothesis iSAM using Bayes Tree and Hypo-tree**](http://www.cs.cmu.edu/~kaess/pub/Hsiao19icra.pdf)[C]//2019 International Conference on Robotics and Automation (ICRA). IEEE, **2019**: 1274-1280.
   - **代码**：https://bitbucket.org/rpl_cmu/mh-isam2_lib/src/master/

6. #### MOLA（用于定位和建图的模块化优化框架）

   - **论文**：Blanco-Claraco J L. [**A Modular Optimization Framework for Localization and Mapping**](http://roboticsproceedings.org/rss15/p43.pdf)[J]. Proc. of Robotics: Science and Systems (RSS), FreiburgimBreisgau, Germany, **2019**, 2.
   - **代码**：https://github.com/MOLAorg/mola ；[**Video**](https://www.youtube.com/watch?v=Bb92aMBJR44) ；[使用文档](https://docs.mola-slam.org/latest/)

## 感兴趣的论文：

1. Lee W, Eckenhoff K, Geneva P, et al. [**Intermittent GPS-aided VIO: Online Initialization and Calibration**](https://www.researchgate.net/profile/Patrick_Geneva/publication/341713067_Intermittent_GPS-aided_VIO_Online_Initialization_and_Calibration/links/5ed0063b299bf1c67d26cf5d/Intermittent-GPS-aided-VIO-Online-Initialization-and-Calibration.pdf)[J].**2020**
   - 间歇性 GPS 辅助 VIO：在线初始化和校准
   - 特拉华大学，黄国权教授
2. Nam D V, Gon-Woo K. [**Robust Stereo Visual Inertial Navigation System Based on Multi-Stage Outlier Removal in Dynamic Environments**](https://www.mdpi.com/1424-8220/20/10/2922)[J]. Sensors, **2020**, 20(10): 2922.
   - 动态环境中基于多阶段离群值剔除的鲁棒双目视觉惯性导航系统
   - 韩国忠北国立大学，开源期刊，[作者主页](https://sites.google.com/view/dinhnam/)
3.  [**A Survey on Deep Learning for Localization and Mapping: Towards the Age of Spatial Machine Intelligence**](https://arxiv.org/abs/2006.12567)[J]. arXiv preprint arXiv:2006.12567, **2020**.
   - **深度学习用于定位和建图的调研：走向空间机器智能时代**
   - 牛津大学；所有涉及到的**论文的列表**：[Github](https://github.com/changhao-chen/deep-learning-localization-mapping)
4.  Wang W, Zhu D, Wang X, et al. [**TartanAir: A Dataset to Push the Limits of Visual SLAM**](https://arxiv.org/pdf/2003.14338)[J]. arXiv preprint arXiv:2003.14338, **2020**.
   - **TartanAir：突破视觉 SLAM 极限的数据集**
   - CMU，港中文；数据集公开：http://theairlab.org/tartanair-dataset/
5. Du S, Guo H, Chen Y, et al. [**GPO: Global Plane Optimization for Fast and Accurate Monocular SLAM Initialization**](https://arxiv.org/abs/2004.12051)[J]. ICRA **2020**.
   - 准确快速单目 SLAM 初始化的全局平面优化
   - 中科院自动化所，字节跳动
6. Jung J H, Heo S, Park C G. [**Observability Analysis of IMU Intrinsic Parameters in Stereo Visual-Inertial Odometry**](https://ieeexplore.ieee.org/abstract/document/9056527/)[J]. IEEE Transactions on Instrumentation and Measurement, **2020**.
   - 立体视觉惯性里程计中IMU内部参数的可观察性分析
   - 韩国首尔大学；期刊：中科院三区，JCR Q2，IF 3.0
7.  Gomez-Ojeda R. [**Robust Visual SLAM in Challenging Environments with Low-texture and Dynamic Illumination**](https://riuma.uma.es/xmlui/handle/10630/19479)[J]. **2020**.
   - **低纹理和动态光照挑战环境下的鲁棒视觉 SLAM**
   - 西班牙马拉加大学，**点线 SLAM 作者的博士学位论文**
8. Nagy B, Foehn P, Scaramuzza D. [**Faster than FAST: GPU-Accelerated Frontend for High-Speed VIO**](https://arxiv.org/pdf/2003.13493)[J]. arXiv preprint arXiv:2003.13493, **2020**.
   - **用于高速 VIO 的前端 GPU 加速**
   - 苏黎世大学、苏黎世联邦理工；[**代码开源**](https://github.com/uzh-rpg/vilib)
9.  Debeunne C, Vivet D. [**A Review of Visual-LiDAR Fusion based Simultaneous Localization and Mapping**](https://www.mdpi.com/1424-8220/20/7/2068)[J]. Sensors, **2020**, 20(7): 2068.
   - 视觉-激光 SLAM 综述
   - 图卢兹大学；开源期刊，中科院三区，JCR Q2Q3
10. Zhao Y, Smith J S, Karumanchi S H, et al. [**Closed-Loop Benchmarking of Stereo Visual-Inertial SLAM Systems: Understanding the Impact of Drift and Latency on Tracking Accuracy**](https://arxiv.org/pdf/2003.01317.pdf)[C]. **ICRA 2020**.
    - 双目视觉里程计闭环检测基准系统：关于测试漂移和延迟对跟踪准确性的影响
    - 佐治亚理工学院 IVALab [ROBO SLAM](https://ivalab.github.io/RoboSLAM/public/research/)；[**代码开源**](https://github.com/ivalab/meta_ClosedLoopBench)；[作者主页](https://sites.google.com/site/zhaoyipu/)
11.  Cheng J, Zhang H, Meng M Q H. [**Improving Visual Localization Accuracy in Dynamic Environments Based on Dynamic Region Removal**](https://ieeexplore.ieee.org/abstract/document/8972551/)[J]. IEEE Transactions on Automation Science and Engineering, **2020**.
    - 通过动态区域剔除来提升动态环境中视觉定位的准确性
    - 港中文；中科院二区 JCR Q1
12. WANG, Cheng, et al. [**NEAR: The NetEase AR Oriented Visual Inertial Dataset**](https://ieeexplore.ieee.org/abstract/document/8951909). In: 2019 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct). IEEE, **2019**. p. 366-371.
    - **面向视觉惯导数据集的网易 AR**
    - 网易，[**数据集地址**](https://github.com/EZXR-Research/NEAR-VI-Dataset)
13. Speciale P. [**Novel Geometric Constraints for 3D Computer Vision Applications**](https://www.research-collection.ethz.ch/handle/20.500.11850/380042)[D]. ETH Zurich, **2019**.
    - **适用于 3D 计算机视觉应用的新型几何约束**
    - 苏黎世联邦理工博士学位论文、微软，[Google Scholar](https://scholar.google.com/citations?user=-LEhIh0AAAAJ&hl=zh-CN&oi=sra)
14. An S, Che G, Zhou F, et al. [**Fast and Incremental Loop Closure Detection Using Proximity Graphs**](https://arxiv.org/pdf/1911.10752.pdf)[J]. arXiv preprint arXiv:1911.10752, **2019**.
    - **使用邻近图的快速增量式闭环检测**
    - 京东、北航，[代码开源](https://github.com/AnshanTJU/FILD)
15.  [Bundle Adjustment Revisited](https://arxiv.org/pdf/1912.03858.pdf)
    - **再谈 BA**
    - 北京大学
16. Tschopp F, Riner M, Fehr M, et al. [**VersaVIS: An Open Versatile Multi-Camera Visual-Inertial Sensor Suite**](https://arxiv.org/pdf/1912.02469.pdf)[J]. arXiv preprint arXiv:1912.02469, **2019**.
    - **VersaVIS：开源多功能多相机的视觉惯性传感器套件**
    - 苏黎世联邦理工学院，[**代码开源**](https://github.com/ethz-asl/versavis)
17.  Barrau A, Bonnabel S. [**A Mathematical Framework for IMU Error Propagation with Applications to Preintegration**](https://hal-mines-paristech.archives-ouvertes.fr/hal-02394774/document)[J]. **2019**.
    - IMU错误传播的数学框架及其在预积分中的应用
    - PSL Research University
18. Sartipi K, DuToit R C, Cobar C B, et al. [**Decentralized visual-inertial localization and mapping on mobile devices for augmented reality**](http://mars.cs.umn.edu/tr/decentralizedvi19.pdf)[R]. Google, Tech. Rep., Aug. **2019**.[Online]. Available: [http://mars](http://mars/). cs. umn. edu/tr/decentralizedvi19. pdf.
    - 用于移动设备增强现实的分布式视觉惯导定位与建图
    - 明尼苏达大学
19. Wang H, Li J, Ran M, et al. [**Fast Loop Closure Detection via Binary Content**](https://ieeexplore.ieee.org/abstract/document/8899937)[C]//2019 IEEE 15th International Conference on Control and Automation (**ICCA**). IEEE, **2019**: 1563-1568.
    - 通过二进制内容进行快速闭环检测
    - 南洋理工大学，ICCV 会议
20. Zhang M, Zuo X, Chen Y, et al. [**Localization for Ground Robots: On Manifold Representation, Integration, Re-Parameterization, and Optimization**](https://arxiv.org/pdf/1909.03423.pdf)[J]. arXiv preprint arXiv:1909.03423, **2019**.
    - 地面机器人的定位：流形表示，积分，重新参数化和优化
    - 阿里巴巴人工智能实验室
21. Kirsanov P, Gaskarov A, Konokhov F, et al. [**DISCOMAN: Dataset of Indoor SCenes for Odometry, Mapping And Navigation**](https://arxiv.org/pdf/1909.12146.pdf)[J]. arXiv preprint arXiv:1909.12146, **2019**.
    - DISCOMAN：用于里程计、制图和导航的室内场景数据集
    - 三星 AI 中心，数据集随论文正式发表放出
22. Liao Z, Shi J, Qi X, et al. [**Coarse-To-Fine Visual Localization Using Semantic Compact Map**](https://arxiv.org/pdf/1910.04936.pdf)[J]. arXiv preprint arXiv:1910.04936, **2019**.
    - 使用语义紧凑图的从粗糙到精细的视觉定位
    - 北航，face++
23. Zhou Q, Sattler T, Pollefeys M, et al. [**To Learn or Not to Learn: Visual Localization from Essential Matrices**](https://arxiv.org/pdf/1908.01293.pdf)[J]. arXiv preprint arXiv:1908.01293, 2019.
    - 学习或非学习的方法：基础矩阵用于视觉定位
    - 慕尼黑、苏黎世
24. Schenk F, Fraundorfer F. [**RESLAM: A real-time robust edge-based SLAM system**](https://pure.tugraz.at/ws/portalfiles/portal/23662547/schenk_icra_2019.pdf)[C]//IEEE International Conference on Robotics and Automation(**ICRA**) 2019. **2019**.
    - 一种实时稳健的基于边缘的SLAM系统
    - 奥地利格拉茨科技大学  [Google Scholar](https://scholar.google.com/citations?user=IbK5KvYAAAAJ&hl=zh-CN&oi=sra)
    - [**代码开源**](https://github.com/fabianschenk/RESLAM)  [项目主页](https://graz.pure.elsevier.com/en/publications/reslam-a-real-time-robust-edge-based-slam-system)
25. Eckenhoff K, Geneva P, Huang G. [**Closed-form preintegration methods for graph-based visual–inertial navigation**](http://sage.cnpereading.com/paragraph/article/10.1177/0278364919835021)[J]. The International Journal of Robotics Research, 2018.
    - 基于图的视觉惯性导航的**封闭式预积分**方法
    - 特拉华大学   [代码开源](https://github.com/rpng/cpi)
26. Usenko V, Demmel N, Schubert D, et al. [**Visual-Inertial Mapping with Non-Linear Factor Recovery**](https://arxiv.org/pdf/1904.06504.pdf)[J]. arXiv preprint arXiv:1904.06504, **2019**.
    - 具有非线性因子恢复的**视觉-惯导建图**
    - 慕尼黑工业大学   [Google Scholor](https://scholar.google.com/citations?user=APTNKjoAAAAJ&hl=zh-CN&oi=sra)
27. Ling Y, Shen S. [**Real‐time dense mapping for online processing and navigation**](https://onlinelibrary.wiley.com/doi/pdf/10.1002/rob.21868)[J]. Journal of Field Robotics.
    - 用于在线处理和导航的实时**密集建图**
    - **沈邵劼**老师团队  [**Github 代码开源**](https://github.com/ygling2008/dense_mapping)
28. Duff T, Kohn K, Leykin A, et al. [**PLMP-Point-Line Minimal Problems in Complete Multi-View Visibility**](https://arxiv.org/pdf/1903.10008.pdf)[J]. arXiv preprint arXiv:1903.10008, **2019**.
    - PLMP：多视图中的**点线最小化**
    - 佐治亚理工学院
29.  Jinyu Li, Bangbang Yang, Danpeng Chen, Nan Wang, Guofeng Zhang*, Hujun Bao*. [**Survey and Evaluation of Monocular Visual-Inertial SLAM Algorithms for Augmented Reality**](http://vr-ih.com/vrih/resource/latest_accept/267415796648960.pdf)[J] Journal of Virtual Reality & Intelligent Hardware **2019**.
    - 应用于**增强现实**的**单目 VI-SLAM** 算法调研与评估
    - 章国锋教授团队，[工程地址](http://www.zjucvg.net/eval-vislam/)，[Github-评估工具](https://github.com/zju3dv/eval-vislam)
30. Pablo Speciale, Johannes L. Schonberg, Sing Bing Kang. [**Privacy Preserving Image-Based Localization**](https://arxiv.org/pdf/1903.05572.pdf)[J] **2019**.
    - 利用**线云**进行基于图像的定位
    - **苏黎世**联邦理工、微软，[作者主页](http://people.inf.ethz.ch/sppablo/)，[工程地址](https://www.cvg.ethz.ch/research/secon/)
    - Speciale P, Pani Paudel D, Oswald M R, et al. **Consensus maximization with linear matrix inequality constraints**[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. **CVPR 2017**: 4941-4949. 最大化线性矩阵不等式约束 [[PDF](https://www.cvg.ethz.ch/research/conmax/paper/PSpeciale2017CVPR.pdf)] [[Code](https://www.cvg.ethz.ch/research/conmax/paper/PSpeciale2017CVPR_code_sample.tar.gz)] [[Video](https://www.youtube.com/watch?v=yV1wXknpG1U)] [[Project Page](https://www.cvg.ethz.ch/research/conmax)]

## 点线面-struct vio:

#### 1. PL-SVO（点线 SVO）

- **论文**：Gomez-Ojeda R, Briales J, Gonzalez-Jimenez J. [**PL-SVO: Semi-direct Monocular Visual Odometry by combining points and line segments**](http://mapir.isa.uma.es/rgomez/publications/iros16plsvo.pdf)[C]//Intelligent Robots and Systems (IROS), 2016 IEEE/RSJ International Conference on. IEEE, **2016**: 4211-4216.
- **代码**：https://github.com/rubengooj/pl-svo

#### 2. stvo-pl（双目点线 VO）

- **论文**：Gomez-Ojeda R, Gonzalez-Jimenez J. [**Robust stereo visual odometry through a probabilistic combination of points and line segments**](https://riuma.uma.es/xmlui/bitstream/handle/10630/11515/icra16rgo.pdf?sequence=1&isAllowed=y)[C]//2016 IEEE International Conference on Robotics and Automation (**ICRA**). IEEE, **2016**: 2521-2526.
- **代码**：https://github.com/rubengooj/stvo-pl

#### 3. PL-SLAM（点线 SLAM）

- **论文**：Gomez-Ojeda R, Zuñiga-Noël D, Moreno F A, et al. [**PL-SLAM: a Stereo SLAM System through the Combination of Points and Line Segments**](https://arxiv.org/pdf/1705.09479.pdf)[J]. arXiv preprint arXiv:1705.09479, **2017**.
- **代码**：https://github.com/rubengooj/pl-slam
- Gomez-Ojeda R, Moreno F A, Zuñiga-Noël D, et al. [**PL-SLAM: a stereo SLAM system through the combination of points and line segments**](https://arxiv.org/pdf/1705.09479)[J]. IEEE Transactions on Robotics, **2019**, 35(3): 734-746.

#### 4. PL-VIO

- **论文**：He Y, Zhao J, Guo Y, et al. [**PL-VIO: Tightly-coupled monocular visual–inertial odometry using point and line features**](https://www.mdpi.com/1424-8220/18/4/1159)[J]. Sensors, **2018**, 18(4): 1159.
- **代码**：https://github.com/HeYijia/PL-VIO
- **VINS + 线段**：https://github.com/Jichao-Peng/VINS-Mono-Optimization

#### 5. lld-slam（用于 SLAM 的可学习型线段描述符）

- **论文**：Vakhitov A, Lempitsky V. [**Learnable line segment descriptor for visual SLAM**](https://ieeexplore.ieee.org/iel7/6287639/6514899/08651490.pdf)[J]. IEEE Access, **2019**, 7: 39923-39934.
- **代码**：https://github.com/alexandervakhitov/lld-slam ；[**Video**](https://www.youtube.com/watch?v=ntFFiwXIhoA)

> 点线结合的工作还有很多，国内的比如
>
> - 上交邹丹平老师的 Zou D, Wu Y, Pei L, et al. [**StructVIO: visual-inertial odometry with structural regularity of man-made environments**](https://arxiv.org/pdf/1810.06796)[J]. IEEE Transactions on Robotics, **2019**, 35(4): 999-1013.
> - 浙大的 Zuo X, Xie X, Liu Y, et al. [**Robust visual SLAM with point and line features**](https://arxiv.org/pdf/1711.08654)[C]//2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2017: 1775-1782.

#### 6. PlaneSLAM

- **论文**：Wietrzykowski J. [**On the representation of planes for efficient graph-based slam with high-level features**](https://yadda.icm.edu.pl/baztech/element/bwmeta1.element.baztech-7ac7a8f3-9caa-4a34-8a27-8f6c5f43408b)[J]. Journal of Automation Mobile Robotics and Intelligent Systems, **2016**, 10.
- **代码**：https://github.com/LRMPUT/PlaneSLAM
- 作者另外一项开源代码，没有找到对应的论文：https://github.com/LRMPUT/PUTSLAM

#### 7. Eigen-Factors（特征因子平面对齐）

- **论文**：Ferrer G. [**Eigen-Factors: Plane Estimation for Multi-Frame and Time-Continuous Point Cloud Alignment**](http://sites.skoltech.ru/app/data/uploads/sites/50/2019/07/ferrer2019planes.pdf)[C]//2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, **2019**: 1278-1284.
- **代码**：https://gitlab.com/gferrer/eigen-factors-iros2019 ；[演示视频](https://www.youtube.com/watch?v=_1u_c43DFUE&feature=youtu.be)

#### 8. PlaneLoc

- **论文**：Wietrzykowski J, Skrzypczyński P. [**PlaneLoc: Probabilistic global localization in 3-D using local planar features**](https://github.com/ssssjiang/Visual_SLAM_Related_Research/blob/master)[J]. Robotics and Autonomous Systems, **2019**, 113: 160-173.
- **代码**：https://github.com/LRMPUT/PlaneLoc

#### 9. Pop-up SLAM

- **论文**：Yang S, Song Y, Kaess M, et al. [**Pop-up slam: Semantic monocular plane slam for low-texture environments**](https://arxiv.org/pdf/1703.07334.pdf)[C]//2016 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, **2016**: 1222-1229.
- **代码**：https://github.com/shichaoy/pop_up_slam

#### 10. Object SLAM

- **论文**：Mu B, Liu S Y, Paull L, et al. [**Slam with objects using a nonparametric pose graph**](https://arxiv.org/pdf/1704.05959.pdf)[C]//2016 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, **2016**: 4602-4609.
- **代码**：https://github.com/BeipengMu/objectSLAM ；[Video](https://www.youtube.com/watch?v=YANUWdVLJD4&feature=youtu.be)

#### 11. voxblox-plusplus（物体级体素建图）

- **论文**：Grinvald M, Furrer F, Novkovic T, et al. [**Volumetric instance-aware semantic mapping and 3D object discovery**](https://arxiv.org/pdf/1903.00268.pdf)[J]. IEEE Robotics and Automation Letters, **2019**, 4(3): 3037-3044.
- **代码**：https://github.com/ethz-asl/voxblox-plusplus

#### 12. Cube SLAM

- **论文**：Yang S, Scherer S. [**Cubeslam: Monocular 3-d object slam**](https://arxiv.org/pdf/1806.00557)[J]. IEEE Transactions on Robotics, **2019**, 35(4): 925-938.
- **代码**：https://github.com/shichaoy/cube_slam
- 对，这就是带我入坑的一项工作，2018 年 11 月份看到这篇论文（当时是预印版）之后开始学习物体级 SLAM，个人对 Cube SLAM 的一些注释和总结：[链接](https://www.wuxiaolang.cn/slam/)。
- 也有很多有意思的但没开源的物体级 SLAM
  - Ok K, Liu K, Frey K, et al. [**Robust Object-based SLAM for High-speed Autonomous Navigation**](http://groups.csail.mit.edu/rrg/papers/OkLiu19icra.pdf)[C]//2019 International Conference on Robotics and Automation (ICRA). IEEE, **2019**: 669-675.
  - Li J, Meger D, Dudek G. [**Semantic Mapping for View-Invariant Relocalization**](https://www.cim.mcgill.ca/~mrl/pubs/jimmy/li2019icra.pdf)[C]//2019 International Conference on Robotics and Automation (ICRA). IEEE, **2019**: 7108-7115.
  - Nicholson L, Milford M, Sünderhauf N. [**Quadricslam: Dual quadrics from object detections as landmarks in object-oriented slam**](https://arxiv.org/pdf/1804.04011)[J]. IEEE Robotics and Automation Letters, **2018**, 4(1): 1-8.

#### 13. VPS-SLAM（平面语义 SLAM）

- **论文**：Bavle H, De La Puente P, How J, et al. [**VPS-SLAM: Visual Planar Semantic SLAM for Aerial Robotic Systems**](https://ieeexplore.ieee.org/iel7/6287639/8948470/09045978.pdf)[J]. IEEE Access, **2020**.
- **代码**：https://bitbucket.org/hridaybavle/semantic_slam/src/master/

#### 14. Structure-SLAM （低纹理环境下点线 SLAM）

- **论文**：Li Y, Brasch N, Wang Y, et al. [**Structure-SLAM: Low-Drift Monocular SLAM in Indoor Environments**](https://ieeexplore.ieee.org/abstract/document/9165014)[J]. IEEE Robotics and Automation Letters, **2020**, 5(4): 6583-6590.
- **代码**：https://github.com/yanyan-li/Structure-SLAM-PointLine



