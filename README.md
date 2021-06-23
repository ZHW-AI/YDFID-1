# YDFID-1
Yarn-dyed Fabric Image Dataset Version1，色织物图像数据集第一版

——张宏伟西安工程大学人工智能课题组

# 色织物样本数据集Version1简介

色织物样本数据集Version1由西安工程大学电子信息学院张宏伟人工智能课题组整理并开源，共有17种花型，如图1所示。该数据集共包含无缺陷样本图像3189张，缺陷样本图像312张，图像的分辨率为512×512×3，部分缺陷样本如图2所示。

![图1](https://user-images.githubusercontent.com/86339216/123066362-92c13e00-d442-11eb-9dcd-b021d7dc9b55.jpg)

图1 17种花型样本图

![图2](https://user-images.githubusercontent.com/86339216/123066678-dfa51480-d442-11eb-9e6d-bec3d2baf43f.jpg)

图2 色织物缺陷样本

色织物数据集Version1放于YFDⅠ文件夹中，包含Simple Lattices（简单方格类），Stripe Patterns（条纹类）和Complex Lattices（复杂方格类）三大类花型。这三大类花型分别放置于三个文件夹，依次命名为SL，SP，CL。其中SL由7个子文件夹组成，CL由6个子文件夹组成，SP由4个子文件夹组成，总结构图如图3所示。

![图3](https://user-images.githubusercontent.com/86339216/123066426-a5d40e00-d442-11eb-905b-a39e758b4282.jpg)

图3 数据集总体文件结构图

每种色织物花型的数据集文件包含训练集train和测试集test两个子文件夹。其中，训练集为无缺陷样本,放置于defect-free文件夹；测试集为无缺陷样本defect-free、有缺陷样本defect及标记缺陷区域的ground truth。以SL1花型为例，它的文件结构图如图4所示。

![图4](https://user-images.githubusercontent.com/86339216/123067333-7a055800-d443-11eb-834f-d0621078927f.jpg)

图4 SL1样本文件结构图

# 数据集获取：

数据集收集不易，下载此数据集，有以下两点要求，如果给您带来不便，敬请谅解，我们在审核后会将下载链接以邮件形式发送给您： 

1. 将申请电子邮件发送到hwzhang@xpu.edu.cn。

邮件标题:请使用“织物数据集获取”。它是一个固定的形式和一个特殊的标志，用于与其他邮件进行区分。

邮件主体:您的组织或院校；您目前进行的主要工作；数据集的用途。

2. 如果您将数据集用于文章的发表，请引用以下几篇文章：

[1] H. W. Zhang, Q. L. Tan, S. Lu, Z. Q. Ge, and J. Xu, “Yarn-dyed shirt piece defect detection based on an unsupervised reconstruction model of the U-shaped denoising convolutional auto-encoder,” J. Xidian Univ., vol.48, no.3, pp.1-9, 2021.

[2] H. W. Zhang, S. T. Liu, S. Lu, D. Gu, and D. Yan, “Defect detection of yarn-dyed fabric based on multi-scale convolutional auto-encoder,” Basic Sci. J. Text. Univ., vol.34, no.2, pp.36-42, 2021.

[3] H. W. Zhang, W. B. Tang, L. J. Zhang, Z. Q. Ge, and D. Gu, “Defect Detection of Yarn-dyed Shirts Based on Denoising Convolutional Self-encoder,” IEEE Data Driven Control Learn. Syst. Conf. (DDCLS), pp.1263-1268, 2019.

# 关于我们

CSDN链接：https://blog.csdn.net/m0_37758063?spm=1000.2115.3001.5343
