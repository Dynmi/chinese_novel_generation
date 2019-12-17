# chinese_novel_generation
中文小说生成，RNN/机器学习/LSTM/神经网络/
————这是使用LSTM生成中文小说的一个小尝试。
————RNN的架构为Input -> LSTM -> Dropout -> LSTM -> Dropout -> Fully Connected

————使用方法A和B：
  A.这里提供了一段神雕侠侣第一章的片段txt，可以拿来用，直接使用默认的配置，跑一遍代码，生成一段小说文本。
  B.把txtpath改成自己定义的待输入的小说片段文本文档的地址，然后根据个人需求处理原始文本数据，以及修改模型超参数，然后训练模型，跑一遍。
