# 特殊元素介绍

> “特色送雪球”   ———— *`l吟游诗人I`*

这里呈现的是服务器在原版生存的基础上增加的特色元素  
玩家可以在这里进行查询，了解玩法

* * *

## 雪球菜单

丢出雪球，即可在经验条上方看见雪球菜单，  
注意，不要抬头或低头扔出  

雪球菜单目前有以下功能：

* 城镇传送 - 选择目标点进行传送
* 自刎 - 自杀，快速上床
* 玩家互传 - 玩家之间进行传送，详情见[玩家互传](world/MS1/characteristic.md#玩家互传)
* 生存模式 - 当因为某些特殊原因离开保护区域后模式没有进行变化时的应急方案，可以切换为生存模式

低头确认，抬头取消，扔出雪球进行选择

* * *

## 玩家互传

[雪球菜单](world/MS1/characteristic.md#雪球菜单)功能，实现玩家远距离传送

使用方法：   
雪球菜单选择玩家互传后  
首栏显示为刷新  
其余五栏则为随机五名玩家  
选中低头即可发出传送请求   
被选中玩家则通过低头抬头来实现同意与拒绝  
当一名玩家发出请求时，另一名玩家有30秒的时间进行回应，如没有回应，则为了避免恶意占线而重置  
如随机的五栏内不存在想要传送的玩家，第一栏刷新即可  
传送菜单是所有过审玩家都可以发出请求，未过审玩家只能接受请求

* * *

## 魔力结构

玩家可以按照一定形式摆放某些方块  
以搭建出特定的结构  
而这些结构将会有各自的用途  

详见[结构总览](world/MS1/structure.md)

* * *

## 副手自带“无限”

增加此项的目的是为了限制技能点拿去点js科技的人的手段  
不过也就适当算为福利了吧

> 创意来源：*echo服务器组*

* * *

## 高空窒息

> “当人在高空的时候，他们会发现一件事情：这里，没有氧气”   —— *`FoodAssassin`*

当玩家在主世界的高度在不断升高时，从150格开始，会逐渐给予玩家负面效果，越高越恶劣，  
当玩家进入130格后，会有高度预警

> “至于地狱与末地？喂，既然已经到了无法用科学解释的地方了，为啥还要找真实感呢？（笑）”   —— *`FoodAssassin`*

地狱与末地并不会存在高空窒息，请放心

* * *

## 随机传送

玩家可利用『晚阳城』提供的功能进行随机传送，传送点在公告栏上，  
传送范围为：
* 过审玩家
  * 以（0,*,0）为中心，5000×5000的正方形进行随机传送
* 未过审玩家
  * 以（0,*,0）为中心，2000×2000的正方形进行随机传送

* * *

## 可活动范围

因为各种原因，下列区域为玩家的可活动范围：
* 主世界
  * （-30,0,-30）至（30,30,30）为禁止区域
* 地狱
  * （3,8,0）至（-1,3,5）为禁止区域
  * 顶部基岩上方为禁止区域
* 末地
  * 以（15,181,-15）为中心，半径50格内为禁止区域

* * *

## 『末地攻略战』

开放于末地的副本，开启方式为复活末影龙  
副本末影龙已被强化  
* 强化内容
  * 上下浮动
    * 末影龙会选择上下两个位置进行栖息
  * 晴天霹雳
    * ~全员被迫带上避雷针~
    * 末影龙在所有水晶被破坏时，在上方栖息时，会释放闪电进行攻击
  * 水晶掌控
    * 末影龙会引爆玩家背包内的末影水晶
  * 螨群
    * 在所有末影水晶被破坏时，末影龙会试图在全员脚下生成部分末影螨，生成时伴有缓慢效果

* * *

