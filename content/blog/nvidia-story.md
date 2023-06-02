---
date: 2023-06-02 17:55:07
url: 
aliases: 
tags: 
  - 文摘
title: 黄仁勋的 Nvidia 故事
edited date: 2023-06-02 17:58:48
---

黄仁勋的 Nvidia 故事
--------------

黄仁勋大概是硅谷最有影响力的华人。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052809.webp)

1993年，他跟两个朋友一起创办了芯片设计公司 Nvidia（中文名"英伟达"）。当时是小公司，可现在是美国第五大科技公司（仅次于苹果、微软、谷歌和亚马逊）。

十年前，如果你买了 Nvidia 的股票，现在都要笑死了，因为它上涨了[105倍](https://www.chinaz.com/2023/0527/1528509.shtml)！最近十年美国涨幅第一名的股票就是它。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052812.webp)

上周，黄仁勋突然出现在台湾，被拍到在饶河街夜市买小吃。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052810.webp)

后来大家才知道，他要参加5月27日的台大毕业典礼，他是今年的演讲嘉宾。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052811.webp)

我推荐这个演讲，网上有[全文](https://www.businessweekly.com.tw/focus/blog/3012429)。原文是英语，已经译成中文。

他只讲了20分钟，但是解开了我心中一直的疑问：Nvidia 是怎么发家的。下面就是我根据这个演讲，整理出来的 Nvidia 的故事。

黄仁勋说，**为什么要创立 Nvidia？因为我们看好加速计算。** 

人类对计算速度的要求一定会越来越高，CPU 只能做通用计算，加速计算需要定制的专用硬件，所以我们的创业目标就是加速计算的硬件。

市场需求量最大的加速计算硬件，就是游戏的图形芯片（GPU），所以我们选择游戏显卡作为创业产品。我们只做芯片设计，生产全部外包。

1994年，我们的第一个客户是日本游戏公司 SEGA，我们为它的游戏主机设计显卡。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052813.webp)

（图片说明：Nvidia 的第一个产品，SEGA 游戏机的 [NV1 显卡](https://segaretro.org/NV1)。）

但是第二年，微软发布了 Windows 平台的图形接口 Direct3D。我们一下子就慌了，因为它跟我们的设计是冲突的。

我们最终选择中止 SEGA 的合约，**改为 Windows 平台开发 GPU**。这是一步险棋，因为 SEGA 是我们唯一的客户，却被我们踢走了。我们的资金只能支持6个月，如果这点时间里面，拿不出新产品，我们就只有倒闭了。

幸运的是，快要没钱的时候，我们设计出了 Riva 128，这块芯片取得了成功。到了1997年底，它的出货量超过100万张，我们就这样活了下来。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052905.webp)

我们为 Windows 平台设计显卡，一直干了10年。

虽然产品很受欢迎，但是有一个问题：**人们只用这些显卡打游戏，无法用于其他的加速计算。**  因为那时的 GPU 必须通过 Windows 的接口使用，受制于操作系统，用户无法直接操作 GPU，很难将其用于自己的用途。

为了扩展 GPU 的用途，**2007年我们推出了 CUDA 框架，让用户可以操作 GPU 底层接口**，定制化编程，满足自己的加速计算需求。GPU 从此可以用于科学运算、物理模拟等各方面。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052906.webp)

令人失望的是，市场需求始终不旺，而我们推进 CUDA 的成本非常高。那几年，我们的利润受到严重拖累，股价低迷。内部也出现分歧，有人提出放弃 CUDA。

谁能想到，命运的转折点突然出现了。**2014年，人们发现 CUDA 能够满足 AI 训练的大量计算**，它一下子就变得异常火爆。随着 AI 的快速发展，我们从此走上了康庄大道，股价一飞冲天。

除了 AI，我们也尝试把加速计算推广到其他新兴领域。

2007年 iPhone 诞生了，手机芯片成为了一个超级市场。我们开始考虑为安卓手机开发芯片。

但是，手机芯片是集成的，CPU、GPU、通信芯片（调制解调器）做在一起。**如果我们要做安卓芯片，就必须研发通信芯片。这跟我们的加速计算方向是不符合的。** 

我们不得不做出一个艰难的决定：放弃手机市场。为了弥补这个损失，**我们选择进军另一个更符合我们的市场：自动驾驶的车用芯片。**  自动驾驶的计算量非常大，市场也很广阔。

![](https://cdn.beekka.com/blogimg/asset/202305/bg2023052907.webp)

上面就是 Nvidia 的简史。回顾这段历史可以看到，只要你坚信自己的大方向是对的，不妨就坚持做下去，不要害怕遇到挫折，也不要被眼前利益诱惑，最终会看到回报，Nvidia 就是这样走过来的。

> 转载自：http://www.ruanyifeng.com/blog/2023/06/weekly-issue-257.html