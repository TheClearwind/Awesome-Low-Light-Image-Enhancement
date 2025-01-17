# Awesome-Low-Light-Image-Enhancement

## Papers and Codes
### Review && Related Work
[2021 *IJCV*] Benchmarking Low-Light Image Enhancement and Beyond [Paper](https://link.springer.com/content/pdf/10.1007/s11263-020-01418-8.pdf)

[2020 *IEEE ACCESS*] An Experiment-Based Review of Low-Light
Image Enhancement Methods [Paper](https://ieeexplore.ieee.org/document/9088214)


### HE-Based Algorithm

Todo

### Retinex-Based Algorithm
[2020 *TIP*] LR3M: Robust Low-Light Enhancement via
Low-Rank Regularized Retinex Model [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9056796)

[2018 *TIP*] Structure-Revealing Low-Light Image Enhancement via Robust Retinex Model [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8304597)

[2016 *CVPR*] **MF:** A weighted variational model for simultaneous reflectance and illumination estimation [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780673) [Code](https://xueyangfu.github.io/Paper/2016/cvpr/Matlab_implementation.zip)

[2017 *TIP*] **LIME:** Low-Light Image Enhancement via Illumination Map Estimation [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7782813) [Code](https://sites.google.com/view/xjguo/lime)

### Denoise-Based Algorithm

Todo

### Supervised-Deep-Learning Algorithm
[2021 *TIP*] Sparse Gradient Regularized Deep Retinex Network for Robust Low-Light Image Enhancement [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9328179)

[2021 *IJCV*] Attention-guided Low-light Image Enhancement [Paper](https://arxiv.org/pdf/1908.00682.pdf) [Code](https://github.com/yu-li/AGLLNet)

[2021 *Preprint*] R2RNet: Low-light Image Enhancement via Real-low to Real-normal Network [Paper](https://arxiv.org/pdf/2106.14501.pdf) [Code](https://github.com/abcdef2000/R2RNet)

[2020 *CVPR*] Learning to Restore Low-Light Images via Decomposition-and-Enhancement [Paper](https://openaccess.thecvf.com/content_CVPR_2020/Papers/Xu_Learning_to_Restore_Low-Light_Images_via_Decomposition-and-Enhancement_CVPR_2020_Paper.pdf)


[2018 *BMVC*] **Retinex-Net:** Deep Retinex Decomposition for Low-Light Enhancement [Paper](https://arxiv.org/pdf/1808.04560.pdf) [Code](https://github.com/weichen582/RetinexNet)

[2018 *FG*] **GLADNet:** Low-Light Enhancement Network with Global Awareness [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8373911) [Code](https://github.com/weichen582/GLADNet)

[2018 *CVPR*] Learning to See in the Dark [Paper](https://openaccess.thecvf.com/content_cvpr_2018/Papers/Chen_Learning_to_See_CVPR_2018_Paper.pdf) [Code](https://github.com/cchen156/Learning-to-See-in-the-Dark)

### Semi-Supervised-Deep-Learning Algorithm

[2020 *CVPR*] **DRBN:** From Fidelity to Visual Quality: A Semi-Supervised Approach for Low-Light Image Enhancement [Paper](https://openaccess.thecvf.com/content_CVPR_2020/Papers/Yang_From_Fidelity_to_Perceptual_Quality_A_Semi-Supervised_Approach_for_Low-Light_CVPR_2020_Paper.pdf) [Code](https://github.com/flyywh/CVPR-2020-Semi-Low-Light)

### Unsupervised-Deep-Learning Algorithm

[2020 *CVPR*] **Zero-DCE:** Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement [Paper](https://openaccess.thecvf.com/content_CVPR_2020/Papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_Paper.pdf) [Code](https://github.com/Li-Chongyi/Zero-DCE)

[2020.2 *SPL*] Unsupervised Low-Light Image Enhancement Using
Bright Channel Prior [Paper](https://ieeexplore.ieee.org/document/8955834)

[2019.6 *Preprint*] **EnlightenGAN:** Deep Light Enhancement without Paired Supervision [Paper](https://arxiv.org/abs/1906.06972) [Code](https://github.com/TAMU-VITA/EnlightenGAN)

### Low-light Video Enhancement
[2021 *CVPR*] [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Learning_Temporal_Consistency_for_Low_Light_Video_Enhancement_From_Single_CVPR_2021_paper.pdf) [Code](https://github.com/zkawfanx/StableLLVE)

### Application
[2021 *TMM*] Recurrent Exposure Generation for Low-Light Face Detection [Paper](https://arxiv.org/pdf/2007.10963.pdf)

[2021 *CVPR*] HLA-Face: Joint High-Low Adaptation for Low Light Face Detection [Paper](https://arxiv.org/pdf/2104.01984.pdf)

[2020 *ACM MM*] Integrating Semantic Segmentation and Retinex Model [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413757)

## Datasets

LOL(**LO**w-**L**ight): 500 pairs images. [Download](https://daooshee.github.io/BMVC2018website/)

GladNet-Dataset: [Download](https://daooshee.github.io/fgworkshop18Gladnet/)

Synthetic Dataset [Download](http://phi-ai.org/project/AgLLNet/default.htm)

SID(**S**ee **I**n the **D**ark) [Download](https://github.com/cchen156/Learning-to-See-in-the-Dars)

MIT-Adobe FiveK Dataset [Download](https://data.csail.mit.edu/graphics/fivek/)

Exclusively-Dark-Image-Dataset [Download](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset)

Darkface [Download](https://flyywh.github.io/ChinaMM2019FDLOL/)

LSRW [Download](https://github.com/abcdef2000/R2RNet)

## Indexes 

#### Full Reference Quality Indexes

MSE [Matlab](https://www.mathworks.com/help/images/ref/immse.html)

PSNR [Matlab](https://www.mathworks.com/help/images/ref/psnr.html)

SSIM [Matlab](https://www.mathworks.com/help/images/ref/ssim.html)

UQI [Matlab](https://live.ece.utexas.edu/research/Quality/zhou_research_anch/quality_index/demo.html)

TQMI [Matlab](https://ece.uwaterloo.ca/~z70wang/research/tmqi/)

#### No-Reference Quality Indexes

NIQE [Matlab](https://www.mathworks.com/help/images/ref/niqe.html) 

LOE [Matlab](https://shuhangwang.wordpress.com/2015/12/14/naturalness-preserved-enhancement-algorithm-for-non-uniform-illumination-images/)

## Related Work

Bak of codes and datasets [Baidu Drive](https://pan.baidu.com/s/1Dm0KDZkuDZ_TCbeiVR_ZIg) (hxyi) <!--[Google Drive]()-->

## Reference

To do

## Citing

```
@Misc{2021shiALLIE,
	howpublished = {\url{https://github.com/ymmshi/Awesome-Low-Light-Enhancement}},
	title = {Awesome-Low-Light-Image-Enhancement},
	author = {ymshi},
}
```

If your research interests is related to low-light image enhancement, please contact us, email: ymshi At mail.ustc.edu.cn

Welcome to pull requests or create issues!