# Awesome-Underwater-Image-Enhancement
The information about underwater images enhancment(updating……)

# Commomly-used Physical Models
* atmospheric acattering model [[paper]]()
* simplified model [[paper]](https://ieeexplore.ieee.org/document/6104148)
* revised model [[paper]](https://ieeexplore.ieee.org/document/8578801)

# Datasets
### 1 Fish4Knowledge <br>
由欧洲联盟海洋生态系统研究第七框架项目资助，该项目提供了一个视频和鱼类分析数据集(约200Tb) <br>
http://groups.inf.ed.ac.uk/f4k/index.html <br>
### 2 ULFID <br>
水下光场图像数据集包含了几张在纯水和朦胧条件下的水下光场图像，以及在空气中拍摄的图像供参考 <br>
https://github.com/kskin/data <br>
### 3 MARIS <br>
Marine Autonomous Robotics for InterventionS（海洋干预自主机器人）为了推进在海洋产业、搜救任务和各种各样的科学探索中，合作式AUVs的发展,该项目提供了几种水下立体视觉系统拍摄的水下图像和视频 <br>
http://rimlab.ce.unipr.it/Maris.html <br>
### 4 Haze-line Dataset <br>
收集了在不同地点拍摄的不同水属性的图像数据集，显示了场景中的颜色图表(约33GB)，并基于立体成像计算场景的三维结构 <br>
http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html <br>
### 5 UIEBD <br>
Underwater Image Enhancement Benchmark Dataset（水下图像增强基准数据集） <br>
  a. 包含950张真实水下图像，其中890张具有相应的参考图像，每个参考图像是从12个增强结果中选择的。其余60幅无法获得满意参考资料的水下图像作为具有挑战性的数据处理 <br>
  b. 包含一个大范围的图像分辨率和跨越不同的场景/主要对象类别 <br>
https://li-chongyi.github.io/proj_benchmark.html <br>

# Survey
* Saeed Anwar and Chongyi Li, “Diving deeper into underwater image enhancement: A survey,”Signal Processing-image Communication, 2020, doi: 10.1016/j.image.2020.115978.[[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0923596520301478)[[note]](https://www.yuque.com/u12128212/yrs2r6/gu6n1o)
* M. Han, Z. Lyu, T. Qiu, and M. Xu, “A Review on Intelligence Dehazing and Color Restoration for Underwater Images,” IEEE Trans. Syst. Man Cybern, Syst., vol. 50, no. 5, pp. 1820–1832, May 2020, doi: 10.1109/TSMC.2017.2788902. [[paper]](https://ieeexplore.ieee.org/document/8267119)

# 1 The backbone of these model almost use CNN.
## 1.1
This part is almost CNN-based single-information methods
* Sun, X., Liu, L., Li, Q., Dong, J., Lima, E., Yin, R.: Deep pixel to pixel network for underwater image enhancement and restoration. IET Image Processing (2018) [[paper]](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/iet-ipr.2018.5237)`P2P`
* Y. Wang, J. Zhang, Y. Cao and Z. Wang, "A deep CNN method for underwater image enhancement," 2017 IEEE International Conference on Image Processing (ICIP), 2017, pp. 1382-1386, doi: 10.1109/ICIP.2017.8296508. [[paper]](https://ieeexplore.ieee.org/document/8296508) `UIE-Net`

## 1.2
This part is almost CNN-based supplementary-information methods
* C. Li, S. Anwar, J. Hou, R. Cong, C. Guo, and W. Ren, “Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding,” IEEE Trans. on Image Process., vol. 30, pp. 4985–5000, 2021, doi: 10.1109/TIP.2021.3076367.[[paper]](https://ieeexplore.ieee.org/document/9426457/)[[code]](https://github.com/Li-Chongyi/Ucolor)`Ucolor`
* C. Li, S. Anwar, and F. Porikli, “Underwater scene prior inspired deep underwater image and video enhancement,” Pattern Recognition, vol. 98, p. 107038, Feb. 2020, doi: 10.1016/j.patcog.2019.107038.[[paper]](https://linkinghub.elsevier.com/retrieve/pii/S0031320319303401)[[code]](https://github.com/saeed-anwar/UWCNN)`UWCNN`
* C. Li et al., “An Underwater Image Enhancement Benchmark Dataset and Beyond,” arXiv:1901.05495 [cs], Nov. 2019, Accessed: Dec. 15, 2021. [[paper]](http://arxiv.org/abs/1901.05495)[[code]](https://github.com/Li-Chongyi/Water-Net_Code)`Water-Net`
* M. Hou, R. Liu, X. Fan and Z. Luo, "Joint Residual Learning for Underwater Image Enhancement," 2018 25th IEEE International Conference on Image Processing (ICIP), 2018, pp. 4043-4047, doi: 10.1109/ICIP.2018.8451209. [[paper]](https://ieeexplore.ieee.org/document/8451209)`URCNN`
* K. Cao, Y. Peng and P. C. Cosman, "Underwater Image Restoration using Deep Networks to Estimate Background Light and Scene Depth," 2018 IEEE Southwest Symposium on Image Analysis and Interpretation (SSIAI), 2018, pp. 1-4, doi: 10.1109/SSIAI.2018.8470347. [[paper]](https://ieeexplore.ieee.org/document/8470347)`UIR-Net`

# 2 The backbone of these model almost use GAN.
## 2.1
This part is almost GAN-based single-information methods
* Fabbri, C., Islam, M.J., Sattar, J.: Enhancing underwater imagery using generative adversarial networks. arXiv preprint arXiv:1801.04011 (2018) [[paper]](https://scholar.google.com/scholar?q=Enhancing%20Underwater%20Imagery%20using%20Generative%20Adversarial%20Networks)`UGAN`
* Y. Guo, H. Li and P. Zhuang, "Underwater Image Enhancement Using a Multiscale Dense Generative Adversarial Network," in IEEE Journal of Oceanic Engineering, vol. 45, no. 3, pp. 862-870, July 2020, doi: 10.1109/JOE.2019.2911447. [[paper]](https://ieeexplore.ieee.org/document/8730425)`GenseGAN`

## 2.2
This part is almost GAN-based supplementary-information methods
* Li, H., Li, J., Wang, W.: A Fusion Adversarial Underwater Image Enhancement Network with a Public Test Dataset. arXiv e-prints arXiv:1906.06819 (2019) [[paper]](https://arxiv.org/abs/1906.06819)`FGAN`
* Lu, J., Li, N., Zhang, S., Yu, Z., Zheng, H., Zheng, B.: Multi-scale adversarial network for underwater image restoration. Optics & Laser Technology (2019) [[paper]](https://www.sciencedirect.com/science/article/pii/S003039921830690X?via%3Dihub)

## 2.3
This part is almost multi-generator or multi-discriminator GAN-based methods
* Jolicoeur-Martineau, A.: The relativistic discriminator: a key element missing from standard gan. arXiv preprint arXiv:1807.00734 (2018) [[paper]](https://scholar.google.com/scholar?q=The%20relativistic%20discriminator:%20a%20key%20element%20missing%20from%20standard%20GAN)`UWGAN`
* Ren, S., He, K., Girshick, R., etal: Guided image filtering. TPAMI (2017) [[paper]](https://link.springer.com/chapter/10.1007%2F978-3-642-15549-9_1)`MCycleGAN`

# 3 Characteristic Novel Approach
* Uplavikar, P., Wu, Z., Wang, Z.: All-in-one underwater image enhancement using domain-adversarial learning. arXiv preprint arXiv:1905.13342 (2019) [[paper]](https://scholar.google.com/scholar?q=All-in-One%20Underwater%20Image%20Enhancement%20Using%20Domain-Adversarial%20Learning)
* Ronneberger, O., Fischer, P., Brox, T.: U-net: Convolu- tional networks for biomedical image segmentation. In: International Conference on Medical image computing and computer-assisted intervention (2015) [[paper]](https://scholar.google.com/scholar?q=U-Net:%20Convolutional%20Networks%20for%20Biomedical%20Image%20Segmentation)`UIE-sGAN`

# 4 Comparison
* ***SSR*** [[paper]](https://ieeexplore.ieee.org/abstract/document/557356)[code] <br>
> Jobson D.J., Rahman Z. Properties and performance of a center/surround retinex IEEE Trans Image Process, 6 (3) (1997), pp. P.451-462 <br>

* Jobson D.J., Rahman Z., Woodell G.A. A multiscale retinex for bridging the gap between color images and the human observation of scenes IEEE Trans Image Process, 6 (7) (2002), pp. 965-976 <br>
`MSR`[paper][code]

* `MR`[paper][code] <br>
Rahman Z, Jobson DJ, Woodell GA. Multi-scale retinex for color image enhancement. In: Proceedings of 3rd IEEE international conference on image processing. 2002.
* `FB`[paper][code] <br>
Ancuti C, Ancuti CO, Haber T, Bekaert P. Enhancing underwater images and videos by fusion. In: IEEE conference on computer vision & pattern recognition. 2012, p. 81–8.
* `UWCNN`[paper][code] <br>
Li C., Anwar S. Underwater scene prior inspired deep underwater image and video enhancement Pattern Recognit, 98 (2019), Article 107038
* `TB`[paper][code] <br>
Drews JP, Nascimento E, Moraes F, Botelho S, Campos M. Transmission estimation in underwater single images. In: IEEE international conference on computer vision workshops. 2013.
* `DCP`[paper][code] <br>
K. He, J. Sun and X. Tang, "Single image haze removal using dark channel prior", IEEE transactions on pattern analysis and machine intelligence, 2011.
* `IBLA`[paper][code] <br>
Y.-T. Peng and P. C. Cosman, "Underwater image restoration based on image blurriness and light absorption", IEEE transactions on image processing, 2017.
* `UGAN`[paper][code] <br>
C. Fabbri, M. J. Islam and J. Sattar, "Enhancing underwater imagery using generative adversarial networks", IEEE International Conference on Robotics and Automation (ICRA), 2018.
* `Water-Net`[paper][code] <br>
C. Li, C. Guo, W. Ren, R. Cong, J. Hou, S. Kwong, et al., "An underwater image enhancement benchmark dataset and beyond", IEEE Transactions on Image Processing, 2019.
* `FUnIE-GAN`[paper][code] <br>
M. J. Islam, Y. Xia and J. Sattar, "Fast underwater image enhancement for improved visual perception", IEEE Robotics and Automation Letters, 2020.
* `Deep SESR`[paper][code] <br>
M. J. Islam, P. Luo and J. Sattar, "Simultaneous Enhancement and Super-Resolution of Underwater Imagery for Improved Visual Perception", Robotics: Science and Systems (RSS), 2020.
* `NUDCP`[paper][code] <br>
W. Song, Y. Wang, D. Huang, A. Liotta, and C. Perra, “Enhancement of Underwater Images with Statistical Model of Background Light and Optimization of Transmission Map,” IEEE Trans. Broadcast. 66(1), 153–169 (2020).
* `(SR)CNN`[paper][code] <br>
Y. Li, C. Ma, T. Zhang, J. Li, Z. Ge, Y. Li, and S. Serikawa, “Underwater Image High Definition Display Using the Multilayer Perceptron and Color Feature-Based SRCNN,” IEEE Access 7, 83721–83728 (2019).
* `FA`[paper][code] <br>
Y. Wang, H. Liu, and L.-P. Chau, “Single underwater image restoration using attenuation-curve prior,” in Proc. IEEE Int. Symp. Circuits Syst. May 2017.
* `UDCP`[paper][code] <br>
Drews P.L.J., Nascimento E.R., Botelho S.S.C., Montenegro Campos M.F. Underwater depth estimation and image restoration based on single images IEEE Comput Graph Appl, 36 (2) (2016), pp. 24-35
* `UIC`[paper][code] <br>
Li C., Guo J., Guo C., Cong R., Gong J. A hybrid method for underwater image correction Pattern Recognit Lett, 94 (2017), pp. 62-67
* `GDCP`[paper][code] <br>
Peng Y., Cao K., Cosman P.C. Generalization of the dark channel prior for single image restoration IEEE Trans Image Process, 27 (6) (2018), pp. 2856-2868
* `GVF`[paper][code] <br>
Hou G., Li J., Wang G., Yang H., Huang B., Pan Z. A novel dark channel prior guided variational framework for underwater image restoration J Vis Commun Image Represent, 66 (2020), Article 102732
* `RBEA` <br>
Fu X., Zhuang P., Huang Y., Liao Y., Zhang X., Ding X. A retinex-based enhancing approach for single underwater image 2014 IEEE international conference on image processing (ICIP) (2014), pp. 4572-4576
* `TS`[paper][code] <br>
Two-step approach for single underwater image enhancement 2017 international symposium on intelligent signal processing and communication systems (ISPACS) (2017), pp. 789-794
* `MCCM`[paper][code] <br>
Single image defogging based on multi-channel convolutional msrcr IEEE Access, 7 (2019), pp. 72492-72504
* `CCBE`[paper][code] <br>
Zhang W., Dong L., Zhang T., Xu W. Enhancing underwater image via color correction and bi-interval contrast enhancement Signal Process, Image Commun, 90 (2021), Article 116030
* `Haze Line`[paper][code] <br>
D. Berman, T. Treibitz, S. Avidan Diving into haze-lines: color restoration of underwater images Proc. British Machine Vision Conference (BMVC), 1 (2017)
* `Histogram Prior`[paper][code] <br>
C.-Y. Li, J.-C. Guo, R.-M. Cong, Y.-W. Pang, B. Wang Underwater image enhancement by dehazing with minimum information loss and histogram distribution prior IEEE Trans. Image Process., 25 (12) (2016), pp. 5664-5677
* `CycleGAN`[paper][code] <br>
J. Zhu, T. Park, P. Isola, A.A. Efros, Unpaired image-to-image translation using cycle-consistent adversarial networks, in: IEEE International Conference on Computer Vision (ICCV), 2017, pp. 2242–2251, doi:10.1109/ICCV.2017.244.
* `CG`[paper][code] <br>
Tunai Porto Marques, Alexandra Branzan Albu, and Maia Hoeberechts. A contrast-guided approach for the enhancement of low-lighting underwater images. Journal of Imaging, 5(10):79, 2019. 1, 2, 3, 4, 5, 7, 8
* `UVSB`[paper][code] <br>
Younggun Cho and Ayoung Kim.Visibility enhancement for underwater visual slam based on underwater light scattering model. In 2017 IEEE International Conference on Robotics and Automation (ICRA), pages 710–717. IEEE, 2017. 1, 2, 7, 8
* `MRP`[paper][code] <br>
Jing Zhang, Yang Cao, Shuai Fang, Yu Kang, and Chang Wen Chen. Fast haze removal for nighttime image using maximum reflectance prior. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 7418–7426, 2017. 1, 2, 7, 8
* `VIM`[paper][code] <br>
Xiaojie Guo, Yu Li, and Haibin Ling. Lime: Low-light image enhancement via illumination map estimation. IEEE Transactions on Image Processing, 26(2):982–993, 2016. 1, 2, 7, 8
* `Ucolor`[paper][code] <br>
C. Li, S. Anwar, J. Hou, R. Cong, C. Guo and W. Ren, "Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding," in IEEE Transactions on Image Processing, vol. 30, pp. 4985-5000, 2021, doi: 10.1109/TIP.2021.3076367.
* `MDGAN`[paper][code] <br>
Y. Guo, H. Li, and P. Zhuang, “Underwater image enhancement using a multiscale dense generative adversarial network,” IEEE J. Ocean. Eng., vol. 45, no. 3, pp. 862–870, Jul. 2020.
* `UcycleGAN`[paper][code] <br>
C. Li, J. Guo, and C. Guo, “Emerging from water: Underwater image color correction based on weakly supervised color transfer,” IEEE Signal Process. Lett., vol. 25, no. 3, pp. 323–327, Mar. 2018.
* `Unet`[paper][code] <br>
J. Kim, J. K. Lee, and K. M. Lee, “Accurate image super-resolution using very deep convolutional networks,” in Proc. IEEE Conf. Comput. Vis. Pattern Recognit. (CVPR), Jun. 2016, pp. 1646–1654.
