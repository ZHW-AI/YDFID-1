# YDFID-3
Yarn-Dyed Fabric Image Dataset Version3，色织物图像数据集第三版 (For the English version, please open README_ENG.md)

——张宏伟西安工程大学人工智能课题组

# 色织物样本数据集Version3简介

色织物样本数据集Version3由西安工程大学电子信息学院张宏伟人工智能课题组整理并开源，共有30种花型。该数据集共包含无缺陷样本图像5224张，缺陷样本图像444张，图像的分辨率为512×512×3。
色织物数据集Version3放于YDFID-3文件夹中，包含Simple Lattices（简单方格类），Stripe Patterns（条纹类）和Complex Lattices（复杂方格类）三类花型。这三类花型分别放置于三个文件夹，依次命名为SL，SP，CL。其中SL由10个子文件夹组成，CL由10个子文件夹组成，SP由10个子文件夹组成，总结构如图所示。

<img width="604" alt="db4e565fea72fd1e61ff5ab3fb9362a" src="https://github.com/ZHW-AI/YDFID-1/assets/86339216/d439407a-a1a5-4b6d-a7bc-f452424f864e">



YDFID-3数据集总体文件结构图


# YDFID-2
Yarn-Dyed Fabric Image Dataset Version2，色织物图像数据集第二版 (For the English version, please open README_ENG.md)

——张宏伟西安工程大学人工智能课题组

# 色织物样本数据集Version2简介

色织物样本数据集Version2由西安工程大学电子信息学院张宏伟人工智能课题组整理并开源，共有19种花型。该数据集共包含无缺陷样本图像3500张，缺陷样本图像330张，图像的分辨率为512×512×3。
色织物数据集Version2放于YDFID-1文件夹中，包含Simple Lattices（简单方格类），Stripe Patterns（条纹类）和Complex Lattices（复杂方格类）三类花型。这三类花型分别放置于三个文件夹，依次命名为SL，SP，CL。其中SL由9个子文件夹组成，CL由6个子文件夹组成，SP由4个子文件夹组成，总结构如图所示。

![YDFID-2](https://user-images.githubusercontent.com/86339216/175951521-8f55361c-eaaf-4c5d-acd1-3d8ba33a4f87.png)

YDFID-2数据集总体文件结构图


# YDFID-1
Yarn-dyed Fabric Image Dataset Version1，色织物图像数据集第一版 (For the English version, please open README_ENG.md)

——张宏伟西安工程大学人工智能课题组

# 色织物样本数据集Version1简介

色织物样本数据集Version1由西安工程大学电子信息学院张宏伟人工智能课题组整理并开源，共有17种花型，如图1所示。该数据集共包含无缺陷样本图像3189张，缺陷样本图像312张，图像的分辨率为512×512×3。

![图1](https://user-images.githubusercontent.com/86339216/123066362-92c13e00-d442-11eb-9dcd-b021d7dc9b55.jpg)

17种花型样本图

![图2](https://user-images.githubusercontent.com/86339216/123066678-dfa51480-d442-11eb-9e6d-bec3d2baf43f.jpg)

色织物缺陷样本

色织物数据集Version1放于YDFID-1文件夹中，包含Simple Lattices（简单方格类），Stripe Patterns（条纹类）和Complex Lattices（复杂方格类）三类花型。这三类花型分别放置于三个文件夹，依次命名为SL，SP，CL。其中SL由7个子文件夹组成，CL由6个子文件夹组成，SP由4个子文件夹组成，总结构如图所示。

![图3](https://user-images.githubusercontent.com/86339216/123086029-85fa1580-d455-11eb-94fc-f153e370d535.jpg)

YDFID-1数据集总体文件结构图

每种色织物花型的数据集文件包含训练集train和测试集test两个子文件夹。其中，训练集为无缺陷样本,放置于defect-free文件夹；测试集为无缺陷样本defect-free、有缺陷样本defect及标记缺陷区域的ground truth。以SL1花型为例，它的文件结构图如图4所示。

![图4](https://user-images.githubusercontent.com/86339216/123067333-7a055800-d443-11eb-834f-d0621078927f.jpg)

SL1花型文件结构图

# 数据集获取：

数据集收集不易，本数据集免费分享，但是有以下两点要求，如果给您带来不便，敬请谅解，我们在审核后会将下载链接以邮件形式发送给您：

1. 将申请电子邮件发送到hwzhang@xpu.edu.cn。

邮件标题:请使用“织物数据集获取”。它是一个固定的形式和一个特殊的标志，用于与其他邮件进行区分。

邮件主体:您的姓名；您的组织或院校；您目前进行的主要工作；数据集的用途；承诺：（1）不私自传播该数据集（2）在文章中贴出我们的数据集CSDN、github链接或者在引用我们文章列表中的文章进行对比实验时介绍该数据集 (3)在文章发表后同意给我们引用文章的证明图文（4）本数据集仅用于学术研究，严禁用于商业用途或者商业传播，否则本课题组保留追诉的权利。

您的邮箱地址：我们会将链接和提取密码发送到您的邮箱

2. 如果您将数据集用于文章的发表，请引用以下几篇文章：

[1] Zhang Hongwei, Liu Shuting, Tan Quanlu, Lu Shuai, Yao Le, Ge Zhiqiang. Colour-patterned fabric defect detection based on an unsupervised multi-scale U-shaped denoising convolutional autoencoder model. Coloration Technology, 2022. DOI:10.1111/cote.12609.

[2] Zhang Hongwei, Zhang Weiwei, Wang Yang, Lu Shuai, Yao Le, Chen Xia. Colour-patterned fabric-defect detection using unsupervised and memorial defect-free features. Coloration Technology, 2022. DOI:10.1111/cote.12624.

[3] ZHANG Hongwei, TAN Quanlu, LU Shuai, et al. Yarn-dyed shirt piece defect detection based on an unsupervised reconstruction model of the U-shaped denoising convolutional auto-encoder [J]. Journal of Xidian University, 2021, 48(03): 123-130.

[4] ZHANG Hongwei, LIU Shuting,LU Shuai,et al.Defect detection of yarn-dyed fabric based onmulti-scale convolutional encoder[J].Basic Sciences Journal of Textile Universities,2021,34(2):45-51.

[5] ZHANG Hongwei, ZHANG Weiwei,XIONG Wenbo,et al.Defect detection of yarn-dyed fabric based on memory denoising convolutional auto-encoder[J].Basic Sciences Journal of Textile Universities,2022,35(2):64-71.

[6] ZHANG Hongwei, MI Hongmin,LU Shuai,et al.Defect detection of yarn-dyed fabric based on generative adversarial networks[J].Journal of Xi’an Polytechnic University,2022,36(1):1-9.

# 关于我们

CSDN链接：https://blog.csdn.net/m0_37758063?spm=1000.2115.3001.5343
