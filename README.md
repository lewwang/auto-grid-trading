# Auto Grid Trading

### 背景
---
E大公开的网格策略越来越多的人跟车，由于大家设置的参数都相同，在卖出单委托的时候经常发生踩踏行为，迟迟不成交，或者有人抢跑。在此背景下，我们希望参考E大的网格交易的历史文章加上自己的理解，来实现一个自动网格交易策略生成器。


### 方法论
#### 网格1.0
1. 确定交易品种。
2. 列出网格表格。表格中包括交易价格、交易金额、交易日期。
3. 做压力测试。
4. 设置交易提醒。
5. 按照交易提醒进行交易。

### 路线图
---
- v0.1 版本预计实现功能如下：
  1. 输入品种代码能判断是否可以作为网格品种
  2. 如果可以确定其0网位置和网格大小



### 参考资料
---
1. [波段策略.网格之一：写在前面、体系以及策略](https://mp.weixin.qq.com/s/uxktt5ZpNo03FpQQX-aG7g)
2. [波段策略.网格之二：网格策略基础/1.0版](https://mp.weixin.qq.com/s/-czfqGvxkDcay_tSI1jv5g)
3. [波段策略.网格之三：网格策略进阶/2.0版](https://mp.weixin.qq.com/s/8pRKsjiQSZzrmH-uWCkRLQ)
