# 点云分割资料汇总

## 文献调研
### Dynamic Graph CNN for Learning on Point Clouds
| [code - 官方推荐第三方实现版本](https://github.com/AnTao97/dgcnn.pytorch) | [paper](https://arxiv.org/pdf/1801.07829.pdf) |
| ---- | ---- |

#### 贡献
- 提出一个可嵌的新的可微分神经网络模块，能够提取局部点云特征，并保持排列不变形 - EdgeConv
- 模型能通过动态更新层与层之间的图结构来学习点集的语义信息（通过EdgeConv）
- 设计一个以点云为输入的CNN架构
- 在ModelNet40与S3DIS中获得SOTA的表现

#### 参考资料
- [不错的论文解释 - 搞懂DGCNN，这篇就够了！论文及代码完全解析](https://zhuanlan.zhihu.com/p/267895014)

#### 摘要


#### EdgeConv模块
- 设计起因
点云数据结构是离散、缺乏拓扑信息的。建立点与点之间的拓扑能力，应该可以增强表征能力。
  
- 设计原理



#### 网络结构图
![img.png](img/img.png)

## 数据集

- ModelNet40 - 分类
- S3DIS - 局部分割
- ShapeNet Part - 场景分割