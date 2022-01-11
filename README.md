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
* Saeed Anwar and Chongyi Li, “Diving deeper into underwater image enhancement: A survey,”Signal Processing-image Communication, 2020, doi: 10.1016/j.image.2020.115978.[[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0923596520301478)[[note]]()

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

# 2.3
This part is almost multi-generator or multi-discriminator GAN-based methods
* Jolicoeur-Martineau, A.: The relativistic discriminator: a key element missing from standard gan. arXiv preprint arXiv:1807.00734 (2018) [[paper]](https://scholar.google.com/scholar?q=The%20relativistic%20discriminator:%20a%20key%20element%20missing%20from%20standard%20GAN)`UWGAN`
* Ren, S., He, K., Girshick, R., etal: Guided image filtering. TPAMI (2017) [[paper]](https://link.springer.com/chapter/10.1007%2F978-3-642-15549-9_1)`MCycleGAN`

# 3 Characteristic Novel Approach
* Uplavikar, P., Wu, Z., Wang, Z.: All-in-one underwater image enhancement using domain-adversarial learning. arXiv preprint arXiv:1905.13342 (2019) [[paper]](https://scholar.google.com/scholar?q=All-in-One%20Underwater%20Image%20Enhancement%20Using%20Domain-Adversarial%20Learning)
* Ronneberger, O., Fischer, P., Brox, T.: U-net: Convolu- tional networks for biomedical image segmentation. In: International Conference on Medical image computing and computer-assisted intervention (2015) [[paper]](https://scholar.google.com/scholar?q=U-Net:%20Convolutional%20Networks%20for%20Biomedical%20Image%20Segmentation)`UIE-sGAN`

