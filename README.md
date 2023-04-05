# ViT-MNIST-Pytorch

简化了Pytorch Vision Transformer（ViT）的实现，并提供了详细的步骤。

该网络是[An Image is Worth 16X16 Words](https://arxiv.org/pdf/2010.11929.pdf)原始架构的缩小版用于对MNIST数据集进行分类。

该模型在MNIST上的测试准确率约为**99.4%**，在FashionMNIST中的测试准确度约为**91.2%**。

运行命令: <br>
python main.py --dset mnist <br>
python main.py --dset fmnist

<br><br>
Transformer 配置:

 | <!-- -->    | <!-- -->    |
--- | --- | 
Input Size | 28 |
Patch Size | 4 | 
Sequence Length | 7*7 = 49 |
Embedding Size | 64 | 
Num of Layers | 6 | 
Num of Heads | 4 | 
Forward Multiplier | 2 | 
