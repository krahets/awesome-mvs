# Awesome MVS  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of tutorials, papers, software related to multi-view stereo.

Please visit [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) for a more generic computer vision list.

## Contents

- [Tutorial](#tutorial)
- [Survey](#survey)
- [Paper](#paper)
- [Multi-View Stereo](#multi-view-stereo)
    - [Depth Map & Point Cloud Methods](#depth-map--point-cloud-methods)
    - [Volumetric & Implicit Methods](#volumetric--implicit-methods)
- [Mesh Texturing](#mesh-texturing)
- [Viewpoints and Trajectory Optimization](#viewpoints-and-trajectory-optimization)
- [Benchmark](#benchmark)
- [Open Source](#open-source)
- [Commercial Software](#commercial-software)
- [License](#license)
- [Contribution](#contribution)

## Tutorial

- [Multi-View Stereo: A Tutorial](https://drive.google.com/open?id=1rPHk0dyAfjh-1wu-wQShFm-qtiUScPxz). Y. Furukawa, C. Hernández. Foundations and Trends® in Computer Graphics and Vision, 2015.

- [Multiple view geometry in computer vision](https://cseweb.ucsd.edu/classes/sp13/cse252B-a/HZ2eCh2.pdf). Hartley, Richard, and Andrew Zisserman. Cambridge university press, 2003.

## Survey

- [A comparison and evaluation of multi-view stereo reconstruction algorithms](http://vision.middlebury.edu/mview/seitz_mview_cvpr06.pdf). Seitz, Steven M., et al. CVPR 2006.

- [On benchmarking camera calibration and multi-view stereo for high resolution imagery](https://infoscience.epfl.ch/record/126393/files/strecha_cvpr_2008.pdf). Strecha, Christoph, et al. CVPR 2008.

- [State of the art in high density image matching](https://www.researchgate.net/publication/263465866_State_of_the_art_in_high_density_image_matching﻿). F. Remondino, M.G. Spera, E. Nocerino, F. Menna, F. Nex . The Photogrammetric Record 2014.

- [Deep Learning for Multi-View Stereo via Plane Sweep: A Survey](https://arxiv.org/pdf/2106.15328.pdf). Zhu, Qingtian, et al. arXiv 2021.

- [Multi-view stereo in the Deep Learning Era: A comprehensive review](https://www.sciencedirect.com/science/article/pii/S0141938221001062?casa_token=i7-AyFnsLKgAAAAA:aMaW0BsbyrBe2ZVySisLTn6A-9aNc6Nk6I6k4JTKFdjR8wQznyi4VrCquaf5kN1tRwtiifh14Q). Wang, Xiang, et al. Displays 2021.

## Paper

### Multi-View Stereo

#### Depth Map & Point Cloud Methods

> Stereo Matching

- [Stereo Processing by Semiglobal Matching and Mutual Information](https://elib.dlr.de/55367/1/Stereo_Processing-Hirschm%C3%BCller.pdf). Hirschmuller, Heiko. PAMI 2007.

- [Patchmatch stereo-stereo matching with slanted support windows](http://imagine.enpc.fr/~de-la-gm/cours/UPEM/projects/PatchMatch%20Stereo%20-%20Stereo%20Matching%20with%20Slanted%20Support%20Windows.pdf). Bleyer, M., Rhemann, C., & Rother, C. BMVC 2011.

> Geometry-Based

- [Multi-view stereo revisited](https://grail.cs.washington.edu/wp-content/uploads/2015/08/Goesele-2006-MSR.pdf). Goesele, Michael, Brian Curless, and Steven M. Seitz. CVPR 2006.

- [Multi-view stereo for community photo collections](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.146.2530&rep=rep1&type=pdf). Goesele, Michael, et al. ICCV 2007.

- [Using multiple hypotheses to improve depth-maps for multi-view stereo](https://link.springer.com/content/pdf/10.1007/978-3-540-88682-2_58.pdf). Campbell, Neill DF, et al. ECCV 2008.

- [Towards high-resolution large-scale multi-view stereo](http://www.normalesup.org/~labatut/papers/cvpr2009-towards-high-resolution.pdf). Hiep, Vu Hoang, et al. CVPR 2009.

- [Towards internet-scale multi-view stereo](https://www.microsoft.com/en-us/research/wp-content/uploads/2010/06/Furukawa-CVPR10.pdf). Furukawa, Yasutaka, et al. CVPR 2010.

- [Accurate, Dense, and Robust Multiview Stereopsis](http://www.cs.wustl.edu/~furukawa/papers/pami08a.pdf). Y. Furukawa, J. Ponce. CVPR 2007. PAMI 2010.

- [Multi-view reconstruction preserving weakly-supported surfaces](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.225.6187&rep=rep1&type=pdf). Jancosek, Michal, and Tomás Pajdla. CVPR 2011.

- [DAISY: An efficient dense descriptor applied to wide-baseline stereo](https://infoscience.epfl.ch/record/138785/files/tola_daisy_pami_1.pdf). Tola, Engin, Vincent Lepetit, and Pascal Fua. PAMI 2009.

- [Efficient large-scale multi-view stereo for ultra high-resolution image sets](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.225.6187&rep=rep1&type=pdf). Tola, Engin, Christoph Strecha, and Pascal Fua. MVA 2012.

- [Accurate multiple view 3d reconstruction using patch-based stereo for large-scale scenes](https://islab.ulsan.ac.kr/files/announcement/433/Accurate%20Multiple%20View%203D%20Reconstruction%20Using%20Pathch-Based%20Stereo%20for%20Large-Scale%20Scenes.pdf). Shen, Shuhan. TIP 2013.

- [MVE-A Multi-View Reconstruction Environment](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.673.3254&rep=rep1&type=pdf). Fuhrmann, Simon, Fabian Langguth, and Michael Goesele. GCH 2014.

- [Patchmatch based joint view selection and depthmap estimation](https://openaccess.thecvf.com/content_cvpr_2014/papers/Zheng_PatchMatch_Based_Joint_2014_CVPR_paper.pdf). Zheng, Enliang, et al. CVPR 2014.

- [Massively parallel multiview stereopsis by surface normal diffusion](https://openaccess.thecvf.com/content_iccv_2015/papers/Galliani_Massively_Parallel_Multiview_ICCV_2015_paper.pdf). Galliani, Silvano, Katrin Lasinger, and Konrad Schindler. ICCV 2015.

- [Pixelwise View Selection for Unstructured Multi-View Stereo](https://demuc.de/papers/schoenberger2016mvs.pdf). J. L. Schönberger, E. Zheng, M. Pollefeys, J.-M. Frahm. ECCV 2016.

- [Multi-scale geometric consistency guided multi-view stereo](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_Multi-Scale_Geometric_Consistency_Guided_Multi-View_Stereo_CVPR_2019_paper.pdf). Xu, Qingshan, and Wenbing Tao. CVPR 2019.

- [TAPA-MVS: Textureless-aware patchmatch multi-view stereo](https://openaccess.thecvf.com/content_ICCV_2019/papers/Romanoni_TAPA-MVS_Textureless-Aware_PAtchMatch_Multi-View_Stereo_ICCV_2019_paper.pdf). Romanoni, Andrea, and Matteo Matteucci. ICCV 2019.

- [Pyramid multi‐view stereo with local consistency](https://www.researchgate.net/profile/Jie-Liao-5/publication/337249866_Pyramid_Multi-View_Stereo_with_Local_Consistency/links/5dce54a2299bf1b74b426805/Pyramid-Multi-View-Stereo-with-Local-Consistency.pdf). Liao, Jie, et al. Computer Graphics Forum 2019.

> Surpervised Learning

- [MVSNet: Depth Inference for Unstructured Multi-view Stereo](https://arxiv.org/abs/1804.02505), Y. Yao, Z. Luo, S. Li, T. Fang, L. Quan. ECCV 2018.

- [DeepMVS: Learning Multi-View Stereopsis](https://github.com/phuang17/DeepMVS), Huang, P. and Matzen, K. and Kopf, J. and Ahuja, N. and Huang, J. CVPR 2018.

- [MVDepthNet: Real-time multiview depth estimation neural network](https://arxiv.org/pdf/1807.08563.pdf). Wang, Kaixuan, and Shaojie Shen. 3DV 2018.

- [Recurrent MVSNet for high-resolution multi-view stereo depth inference](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yao_Recurrent_MVSNet_for_High-Resolution_Multi-View_Stereo_Depth_Inference_CVPR_2019_paper.pdf). Yao, Yao, et al. CVPR 2019.

- [DPSNet: End-to-end deep plane sweep stereo](https://arxiv.org/pdf/1905.00538.pdf). Im, Sunghoon, et al. arXiv 2019.

- [P-MVSNet: Learning patch-wise matching confidence aggregation for multi-view stereo](https://openaccess.thecvf.com/content_ICCV_2019/papers/Luo_P-MVSNet_Learning_Patch-Wise_Matching_Confidence_Aggregation_for_Multi-View_Stereo_ICCV_2019_paper.pdf). Luo, Keyang, et al. ICCV 2019.

- [Point-based Multi-view Stereo Network](http://hansf.me/projects/PMVSNet/), Rui Chen, Songfang Han, Jing Xu, Hao Su. ICCV 2019.

- [Pyramid multi-view stereo net with self-adaptive view aggregation](https://arxiv.org/pdf/1912.03001.pdf?ref=https://githubhelp.com). Yi, Hongwei, et al. ECCV 2020.

- [Cascade cost volume for high-resolution multi-view stereo and stereo matching](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Cascade_Cost_Volume_for_High-Resolution_Multi-View_Stereo_and_Stereo_Matching_CVPR_2020_paper.pdf). Gu, Xiaodong, et al. CVPR 2020.

- [Cost volume pyramid based depth inference for multi-view stereo](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Cost_Volume_Pyramid_Based_Depth_Inference_for_Multi-View_Stereo_CVPR_2020_paper.pdf). Yang, Jiayu, et al. CVPR 2020.

- [Fast-MVSNet: Sparse-to-dense multi-view stereo with learned propagation and gauss-newton refinement](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_Fast-MVSNet_Sparse-to-Dense_Multi-View_Stereo_With_Learned_Propagation_and_Gauss-Newton_Refinement_CVPR_2020_paper.pdf). Yu, Zehao, and Shenghua Gao. CVPR 2020.

- [Attention-aware multi-view stereo](https://openaccess.thecvf.com/content_CVPR_2020/papers/Luo_Attention-Aware_Multi-View_Stereo_CVPR_2020_paper.pdf). Luo, Keyang, et al. CVPR 2020.

- [Visibility-aware multi-view stereo network](https://arxiv.org/pdf/2008.07928.pdf). Zhang, Jingyang, et al. arXiv 2020.

- [Visibility-aware point-based multi-view stereo network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9076298). Chen, Rui, et al. PAMI 2020.

- [PVSNet: Pixelwise visibility-aware multi-view stereo network](https://arxiv.org/pdf/2007.07714.pdf). Xu, Qingshan, and Wenbing Tao. arXiv 2020.

- [BP-MVSNet: Belief-propagation-layers for multi-view-stereo](https://arxiv.org/pdf/2010.12436.pdf). Sormann, Christian, et al. 3DV 2020.

- [DeepC-MVS: Deep confidence prediction for multi-view stereo reconstruction](https://arxiv.org/pdf/1912.00439). Kuhn, Andreas, et al. 3DV 2020.

- [Mesh-guided multi-view stereo with pyramid architecture](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Mesh-Guided_Multi-View_Stereo_With_Pyramid_Architecture_CVPR_2020_paper.pdf). Wang, Yuesong, et al. CVPR 2020.

- [PatchmatchNet: Learned multi-view patchmatch stereo](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_PatchmatchNet_Learned_Multi-View_Patchmatch_Stereo_CVPR_2021_paper.pdf). Wang, Fangjinhua, et al. CVPR 2021.

- [AA-RMVSNet: Adaptive aggregation recurrent multi-view stereo network](https://openaccess.thecvf.com/content/ICCV2021/papers/Wei_AA-RMVSNet_Adaptive_Aggregation_Recurrent_Multi-View_Stereo_Network_ICCV_2021_paper.pdf). Wei, Zizhuang, et al. ICCV 2021.

- [PatchMatch-RL: Deep MVS with Pixelwise Depth, Normal, and Visibility](https://openaccess.thecvf.com/content/ICCV2021/papers/Lee_PatchMatch-RL_Deep_MVS_With_Pixelwise_Depth_Normal_and_Visibility_ICCV_2021_paper.pdf). Lee, Jae Yong, et al. ICCV 2021.

- [EPP-MVSNet: Epipolar-Assembling Based Depth Prediction for Multi-View Stereo](https://openaccess.thecvf.com/content/ICCV2021/papers/Ma_EPP-MVSNet_Epipolar-Assembling_Based_Depth_Prediction_for_Multi-View_Stereo_ICCV_2021_paper.pdf). Ma, Xinjun, et al. ICCV 2021.

- [Deep multi-view stereo gone wild](https://arxiv.org/pdf/2104.15119.pdf). Darmon, François, et al. 3DV 2021.

- [Generalized Binary Search Network for Highly-Efficient Multi-View Stereo](https://www.semanticscholar.org/paper/c88fc58d7e0f58008738d8844f6452faa4a5bbca). Zhenxing Mi, Di Chang, Dan Xu. arXiv 2021.

> Unsurpervised Learning

- [Learning unsupervised multi-view stereopsis via robust photometric consistency](https://arxiv.org/pdf/1905.02706.pdf). Khot, Tejas, et al. arXiv 2019.

- [MVS2: Deep unsupervised multi-view stereo with multi-view symmetry](https://arxiv.org/pdf/1908.11526.pdf). Dai, Yuchao, et al. 3DV 2019.

- [Mˆ3VSNet: Unsupervised multi-metric multi-view stereo network](https://arxiv.org/pdf/2004.09722.pdf). Huang, Baichuan, et al. ICIP 2021.

- [Self-supervised multi-view stereo via effective co-segmentation and data-augmentation](https://www.aaai.org/AAAI21Papers/AAAI-2549.XuH.pdf). Xu, Hongbin, et al. AAAI 2021.

- [Self-supervised Learning of Depth Inference for Multi-view Stereo](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Self-Supervised_Learning_of_Depth_Inference_for_Multi-View_Stereo_CVPR_2021_paper.pdf). Yang, Jiayu, Jose M. Alvarez, and Miaomiao Liu. CVPR 2021.

- [Digging into Uncertainty in Self-supervised Multi-view Stereo](https://openaccess.thecvf.com/content/ICCV2021/papers/Xu_Digging_Into_Uncertainty_in_Self-Supervised_Multi-View_Stereo_ICCV_2021_paper.pdf). Xu, Hongbin, et al. ICCV 2021.

- [NerfingMVS: Guided optimization of neural radiance fields for indoor multi-view stereo](https://openaccess.thecvf.com/content/ICCV2021/papers/Wei_NerfingMVS_Guided_Optimization_of_Neural_Radiance_Fields_for_Indoor_Multi-View_ICCV_2021_paper.pdf). Wei, Yi, et al. ICCV 2021.

#### Volumetric & Implicit Methods

> Geometry-Based

- [A volumetric method for building complex models from range images](https://dl.acm.org/doi/pdf/10.1145/237170.237269?casa_token=VkAZIffR2GUAAAAA:uWqJ8-28go2eXT0yNn03w17uggY0FtN-jix-Ln1uR5oWm5e6gM6L_zqJtcVsIUH0YOoM1k9FmmI). Curless, Brian, and Marc Levoy. PACMCGIT 1996.

- [Reliable surface reconstruction from multiple range images](https://link.springer.com/content/pdf/10.1007/BFb0015528.pdf). Hilton, Adrian, et al. ECCV 1996.

- [Consensus surfaces for modeling 3D objects from multiple range images](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.43.9546&rep=rep1&type=pdf). Wheeler, Mark D., Yoichi Sato, and Katsushi Ikeuchi. ICCV 1998.

- [A Theory of Shape by Space Carving](https://www.cs.toronto.edu/~kyros/pubs/00.ijcv.carve.pdf). Kiriakos N. Kutulakos, S. Seitz. IJCV 2000.

- [Robust and adaptive integration of multiple range images with photometric attributes](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.2050&rep=rep1&type=pdf). Sagawa, Ryusuke, Ko Nishino, and Katsushi Ikeuchi. CVPR 2001.

- [Object shape modelling from multiple range images by matching signed distance fields](https://ieeexplore.ieee.org/abstract/document/1024099). T. Masuda. Symposium on 3D Data Processing Visualization and Transmission, 2002.

- [The marching intersections algorithm for merging range images](https://d1wqtxts1xzle7.cloudfront.net/53312350/mi_for_fusion.pdf?1496039465=&response-content-disposition=inline%3B+filename%3DThe_Marching_Intersections_Algorithm_for.pdf&Expires=1644514270&Signature=APoQxsfNahoJH9H2uUdzxaLqlYGqt1a5aK0mUj5rRECOEsc-3d807dmUtE224HJqKSoO~URpm-K4OwKvnrvBxtSX1ApMGfKrzECFI4OYfKVeJbGf0qGa7DbXLIkzuq7yQKJCfBFzY~8Kmd~IXzwk0eKZgSGiS9QKRbk-bFpKlGJpG7ikY2iqgShA4X5HOK4gPN7Yzauay9dbyoaAcvt-jvvs-6X6IztwqEnvSLIczlHZ65fPn0SF39fO2IMzYvhLdEKRfd9cZ1CqobTWQ1wRW8iHYluQQ14J-hOmps82iOGHeE-LGiQjU~NuiPWe1MQ2gUk7DHj~DWGtsFUdA0ly5Q__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA). C. Rocchini, P. Cignoni, F. Ganovelli, C. Montani, P. Pingi, R. Scopigno. Visual Comput 2004.

- [A volumetric fusion technique for surface reconstruction from silhouettes and range data](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.329.8153&rep=rep1&type=pdf). Comput. Y. Yemez, C.J. Wetherilt. Vision Image Understand 2007.

- [KinectFusion: Real-time dense surface mapping and tracking](https://www.semanticscholar.org/paper/e2975deb809f35bd47ac3de34e348675a0cfb3f6). Richard A. Newcombe, S. Izadi, Otmar Hilliges, D. Molyneaux, David Kim, A. Davison, P. Kohli, J. Shotton, Steve Hodges, A. Fitzgibbon. ISMAR 2011.

- [Real-time 3D reconstruction at scale using voxel hashing](http://graphics.stanford.edu/~niessner/papers/2013/4hashing/niessner2013hashing.pdf). M. Nießner, M. Zollhöfer, S. Izadi, M. Stamminger. ACM Trans. Graph 2013.

- [BundleFusion: real-time globally consistent 3D reconstruction using on-the-fly surface re-integration](https://arxiv.org/pdf/1604.01093.pdf). Angela Dai, M. Nießner, M. Zollhöfer, S. Izadi, C. Theobalt. TOGS 2016.

> Learning-Based

- [Learning a multi-view stereo machine](https://proceedings.neurips.cc/paper/2017/file/9c838d2e45b2ad1094d42f4ef36764f6-Paper.pdf). Kar, Abhishek, Christian Häne, and Jitendra Malik. NeuralIPS 2017.

- [SurfaceNet: An end-to-end 3d neural network for multiview stereopsis](https://openaccess.thecvf.com/content_ICCV_2017/papers/Ji_SurfaceNet_An_End-To-End_ICCV_2017_paper.pdf). Ji, Mengqi, et al. ICCV 2017.

- [RayNet: Learning Volumetric 3D Reconstruction with Ray Potentials](https://avg.is.tuebingen.mpg.de/publications/paschalidou2018cvpr), D. Paschalidou and A. O. Ulusoy and C. Schmitt and L. Gool and A. Geiger. CVPR 2018.

- [Atlas: End-to-end 3d scene reconstruction from posed images](https://arxiv.org/pdf/2003.10432.pdf?ref=https://githubhelp.com). Murez, Zak, et al. ECCV 2020.

- [RoutedFusion: Learning real-time depth map fusion](https://openaccess.thecvf.com/content_CVPR_2020/papers/Weder_RoutedFusion_Learning_Real-Time_Depth_Map_Fusion_CVPR_2020_paper.pdf). Weder, Silvan, et al. CVPR 2020.

- [SurfaceNet+: An end-to-end 3D neural network for very sparse multi-view stereopsis](https://arxiv.org/pdf/2005.12690.pdf?ref=https://githubhelp.com). Ji, Mengqi, et al. PAMI 2020.

- [Differentiable Volumetric Rendering: Learning implicit 3d representations without 3d supervision](https://openaccess.thecvf.com/content_CVPR_2020/papers/Niemeyer_Differentiable_Volumetric_Rendering_Learning_Implicit_3D_Representations_Without_3D_Supervision_CVPR_2020_paper.pdf). Niemeyer, Michael, et al. CVPR 2020.

- [Multiview neural surface reconstruction by disentangling geometry and appearance](https://proceedings.neurips.cc/paper/2020/file/1a77befc3b608d6ed363567685f70e1e-Paper.pdf). Yariv, Lior, et al. NeuralIPS 2020.

- [NeuralRecon: Real-time coherent 3D reconstruction from monocular video](http://openaccess.thecvf.com/content/CVPR2021/papers/Sun_NeuralRecon_Real-Time_Coherent_3D_Reconstruction_From_Monocular_Video_CVPR_2021_paper.pdf). Sun, Jiaming, et al. CVPR 2021.

- [NeuralFusion: Online depth fusion in latent space](https://openaccess.thecvf.com/content/CVPR2021/papers/Weder_NeuralFusion_Online_Depth_Fusion_in_Latent_Space_CVPR_2021_paper.pdf). Weder, Silvan, et al. CVPR 2021.

- [UNISURF: Unifying neural implicit surfaces and radiance fields for multi-view reconstruction](https://openaccess.thecvf.com/content/ICCV2021/papers/Oechsle_UNISURF_Unifying_Neural_Implicit_Surfaces_and_Radiance_Fields_for_Multi-View_ICCV_2021_paper.pdf). Oechsle, Michael, Songyou Peng, and Andreas Geiger. ICCV 2021.

- [NeuS: Learning neural implicit surfaces by volume rendering for multi-view reconstruction](https://arxiv.org/pdf/2106.10689.pdf). Wang, Peng, et al. arXiv 2021.

- [Volume rendering of neural implicit surfaces](https://proceedings.neurips.cc/paper/2021/file/25e2a30f44898b9f3e978b1786dcd85c-Paper.pdf). Yariv, Lior, et al. NeuralIPS 2021.

### Mesh Texturing

- [Seamless image-based texture atlases using multi-band blending](http://imagine.enpc.fr/publications/papers/ICPR08a.pdf). C. Allène, J-P. Pons and R. Keriven. ICPR 2008.

- [Let There Be Color! - Large-Scale Texturing of 3D Reconstructions](http://www.gcc.tu-darmstadt.de/home/proj/texrecon/). M. Waechter, N. Moehrle, M. Goesele. ECCV 2014.

- [Texture Mapping for 3D Reconstruction with RGB-D Sensor](https://openaccess.thecvf.com/content_cvpr_2018/papers/Fu_Texture_Mapping_for_CVPR_2018_paper.pdf). Yanping Fu, Qingan Yan, Long Yang, Jie Liao, Chunxia Xiao. CVPR 2018.

### Viewpoints and Trajectory Optimization

- [Next Best View Planning for Active Model Improvement](http://www.bmva.org/bmvc/2009/Papers/Paper436/Paper436.pdf). Dunn, Enrique, and Jan-Michael Frahm. BMVC 2009.

- [Submodular Trajectory Optimization for Aerial 3D Scanning](http://graphics.stanford.edu/papers/aerial_scanning/). M. Roberts, A. Truong, D. Dey, S. Sinha, A. Kapoor, N. Joshi, P. Hanrahan. 2017.

- [Aerial path planning for urban scene reconstruction: A continuous optimization method and benchmark](https://repository.kaust.edu.sa/bitstream/handle/10754/628907/Smith2018UAVPathPlanning.pdf?sequence=1&isAllowed=y). Smith, Neil, et al. 2018.

- [Plan3D: Viewpoint and trajectory optimization for aerial multi-view stereo reconstruction](https://dl.acm.org/doi/pdf/10.1145/3233794?casa_token=UbS5wvWLymcAAAAA:oNXMUe6rYZkvV3prNJJyQ0yKvnicgswp2vWweqOjL6c5ZdkaFRGjpx-dyN-PuH-dqL7fclGj6iQ). Hepp, Benjamin, Matthias Nießner, and Otmar Hilliges. ACM TOG 2018.

- [Automatic and semantically-aware 3D UAV flight planning for image-based 3D reconstruction](https://www.mdpi.com/2072-4292/11/13/1550/htm). Koch, Tobias, Marco Körner, and Friedrich Fraundorfer. Remote Sensing 2019.

- [Offsite aerial path planning for efficient urban scene reconstruction](https://dl.acm.org/doi/pdf/10.1145/3414685.3417791). Zhou, Xiaohui, et al. ACM TOG 2020.

## Benchmark

- [**DTU**. Large scale multi-view stereopsis evaluation](https://roboimagedata2.compute.dtu.dk/data/text/multiViewCVPR2014.pdf). Jensen, Rasmus, et al. CVPR 2014. [Large-scale data for multiple-view stereopsis](https://publications.aston.ac.uk/id/eprint/28180/1/Large_scale_data_for_multiple_view_stereopsis.pdf). Aanæs, Henrik, et al. ICCV2016.

- [**Tanks and Temples**: Benchmarking large-scale scene reconstruction](https://dl.acm.org/doi/pdf/10.1145/3072959.3073599?casa_token=-U2AbKrHwnUAAAAA:wDnJtCC9xWfy6G7cRfiFAzxiEbePrhDuCQRoxNnxCoO1tWgonmm6Xh3158u5-ALq9EtIskTcHTdiRQ). Knapitsch, Arno, et al. ACM TOG 2017.

- [**ETH3D**. A multi-view stereo benchmark with high-resolution images and multi-camera videos](https://openaccess.thecvf.com/content_cvpr_2017/papers/Schops_A_Multi-View_Stereo_CVPR_2017_paper.pdf). Schops, Thomas, et al. CVPR 2017.

- [**ScanNet**: Richly-Annotated 3D Reconstructions of Indoor Scenes](https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf). Angela Dai, Angel X. Chang, M. Savva, Maciej Halber, T. Funkhouser, M. Nießner. CVPR 2017.

- [**BlendedMVS**: A large-scale dataset for generalized multi-view stereo networks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yao_BlendedMVS_A_Large-Scale_Dataset_for_Generalized_Multi-View_Stereo_Networks_CVPR_2020_paper.pdf). Yao, Yao, et al. CVPR 2020.

- [**GigaMVS**: A Benchmark for Ultra-large-scale Gigapixel-level 3D Reconstruction](https://www.computer.org/csdl/journal/tp/5555/01/09547729/1x9Tv1542aY). Zhang, Jianing, et al. PAMI 2021.

- [Multi-sensor large-scale dataset for multi-view 3D reconstruction](https://arxiv.org/pdf/2203.06111.pdf). Oleg Voynov, etal. CVPR 2022.

## Open Source

| Project                                                      | Language            | License      |
| ------------------------------------------------------------ | ------------------- | ------------ |
| [CMVS-PMVS](https://github.com/pmoulon/CMVS-PMVS)            | C++, CUDA           | GPL          |
| [Colmap](https://github.com/colmap/colmap)                   | C++, CUDA           | BSD 3-Clause |
| [Gipuma + Fusibile](https://github.com/kysucix)              | C++, CUDA           | GPL-3.0      |
| [MeshRoom(AliceVision)](https://github.com/alicevision/meshroom) | C++, Python         | MPL2         |
| [MVE](https://github.com/simonfuhrmann/mve)                  | C++                 | BSD 3-Clause |
| [OpenMVS](https://github.com/cdcseacave/openMVS/)            | C++, CUDA(Optional) | AGPL3        |
| [MVS-Texturing](https://github.com/nmoehrle/mvs-texturing)   | C++                 | BSD 3-Clause |

## Commercial Software

| Software                                                     | Company                                              |
| ------------------------------------------------------------ | ---------------------------------------------------- |
| [ContextCapture](https://www.bentley.com/en/products/brands/contextcapture) | [Bentley Systems](https://www.bentley.com/en)        |
| [DJI Terra](https://www.dji.com/cn/dji-terra)                | [DJI](https://www.dji.com/)                          |
| [MetaShape](https://www.agisoft.com/)                        | [Agisoft](https://www.agisoft.com/)                  |
| [Pix4Dmapper](https://www.pix4d.com/product/pix4dmapper-photogrammetry-software) | [Pix4D](https://www.pix4d.com/)                      |
| [RealityCapture](https://www.capturingreality.com/)          | [Epic Games](https://www.epicgames.com/store/en-US/) |

## License

MIT

## Contribution

Welcome to create a pull request. Please ensure your pull request adheres the formats.
