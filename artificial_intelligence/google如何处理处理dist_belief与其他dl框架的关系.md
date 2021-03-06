这个问题是一个`old`或者`stale`的问题.

因为现在谷歌在大力的推广公司的 `tensorflow`.

### 一个AI商品的生命周期
1. 调研
2. 小规模实验
3. 大规模实验
4. 部署上线

### 对于研究

#### 研究的需求
1. 跟进学术界发展.
2. 快速复现最新paper中的结果.

这就要求研究的同学不能统一使用一个框架, 而且也不能要求研究人员使用一个固定的版本, 本着科学研究中的固定变量的思路. 最好要使用paper中的指定的版本(可能被论文作者修改过), 感谢github,现在论文作者也会把代码放出来.


#### 给用户自由
1. 要支持多种不同的框架
2. 给用户自由, 让研究人员自己来搞定这个事情


#### 给工程师自由
如果让工程师来做这件事情, 很不值当, 无法充分利用工程师的能力, 很多时候在`打杂`.

1. 提供底层库的便利安装包
2. 一键可以框架依赖的第三方包的部署工作


### 对于产品级应用

#### 产品的需求
1. 标准化
2. 稳定
3. 有专人support

可以根据公司的具体的业务来做需求.

### 公司内部如何处理

谷歌鼓励研究人员自己搞研究, 在自己的机器上随便折腾, 可以使用任何框架, 绝无限制. 针对具体的问题采用具体的工具.

但是如果调研阶段结束, 可是模型的训练和部署阶段. 就需要使用谷歌内部的工具, 比如 dist-belief, 比如tensorflow.

`兼顾工业级应用和AI前沿技术`, 同时tensorflow可以不断的从其他工中吸收经验教训不断的发展进步.

`这是一条螺旋上升的道路, 持续的正反馈`.

