## DCGAN介绍

***UNSUPERVISED REPRESENTATION LEARNING WITH DEEP CONVOLUTIONAL GENERATIVE ADVERSARIAL NETWORKS*** https://arxiv.org/pdf/1511.06434.pdf

***译文：***https://ask.julyedu.com/question/7681

## 项目描述及需求

#### **DCGAN生成标识牌图像：**

生成对抗网络作为无监督学习的一种方法，网络包括一个生成模型G和一个判别模型D：

生成模型的输入是一个随机生成的向量，长度不定，输出是一个具有一定大小的图像。

判别模型的输入维度和G的输出一样，通过输出判定生成图片与真实图片是否相似。

通过两个模型的对抗过程，期望G生成一个足够真的图像，而D能保证验证的准确率。

## 项目准备

3k-5k张经过处理后的图片：



学习dcgan

帖子：

https://blog.csdn.net/yzxnuaa/article/details/79723187

https://blog.csdn.net/liuxiao214/article/details/74502975



框架：tensorflow（python）

开源项目：https://github.com/carpedm20/DCGAN-tensorflow.git

训练数据集：MNIST、SVHN（暂时，参考训练数据集https://www.jianshu.com/p/183ecfbcae20）



#### 





