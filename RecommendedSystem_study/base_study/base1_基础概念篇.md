# 【关于 推荐系统】那些你不知道的事

> 笔者：杨夕
>
> 项目地址：https://github.com/km1994/nlp_paper_study
> 
> 个人介绍：大佬们好，我叫杨夕，该项目主要是本人在研读顶会论文和复现经典论文过程中，所见、所思、所想、所闻，可能存在一些理解错误，希望大佬们多多指正。

## 整体框架图

![](img/微信图片_20201018180302.png)

## 简介

1. What
  a. 用户：推荐系统是一种帮助用户快速发现有用信息的工具
  b. 公司：推荐系统是一种增加公司产品与用户接触,购买等行为概率的工具
2. Why
  a. 用户：在用户需求并不十分明确的情况下进行信息的过滤,与搜索系统相比,推荐系统更多的利用用户的各类历史信息猜测其可能喜欢的内容
  b. 公司：解决产品能够最大限度地吸引用户,留存用户,增长用户黏性,提高用户转化率,从而达到公司商目标连续增长的目的.
> **本质上是一种实现将用户-商品-公司之间利益最大化的手段.**
3. Who
  从上面的1和2可以看出用户与公司是需要推荐系统的主要对象，那么可以在1和2的基础上展开想想什么样子的人需要推荐系统，以及什么样的公司需要推荐系统。

## 常见评价指标

1. 用户满意度
2. 预测准确度
   1. 评分预测
   2. TopN推荐
3. 覆盖率
4. 多样性
5. 新颖性
6. AUC曲线
