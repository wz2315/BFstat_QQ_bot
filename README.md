# BFstat_QQ_bot
薯薯人的第一个机器人，请大家见谅！（部署方法在下面）
基本的功能已经完成，由于是第一个版本，所以相关的美化有所欠缺。
## 主要功能 （注意必须英文等号=）
1.查询战绩结果如下图所示：（支持bf1和bfv）用法（‘cx=’与‘cx5=’）。
![22b776426f993433089847391f6b774c](https://github.com/user-attachments/assets/f23c7f34-e673-439d-8df9-47349238f708)
2.战队信息查询（‘plat=’）：
![12ecd8f9b779b94860a9268b3b5434d4](https://github.com/user-attachments/assets/f87a73ed-0792-4456-bb8c-29930f46b5b5)

## TO DO LIST：
1.支持2042的战绩查询（不能使用gametools的api，需要使用BTR的api），需要简单配置下

2.添加查询结果背景图（random）背景已经找好了。
![image](https://github.com/user-attachments/assets/1032058b-c587-4fd1-a1e1-e50cde238574)

3.支持hacker识别，比如说BFVhacker的api。不过战地一的不知道怎么弄，我自己以前有一套标准的，可刷枪什么的都要排除，本来想着用gametools返回的枪械类型进行简单判断，但是有很大的问题，比如：刘将军被归类为半自动，还有独头弹和猎人的爆头率差异很大，还没有想好怎么办。

4.行动和交换

## NO PLAN TO DO：
1.管服相关内容，有些东西说不清的麻烦，我怕写出史山，

## 免责声明：
#### 注意图片中的BFEAC与BFBAN与本人无关。为民间BattleField反作弊组织，官网分别为bfeac.com和bfban.com，若被封禁请去官网寻求帮助！

## 以下为部署教程：
在这里只教学windows系统llonebot的方法，如您需要其他系统或其他机器人框架（如napcat，lagrange，go-cqhttp请自行寻找相关文档）

#### 注意，部分api并不一定公开的，有些api我并没有找到文档，而是直接使用F12网络监听获取的，我会在源码中去除F12获取到的内容，你也去F12一下就行

剩下的鸽着，发release的时候写
