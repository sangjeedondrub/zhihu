![](https://img.shields.io/badge/liscense-by%20NelsonZhao-brightgreen.svg)    ![](https://img.shields.io/badge/health-100%25-brightgreen.svg)    ![](https://img.shields.io/badge/programming%20language-Python-orange.svg)


## 简介

该Repo内容为知乎专栏《机器不学习》的源代码。

专栏地址：<https://zhuanlan.zhihu.com/zhaoyeyu>

## 代码框架
```TensorFlow```

## 包含内容

### 1.anna_lstm
基于RNN（LSTM）对《安娜卡列尼娜》英文文本的学习，实现一个字符级别的生成器。 
> 文章地址：[《安娜卡列尼娜》文本生成——利用TensorFlow构建LSTM模型
](https://zhuanlan.zhihu.com/p/27087310)


### 2.skip-gram
实现skip-gram算法的Word2Vec，基于对英文语料的训练，模型学的各个单词的嵌入向量。
> 文章地址：[基于TensorFlow实现Skip-Gram模型](https://zhuanlan.zhihu.com/p/27296712)


### 3.generate_lyrics
基于RNN实现歌词生成器。


### 4.basic_seq2seq
基于RNN Encoder-Decoder结构的Seq2Seq模型，实现对一个单词中字母的排序。
> 文章地址：[从Encoder到Decoder实现Seq2Seq模型](https://zhuanlan.zhihu.com/p/27608348)


### 5.denoise\_auto\_encoder
基于MNIST手写数据集训练了一个自编码器，并在此基础上增加卷积层实现一个卷积自编码器，从而实现对图像的降噪。
> 文章地址：[利用卷积自编码器对图片进行降噪](https://zhuanlan.zhihu.com/p/27902193)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/denoise_auto_encoder/dae_example.png)

### 6.cifar_cnn
对Kaggle上CIFAR图像分类比赛的一个实现，分别对比了KNN和卷积神经网络在数据上的表现效果。
> 文章地址：[利用卷积神经网络处理CIFAR图像分类](https://zhuanlan.zhihu.com/p/28035475)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/cifar_cnn/example_pic.png)


### 7.mnist_gan
基于MNIST手写数据集，训练了一个隐层为Leaky ReLU的生成对抗网络，让模型学会自己生成手写数字。
> 文章地址：[生成对抗网络（GAN）之MNIST数据生成](https://zhuanlan.zhihu.com/p/28057434)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/mnist_gan/gan_examples.png)

### 8.dcgan
基于MNIST数据集训练了一个DCGAN，加入了Batch normalization，加速模型收敛并提升新能。
> 文章地址：[深度卷积GAN之图像生成](https://zhuanlan.zhihu.com/p/28329335)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/dcgan/mnist_dcgan_pic.png)

> 基于CIFAR数据集中的马的图像训练一个DCGAN生成马的图像。
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/dcgan/cifar_dcgan_pic.png)

### 9.batch\_normalization\_discussion
该部分代码基于MNIST手写数据集构造了一个三层的全连接层神经网络。通过改变不同参数来测试BN对于模型性能的影响。同时利用TensorFlow实现底层的batch normalization。
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/batch_normalization_discussion/bn_example.png)


### 不定期更新干货，欢迎Star，欢迎Fork。