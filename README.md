# NeuroNetworkWithPytorch
a neuro network yields 100-dim binary output



* 通过观察最后的out参数，我们可以发现我们的网络功能是很弱的
* 改进角度：
  * genNet的损失函数：我们的目标是让fitNet(val)尽可能大，有没有什么方法，既可以有梯度，效果又优于取倒数？
  * 对于fitNet训练集，我依然没有解决-1的问题
  * 激活函数
  * 神经网络结构
  * 从头再来。。。。。