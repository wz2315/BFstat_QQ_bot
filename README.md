# BFstat_QQ_bot
薯薯人的第一个机器人，请大家见谅！（部署方法在下面）
##### 有问题直接发issue我可以通过邮箱快速收到通知！
基本的功能已经完成，由于是第一个版本，所以相关的美化有所欠缺。
## 使用文档（帮助界面）：
##### 1.战绩查询：战地一（'cx='），战地五('cx5=')如下图演示（演示是我随机寻找的，由于这些信息都是公开的，所以应该不会存在纠纷）：
2024.10.04 优化了战绩查询，增加头像和异常武器，后续将增加bfv robot的机器人服名单情况
##### 2.战队成员查询('plat=')这个ID 你可以使用包括但不限于ghs机器人查询，主要是用来给vban战队留证据的，还能快速找到战队中的害虫
![da497a3caae5a6ad94e29576108fddb2](https://github.com/user-attachments/assets/e7afbf90-3801-407f-b14a-5edba202bdf5)

## TO DO LIST：
0.将下图中未在上文介绍的分支进行美观度的优化（最高优先级）

![image](https://github.com/user-attachments/assets/9bdaec7e-215f-4e26-98c4-0b4623ad979e)

1.支持2042的战绩查询（不能使用gametools的api，需要使用BTR的api），需要简单配置下（2024.10.04 经核实btr查询多次会遇验证码，ip池本人无能力使用，该功能已经暂停编写）

2.添加查询结果背景图（random）背景已经找好了。(2024.10.04 功能性优先，美观退后)
![image](https://github.com/user-attachments/assets/1032058b-c587-4fd1-a1e1-e50cde238574)

3.支持hacker识别，比如说BFVhacker的api。在战绩面板就能查询到了，done。

4.行动和交换(其他机器人功能强大，就不弄了)

## NO PLAN TO DO：
1.管服相关内容，有些东西说不清的麻烦，我怕写出史山，

## 免责声明：
#### 注意图片中的BFEAC与BFBAN与本人无关。为民间BattleField反作弊组织，官网分别为bfeac.com和bfban.com，若被封禁请去官网寻求帮助！

## 以下为部署教程：
在这里只教学windows系统llonebot的方法，如您需要其他系统或其他机器人框架（如napcat，lagrange，go-cqhttp请自行寻找相关文档）

#### 注意，部分api并不一定公开的，有些api我并没有找到文档，而是直接使用F12网络监听获取的，我会在源码中去除F12获取到的内容，你也去F12一下就行

剩下的鸽着，发release的时候写
