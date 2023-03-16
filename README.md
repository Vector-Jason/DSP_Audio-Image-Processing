# DSP_Audio-Image-Processing
结合数字信号处理中窗函数的思想，搭建音频和图像处理系统，提取多域特征，进行滤波处理。

详情可了解<a href='https://www.bilibili.com/video/BV12G4y1m7mY/?spm_id_from=333.999.0.0&vd_source=a24c565b3a8dffe05e6d6502dbb5f36a'>音像处理系统-Bilibili</a>。

由于音频处理文件较大无法上传，此处主要具体介绍图像处理的结果：

![image](https://github.com/Vector-Jason/DSP_Audio-Image-Processing/blob/main/%E5%9B%BE%E5%83%8F%E5%A4%84%E7%90%86.png)

首先将输入图像进行傅里叶变化，再通过自主设计的高斯高通滤波器进行滤波，最后通过反变换即可获得经过高斯高通滤波器后的结果图像。

可见高通滤波器能够提取出图像的边缘特征，即高频特征，这符合我们的直观认识。
