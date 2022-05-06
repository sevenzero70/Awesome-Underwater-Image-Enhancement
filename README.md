# Awesome-Underwater-Image-Enhancement
The information about underwater images enhancment(updating……)
<br>

🏠 [Commomly-used Physical Models](#Commomly-used Physical Models) <br>

🍱 [Datasets](#Datasets) <br>
🍜 [Survey](#Survey) <br>
🍢 [Methods](#Methods) <br>
🍹
🍧
🍰

<p id="Commomly-used Physical Models"></p>

# Commomly-used Physical Models
* atmospheric acattering model [[paper]]()
* simplified model [[paper]](https://ieeexplore.ieee.org/document/6104148)
* revised model [[paper]](https://ieeexplore.ieee.org/document/8578801)

<p id="Datasets"></p>

# Datasets
### 1 [Fish4Knowledge](http://groups.inf.ed.ac.uk/f4k/index.html) <br>
由欧洲联盟海洋生态系统研究第七框架项目资助，该项目提供了一个视频和鱼类分析数据集(约200Tb) <br>

### 2 [ULFID](https://github.com/kskin/data) <br>
水下光场图像数据集包含了几张在纯水和朦胧条件下的水下光场图像，以及在空气中拍摄的图像供参考 <br>

### 3 [MARIS](http://rimlab.ce.unipr.it/Maris.html) <br>
Marine Autonomous Robotics for InterventionS（海洋干预自主机器人）为了推进在海洋产业、搜救任务和各种各样的科学探索中，合作式AUVs的发展,该项目提供了几种水下立体视觉系统拍摄的水下图像和视频 <br>

### 4 [Haze-line Dataset](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html) <br>
收集了在不同地点拍摄的不同水属性的图像数据集，显示了场景中的颜色图表(约33GB)，并基于立体成像计算场景的三维结构 <br>

### 5 [UIEBD](https://li-chongyi.github.io/proj_benchmark.html) <br>
Underwater Image Enhancement Benchmark Dataset（水下图像增强基准数据集） <br>
  a. 包含950张真实水下图像，其中890张具有相应的参考图像，每个参考图像是从12个增强结果中选择的。其余60幅无法获得满意参考资料的水下图像作为具有挑战性的数据处理 <br>
  b. 包含一个大范围的图像分辨率和跨越不同的场景/主要对象类别 <br>

<p id="Survey"></p>

# Survey
* Saeed Anwar and Chongyi Li, “Diving deeper into underwater image enhancement: A survey,”Signal Processing-image Communication, 2020, doi: 10.1016/j.image.2020.115978.[[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0923596520301478)[[note]](https://www.yuque.com/u12128212/yrs2r6/gu6n1o)
* M. Han, Z. Lyu, T. Qiu, and M. Xu, “A Review on Intelligence Dehazing and Color Restoration for Underwater Images,” IEEE Trans. Syst. Man Cybern, Syst., vol. 50, no. 5, pp. 1820–1832, May 2020, doi: 10.1109/TSMC.2017.2788902. [[paper]](https://ieeexplore.ieee.org/document/8267119)

<p id="Methods"></p>

# Methods
## 1 Deep Learning
* ***`Unet`*** ----- [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Kim_Accurate_Image_Super-Resolution_CVPR_2016_paper.pdf)[code] <br>
  > J. Kim, J. K. Lee, and K. M. Lee, “Accurate image super-resolution using very deep convolutional networks,” in Proc. IEEE Conf. Comput. Vis. Pattern Recognit. (CVPR), Jun. 2016, pp. 1646–1654.

* ***`CycleGAN`*** ----- [[paper]](https://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.html)[code] <br>
  > J. Zhu, T. Park, P. Isola, A.A. Efros, Unpaired image-to-image translation using cycle-consistent adversarial networks, in: IEEE International Conference on Computer Vision (ICCV), 2017, pp. 2242–2251, doi:10.1109/ICCV.2017.244.

* ***`Haze Line`*** ----- [[paper]](https://www.eng.tau.ac.il/~berman/UnderwaterColorRestoration/UnderwaterHazeLines_BMVC2017.pdf)[code] <br>
  > D. Berman, T. Treibitz, S. Avidan Diving into haze-lines: color restoration of underwater images Proc. British Machine Vision Conference (BMVC), 1 (2017)

* ***`UcycleGAN`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8253820)[code] <br>
  > C. Li, J. Guo, and C. Guo, “Emerging from water: Underwater image color correction based on weakly supervised color transfer,” IEEE Signal Process. Lett., vol. 25, no. 3, pp. 323–327, Mar. 2018.

* ***`UGAN`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8460552)[code] <br>
  > C. Fabbri, M. J. Islam and J. Sattar, "Enhancing underwater imagery using generative adversarial networks", IEEE International Conference on Robotics and Automation (ICRA), 2018.

* ***`UWCNN`*** ----- [[paper]](https://www.sciencedirect.com/science/article/pii/S0031320319303401?casa_token=rzfvsEXr4hAAAAAA:Nkt4m1ZHy8ORrftU2CWfoyn7VPd1iM_Gz8Qc51ihdh1FEjveggOwmaeNnEbizBIgNHXPUzPZWv0)[code] <br>
  > Li C., Anwar S. Underwater scene prior inspired deep underwater image and video enhancement Pattern Recognit, 98 (2019), Article 107038

* ***`CG`*** ----- [[paper]](https://www.mdpi.com/2313-433X/5/10/79)[code] <br>
  > Tunai Porto Marques, Alexandra Branzan Albu, and Maia Hoeberechts. A contrast-guided approach for the enhancement of low-lighting underwater images. Journal of Imaging, 5(10):79, 2019. 1, 2, 3, 4, 5, 7, 8

* ***`Water-Net`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8917818)[code] <br>
  > C. Li, C. Guo, W. Ren, R. Cong, J. Hou, S. Kwong, et al., "An underwater image enhancement benchmark dataset and beyond", IEEE Transactions on Image Processing, 2019.

* ***`(SR)CNN`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8746235)[code] <br>
  > Y. Li, C. Ma, T. Zhang, J. Li, Z. Ge, Y. Li, and S. Serikawa, “Underwater Image High Definition Display Using the Multilayer Perceptron and Color Feature-Based SRCNN,” IEEE Access 7, 83721–83728 (2019).

* ***`MSRCR`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8727948)[code] <br>
  > W. Zhang, L. Dong, X. Pan, J. Zhou, L. Qin and W. Xu, "Single Image Defogging Based on Multi-Channel Convolutional MSRCR," in IEEE Access, vol. 7, pp. 72492-72504, 2019, doi: 10.1109/ACCESS.2019.2920403.

* ***`MDGAN`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8730425)[code] <br>
  > Y. Guo, H. Li, and P. Zhuang, “Underwater image enhancement using a multiscale dense generative adversarial network,” IEEE J. Ocean. Eng., vol. 45, no. 3, pp. 862–870, Jul. 2020.

* ***`FUnIE-GAN`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/9001231)[code] <br>
  > M. J. Islam, Y. Xia and J. Sattar, "Fast underwater image enhancement for improved visual perception", IEEE Robotics and Automation Letters, 2020.

* ***`Ucolor`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/9426457)[code] <br>
  > C. Li, S. Anwar, J. Hou, R. Cong, C. Guo and W. Ren, "Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding," in IEEE Transactions on Image Processing, vol. 30, pp. 4985-5000, 2021, doi: 10.1109/TIP.2021.3076367.

## 2 Tradition
* ***`SSR`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/557356)[code]
  > Jobson D.J., Rahman Z. Properties and performance of a center/surround retinex IEEE Trans Image Process, 6 (3) (1997), pp. P.451-462 <br>

* ***`MSR`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/597272)[code]
  > Jobson D.J., Rahman Z., Woodell G.A. A multiscale retinex for bridging the gap between color images and the human observation of scenes IEEE Trans Image Process, 6 (7) (2002), pp. 965-976 <br>

* ***`MR`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/560995)[code]
  > Rahman Z, Jobson DJ, Woodell GA. Multi-scale retinex for color image enhancement. In: Proceedings of 3rd IEEE international conference on image processing. 2002.

* ***`FB`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/6247661)[code]
  > Ancuti C, Ancuti CO, Haber T, Bekaert P. Enhancing underwater images and videos by fusion. In: IEEE conference on computer vision & pattern recognition. 2012, p. 81–8.

* ***`TB`*** ----- [[paper]](https://www.cv-foundation.org//openaccess/content_iccv_workshops_2013/W24/papers/Drews_Jr._Transmission_Estimation_in_2013_ICCV_paper.pdf)[code] 
  > Drews JP, Nascimento E, Moraes F, Botelho S, Campos M. Transmission estimation in underwater single images. In: IEEE international conference on computer vision workshops. 2013.

* ***`DCP`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/5567108)[code] <br>
  > K. He, J. Sun and X. Tang, "Single image haze removal using dark channel prior", IEEE transactions on pattern analysis and machine intelligence, 2011.

* ***`RBEA`*** ----- [[paper]](https://ieeexplore.ieee.org/document/7025927)[code] <br>
  > Fu X., Zhuang P., Huang Y., Liao Y., Zhang X., Ding X. A retinex-based enhancing approach for single underwater image 2014 IEEE international conference on image processing (ICIP) (2014), pp. 4572-4576

* ***`VIM`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/7782813)[code] <br>
  > Xiaojie Guo, Yu Li, and Haibin Ling. Lime: Low-light image enhancement via illumination map estimation. IEEE Transactions on Image Processing, 26(2):982–993, 2016. 1, 2, 7, 8

* ***`Histogram Prior`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/7574330)[code] <br>
  > C.-Y. Li, J.-C. Guo, R.-M. Cong, Y.-W. Pang, B. Wang Underwater image enhancement by dehazing with minimum information loss and histogram distribution prior IEEE Trans. Image Process., 25 (12) (2016), pp. 5664-5677

* ***`UDCP`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/7426236)[code] <br>
  > Drews P.L.J., Nascimento E.R., Botelho S.S.C., Montenegro Campos M.F. Underwater depth estimation and image restoration based on single images IEEE Comput Graph Appl, 36 (2) (2016), pp. 24-35

* ***`FA`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8050994)[code] <br>
  > Y. Wang, H. Liu, and L.-P. Chau, “Single underwater image restoration using attenuation-curve prior,” in Proc. IEEE Int. Symp. Circuits Syst. May 2017.

* ***`IBLA`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/7840002)[code] <br>
  > Y.-T. Peng and P. C. Cosman, "Underwater image restoration based on image blurriness and light absorption", IEEE transactions on image processing, 2017.

* ***`Hybrid-UIC`*** ----- [[paper]](https://www.sciencedirect.com/science/article/pii/S016786551730171X?casa_token=_kn2EpjPDt0AAAAA:NDnKeeNwqUvCqzkzjsgRBEVYgJBk2phQYa_wZNkAUfksyQsuv7NzSYcBcX6Z5bZs2ClG7vbR9ww)[code] <br>
  > Li C., Guo J., Guo C., Cong R., Gong J. A hybrid method for underwater image correction Pattern Recognit Lett, 94 (2017), pp. 62-67

* ***`TS`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8266583)[code] <br>
  > X. Fu, Z. Fan, M. Ling, Y. Huang and X. Ding, "Two-step approach for single underwater image enhancement," 2017 International Symposium on Intelligent Signal Processing and Communication Systems (ISPACS), 2017, pp. 789-794, doi: 10.1109/ISPACS.2017.8266583.

* ***`MRP`*** ----- [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Fast_Haze_Removal_CVPR_2017_paper.pdf)[code] <br>
  > Jing Zhang, Yang Cao, Shuai Fang, Yu Kang, and Chang Wen Chen. Fast haze removal for nighttime image using maximum reflectance prior. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 7418–7426, 2017. 1, 2, 7, 8

* ***`UVSB`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/7989087)[code] <br>
  > Younggun Cho and Ayoung Kim.Visibility enhancement for underwater visual slam based on underwater light scattering model. In 2017 IEEE International Conference on Robotics and Automation (ICRA), pages 710–717. IEEE, 2017. 1, 2, 7, 8

* ***`GDCP`*** ----- [[paper]](https://ieeexplore.ieee.org/document/8307410)[code] <br>
  > Peng Y., Cao K., Cosman P.C. Generalization of the dark channel prior for single image restoration IEEE Trans Image Process, 27 (6) (2018), pp. 2856-2868

* ***`GVF`*** ----- [[paper]](https://www.sciencedirect.com/science/article/pii/S1047320319303530?casa_token=n-B0bDz4IYYAAAAA:NHjAfpQznSTLcdExB52h5Z-_AQjL5BiGcwz_46P_cSYNNXWuU7WAmo2WReCTjpMGJ-20UJJilEs)[code] <br>
  > Hou G., Li J., Wang G., Yang H., Huang B., Pan Z. A novel dark channel prior guided variational framework for underwater image restoration J Vis Commun Image Represent, 66 (2020), Article 102732

* ***`Deep SESR`*** ----- [[paper]](https://arxiv.org/abs/2002.01155)[code] <br>
  > M. J. Islam, P. Luo and J. Sattar, "Simultaneous Enhancement and Super-Resolution of Underwater Imagery for Improved Visual Perception", Robotics: Science and Systems (RSS), 2020.

* ***`NUDCP`*** ----- [[paper]](https://ieeexplore.ieee.org/abstract/document/8957276)[code] <br>
  > W. Song, Y. Wang, D. Huang, A. Liotta, and C. Perra, “Enhancement of Underwater Images with Statistical Model of Background Light and Optimization of Transmission Map,” IEEE Trans. Broadcast. 66(1), 153–169 (2020).

----------
----------
