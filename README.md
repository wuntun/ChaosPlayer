# ChaosPlayer

成员：@WangXiangUSTC @meathill @tsthght @Startalkers

## 项目介绍

将 Chaos Mesh 和游戏结合起来，提高它的易用性和趣味性。

## 背景&动机

目前使用 Chaos Mesh Dashboard 的过程中存在以下问题：
- 创建 workflow（编排）非常复杂，不太直观，而且配置后不容易对故障的拓扑结构进行调整
- 混沌实验的过程略显枯燥

![image](https://user-images.githubusercontent.com/5793595/148079094-8f2a5f88-3653-48bb-a380-e6d968775548.png)

我们希望通过该项目，探索将 Chaos Mesh 与游戏结合起来，提高它的易用性和趣味性。


## 项目设计

设计一个游戏场景，与 Chaos Mesh 结合起来。例如：

1. 赛车游戏

      被测应用为玩家控制的汽车，路上的路障/坑为故障，通过编辑道路来创建和组合各种故障。
![image](https://user-images.githubusercontent.com/5793595/148080848-aab9a11b-6479-45c4-9abf-2979427d9f62.png)

2. 外星侵略者

       被测的 deployment/service 为外星飞船主舰，各个 Pod 为战机。玩家对 Pod 进行攻击（注入故障）。
![image](https://user-images.githubusercontent.com/5793595/148081072-5737cfe0-eeac-45a1-b7f6-707cb6813ce7.png)


目前游戏场景还在选择和设计中。


## 参考项目

https://github.com/lucky-sideburn/KubeInvaders
https://github.com/storax/kubedoom
