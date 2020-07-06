# Chinese Novel Generation using LSTM


使用LSTM生成中文小说的一个简单尝试.

</br>

###  >>>Abandoned project<<<
</br>

## Dependencies
- tensorflow 1.5+
- numpy

## 本处所搭建的RNN结构 
- ***Input -> LSTM -> Dropout -> LSTM -> Dropout -> Fully Connected*** 

## Default HyperParameters for the model

```
# 训练循环次数
num_epochs = 200

# batch大小
batch_size = 256

# lstm层中包含的unit个数
rnn_size = 1024

# embedding layer的大小
embed_dim = 1500

# 训练步长
seq_length = 60

# 学习率
learning_rate = 0.001
```

## 提供两种试用方法A和B

A：这里上传了一段神雕侠侣第一章的片段sdxl1.txt，可以拿来用，使用默认的配置，跑一遍代码，直接生成一段小说文本。  

B： 把txtpath改成自己定义的待输入的小说片段文本文档的地址，然后根据个人需求处理原始文本数据，以及修改模型超参数，然后训练模型，跑一遍。 

## TIPS
这个模型不是很easy，最好使用算力较强的机器来跑哦。 
