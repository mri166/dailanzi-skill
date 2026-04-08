# 抽象带篮子语料库（v2 标签版）

生成时间：2026-04-08 17:58:04（Asia/Shanghai）

## 字段说明

- `style_labels`：句式标签（命令句/反差句/自嘲句/苦感口号/身份反讽/一般梗句）
- `scene_labels`：场景标签（评论区/直播口播/短视频切片/通用）
- `risk_score`：风险分 0-5（越高越需降级处理）
- `risk_reasons`：风险来源解释

## 数据规模

- 输入：`raw-corpus-curated.jsonl`
- 输出样本（去重后）：376 条
- 结构化文件：`raw-corpus-v2-labeled.jsonl`

## 风险分布

- `risk=0`：300 条
- `risk=1`：63 条
- `risk=2`：12 条
- `risk=3`：1 条
- `risk=4`：0 条
- `risk=5`：0 条

## 句式标签分布

- `一般梗句`：280
- `苦感口号`：57
- `身份反讽`：30
- `命令句`：7
- `反差句`：6
- `自嘲句`：1

## 场景标签分布

- `通用`：338
- `短视频切片`：25
- `直播口播`：14

## 低风险高可用样本（Top 200）

1. `吃饱喝足去xx`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子，吃饱喝足去xx](https://www.bilibili.com/video/BV1t44y1N7WS/)
2. `带篮子，吃饱喝足去xx`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子，吃饱喝足去xx](https://www.bilibili.com/video/BV1t44y1N7WS/)
3. `峰哥x带篮子带货`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[峰哥x带篮子带货](https://www.bilibili.com/video/BV1cJDNBkEuJ/)
4. `【带篮子】经典语录视频合集`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】经典语录视频合集](https://www.bilibili.com/video/BV1qu41197t8/)
5. `带篮子评价方大同`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价方大同](https://www.bilibili.com/video/BV1529yYZETo/)
6. `带篮子评价身高合集`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价身高合集](https://www.bilibili.com/video/BV1H54y127MR/)
7. `抽象带篮子经典视频合集`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象带篮子经典视频合集](https://www.bilibili.com/video/BV14h6MBvELf/)
8. `【带蓝子】大战反差老师`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[爆笑了！【带蓝子】大战反差老师！全程高能！](https://www.bilibili.com/video/BV1ySk7BcEKX/)
9. `爆笑了！【带蓝子】大战反差老师！全程高能！`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[爆笑了！【带蓝子】大战反差老师！全程高能！](https://www.bilibili.com/video/BV1ySk7BcEKX/)
10. `【带篮子】忻州往事之扛把之路 全新故事会 爆笑了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】忻州往事之扛把之路 全新故事会 爆笑了](https://www.bilibili.com/video/BV1jZSmBXETq/)
11. `带篮子合集`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子合集](https://www.bilibili.com/video/BV1q611YGEga/)
12. `给你们拷起来`
   - style_labels：`命令句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子：今晚去查房 查到？？给你们拷起来](https://www.bilibili.com/video/BV1CQ4y1M77e/)
13. `都给我拷起来`
   - style_labels：`命令句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【抽象带篮子】全网最高学历保安！都给我拷起来？](https://www.bilibili.com/video/BV1Xc411h7d1/)
14. `带篮子520`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子520](https://www.bilibili.com/video/BV19DERzrEtU/)
15. `带篮子经典视频`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子经典视频](https://www.bilibili.com/video/BV18ggHzHEYv/)
16. `带篮子连麦刀哥`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子连麦刀哥，分享漏牛子经历](https://www.bilibili.com/video/BV1dn4y1X7B2/)
17. `分享漏牛子经历`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子连麦刀哥，分享漏牛子经历](https://www.bilibili.com/video/BV1dn4y1X7B2/)
18. `带篮子经典战役`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子经典战役](https://www.bilibili.com/video/BV15Q4y1A7aH/)
19. `带篮子陈义12`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子陈义12.8 烧牌“秋老师”高手过招 招架不住](https://www.bilibili.com/video/BV16V411871H/)
20. `【带篮子日常】“E哥`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子日常】“E哥，我裤子被同学扒了丢人吗”1](https://www.bilibili.com/video/BV1Hp4y1B7KP/)
21. `狡猾的带篮子发现相对论`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[狡猾的带篮子发现相对论](https://www.bilibili.com/video/BV1XV411a741/)
22. `篮子三件套合集（8种）`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子三件套合集（8种）](https://www.bilibili.com/video/BV1Gr4y1x79r/)
23. `带篮子：今晚去查房 查到`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子：今晚去查房 查到？？给你们拷起来](https://www.bilibili.com/video/BV1CQ4y1M77e/)
24. `我裤子被同学扒了丢人吗”1`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子日常】“E哥，我裤子被同学扒了丢人吗”1](https://www.bilibili.com/video/BV1Hp4y1B7KP/)
25. `带篮子评价快手（全程高能）`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价快手（全程高能）](https://www.bilibili.com/video/BV17e411x7UF/)
26. `【带篮子】经典老番之热血高校`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】经典老番之热血高校](https://www.bilibili.com/video/BV1YK42187gd/)
27. `如何评价亡命天涯峰哥说你高调`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：["e哥，如何评价亡命天涯峰哥说你高调？"](https://www.bilibili.com/video/BV1ab411X7v2/)
28. `【抽象带篮子】全网最高学历保安`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【抽象带篮子】全网最高学历保安！都给我拷起来？](https://www.bilibili.com/video/BV1Xc411h7d1/)
29. `带篮子连麦刀哥，分享漏牛子经历`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子连麦刀哥，分享漏牛子经历](https://www.bilibili.com/video/BV1dn4y1X7B2/)
30. `e哥，如何评价亡命天涯峰哥说你高调？`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：["e哥，如何评价亡命天涯峰哥说你高调？"](https://www.bilibili.com/video/BV1ab411X7v2/)
31. `8 烧牌“秋老师”高手过招 招架不住`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子陈义12.8 烧牌“秋老师”高手过招 招架不住](https://www.bilibili.com/video/BV16V411871H/)
32. `泪洒直播间 带篮子好像真的与自己释怀了`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[“泪洒直播间 带篮子好像真的与自己释怀了”](https://www.bilibili.com/video/BV1LD42157Yi/)
33. `带篮子：今晚去查房 查到？？给你们拷起来`
   - style_labels：`命令句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子：今晚去查房 查到？？给你们拷起来](https://www.bilibili.com/video/BV1CQ4y1M77e/)
34. `［抽象带篮子］连麦秋老师 全程高能被封直播间`
   - style_labels：`一般梗句; scene_labels：直播口播、短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[［抽象带篮子］连麦秋老师 全程高能被封直播间](https://www.bilibili.com/video/BV1Tr4y1M7F4/)
35. `【抽象带篮子】全网最高学历保安！都给我拷起来？`
   - style_labels：`命令句、身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【抽象带篮子】全网最高学历保安！都给我拷起来？](https://www.bilibili.com/video/BV1Xc411h7d1/)
36. `【带篮子】首谈和灿复合的故事：“她就是我的白月光`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】首谈和灿复合的故事：“她就是我的白月光”](https://www.bilibili.com/video/BV1svudzuEcX/)
37. `【带篮子日常】“E哥，我裤子被同学扒了丢人吗”1`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子日常】“E哥，我裤子被同学扒了丢人吗”1](https://www.bilibili.com/video/BV1Hp4y1B7KP/)
38. `好久不见 抽象带篮子一首安静 送给大家 祝大家晚安`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[好久不见 抽象带篮子一首安静 送给大家 祝大家晚安](https://www.bilibili.com/video/BV1n441137d6/)
39. `带篮子陈义12.8 烧牌“秋老师”高手过招 招架不住`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子陈义12.8 烧牌“秋老师”高手过招 招架不住](https://www.bilibili.com/video/BV16V411871H/)
40. `早安追星人`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[早安打工人！早安追星人！](https://www.bilibili.com/video/BV1QT411q7rb/)
41. `好好珍惜吧`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价张雪峰老师逝世：“这个世界怎么了，好好珍惜吧”](https://www.bilibili.com/video/BV1mQQmBCEc1/)
42. `上班Ver`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[Playlist | 早安打工人 您的续命歌单已送达 | 40分钟Kpop通勤歌单 | 上班Ver.](https://www.bilibili.com/video/BV1L71yYuECj/)
43. `带篮子语录`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子语录](https://www.bilibili.com/video/BV1oJgveVETx/)
44. `挂了十几次`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“考了三年驾照，挂了十几次，终于拿到本”](https://www.bilibili.com/video/BV1eK411z7yt/)
45. `终于拿到本`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“考了三年驾照，挂了十几次，终于拿到本”](https://www.bilibili.com/video/BV1eK411z7yt/)
46. `当上厅长啦`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】"e,几天没见，当上厅长啦?"](https://www.bilibili.com/video/BV1sW4y14739/)
47. `现在几点咯`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】喂，啥点？现在几点咯？](https://www.bilibili.com/video/BV1Lt4y147pL/)
48. `各自努力吧`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，各自努力吧。](https://www.bilibili.com/video/BV1UQ4y1m7aL/)
49. `大专怎么了`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，大专生活真自在，大专怎么了](https://www.bilibili.com/video/BV1j64y1y7zY/)
50. `吃饱喝足去`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去...](https://www.bilibili.com/video/BV1Pp4y1b7zw/)
51. `大家早上好`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大家早上好，早安打工人](https://www.bilibili.com/video/BV1Ry4y127f3/)
52. `陈e：早安`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[陈e：早安，打工人](https://www.bilibili.com/video/BV1oK411u7N7/)
53. `竟然过审了`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[竟然过审了，快看别被人删了（吃饱喝足原视频无删减）_bilibili](https://www.bilibili.com/video/BV1yV411f7zj/)
54. `大专人大专魂`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，大专都是人上人](https://www.bilibili.com/video/BV1JxDQYyEdK/)
55. `有人夜里看海`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[有人相爱，有人夜里看海，有人七八个闹钟起不来。早安打工人! -- 《打工人语录》](https://www.bilibili.com/video/BV14Y411z7EU/)
56. `带篮子西海岸`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子西海岸](https://www.bilibili.com/video/BV1hwSdBAEHR/)
57. `最烂嘴的一集`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“怒喷嘴臭女，最烂嘴的一集”](https://www.bilibili.com/video/BV1YH4y1w7qp/)
58. `【带篮子】喂`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】喂，啥点？现在几点咯？](https://www.bilibili.com/video/BV1Lt4y147pL/)
59. `如何评价张译`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“e哥，如何评价张译？”](https://www.bilibili.com/video/BV1jL411F7WH/)
60. `【带篮子】E`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】E，嘎子杀过鬼子，你呢？](https://www.bilibili.com/video/BV1Y341117yr/)
61. `嘎子杀过鬼子`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】E，嘎子杀过鬼子，你呢？](https://www.bilibili.com/video/BV1Y341117yr/)
62. `把篮子整笑了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子看《热血忻州》，把篮子整笑了](https://www.bilibili.com/video/BV1Ph411a7s4/)
63. `【带篮子】4`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】4.11《自闭绅士》与同济研二女主播户外直播录像](https://www.bilibili.com/video/BV1Zv411j7EK/)
64. `场面一度尴尬`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[[第三期]抽象带篮子，邦尼表白篮子哥，场面一度尴尬，委婉被拒。](https://www.bilibili.com/video/BV1Uf4y117cs/)
65. `还搞啥专升本`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂大专都是人上人，还搞啥专升本，看完都想本升专了！](https://www.bilibili.com/video/BV1ZA411b74x/)
66. `带篮子名场面`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子名场面](https://www.bilibili.com/video/BV1oK4y1r7iH/)
67. `吃饱喝足去R`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去R.I.P](https://www.bilibili.com/video/BV1Ae411x7pb/)
68. `大专都是人上人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，大专都是人上人](https://www.bilibili.com/video/BV1JxDQYyEdK/)
69. `带蓝子吃饱喝足`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带蓝子吃饱喝足，去上课了](https://www.bilibili.com/video/BV14N411Z7Rb/)
70. `千金散尽还复来`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[“千金散尽还复来，吃饱喝足就去抬！”](https://www.bilibili.com/video/BV14b4y1f7VN/)
71. `吃饱喝足就去抬`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[“千金散尽还复来，吃饱喝足就去抬！”](https://www.bilibili.com/video/BV14b4y1f7VN/)
72. `带篮子叫你早起`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子叫你早起](https://www.bilibili.com/video/BV1uA411H7tg/)
73. `天生我材必有用`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【加字幕】打工人，打工魂。早安、午安、晚安、加油！打工人！天生我材必有用，打工快乐不会痛。](https://www.bilibili.com/video/BV1ya4y1L7xu/)
74. `吃饱喝足去上课`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去上课](https://www.bilibili.com/video/BV1g4411X7aK/)
75. `不管三七二十一`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[不管三七二十一，吃饱喝足去…[思考]](https://www.bilibili.com/video/BV13bmcBuEyp/)
76. `太TM能装逼了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象网红带篮子评价Psy.P：他就是个傻篮子，太TM能装逼了](https://www.bilibili.com/video/BV17w4m1k7iu/)
77. `最正能量的一集`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“小陈拷打初中生，最正能量的一集”](https://www.bilibili.com/video/BV1LZ421M79D/)
78. `【带篮子】e哥`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】e哥，穿杰克琼斯有排面嘛？](https://www.bilibili.com/video/BV1TT4y1s7YJ/)
79. `吃饱喝足去rp`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去rp](https://www.bilibili.com/video/BV1sa4y1d7ZQ/)
80. `吃饱喝足去逃避`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去逃避](https://www.bilibili.com/video/BV1DN4y1U74g/)
81. `细说日本剧情片`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】小陈侃片-细说日本剧情片](https://www.bilibili.com/video/BV11u411H7kA/)
82. `大专才是人上人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人，大专魂，大专才是人上人](https://www.bilibili.com/video/BV1MP411676D/)
83. `峰哥锐评带篮子`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[峰哥锐评带篮子](https://www.bilibili.com/video/BV1wg41147ik/)
84. `【带篮子】"e`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】"e,几天没见，当上厅长啦?"](https://www.bilibili.com/video/BV1sW4y14739/)
85. `《带篮子》“E`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[《带篮子》“E，能把你腾顿方便屋卖我不”](https://www.bilibili.com/video/BV1cd4y1d7vr/)
86. `篮 子 中 举`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮 子 中 举](https://www.bilibili.com/video/BV1kr4y137Gk/)
87. `【带篮子】“e`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“e，女朋友不是第一次怎么办？”](https://www.bilibili.com/video/BV1LF411x7Uj/)
88. `大专生活真自在`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，大专生活真自在，大专怎么了](https://www.bilibili.com/video/BV1j64y1y7zY/)
89. `带篮子又出名言`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子又出名言](https://www.bilibili.com/video/BV16v41157VD/)
90. `骗 过 上 帝`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[骗 过 上 帝](https://www.bilibili.com/video/BV1hb4y1f7A6/)
91. `你该起床上班了`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[你该起床上班了，早安打工人！](https://www.bilibili.com/video/BV1iK4y1A7kp/)
92. `大专人 大专魂`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人 大专魂](https://www.bilibili.com/video/BV1FV411B7bU/)
93. `带篮子社会语录`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子社会语录](https://www.bilibili.com/video/BV1Jv411s7ki/)
94. `早晚变成瞧不起`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子，打工人，打工魂，打工永远难称神！辞职了奥 开公司，发工资，早晚变成瞧不起！](https://www.bilibili.com/video/BV1bp4y1Y7YJ/)
95. `我们不是一路人`
   - style_labels：`反差句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子，5点还没起床的根本没把自己当回事，互删吧，我们不是一路人，早安打工人](https://www.bilibili.com/video/BV1tT4y1w7L3/)
96. `来自篮子的早安`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[来自篮子的早安。打工人！](https://www.bilibili.com/video/BV1ah411X7yH/)
97. `邦尼表白篮子哥`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[[第三期]抽象带篮子，邦尼表白篮子哥，场面一度尴尬，委婉被拒。](https://www.bilibili.com/video/BV1Uf4y117cs/)
98. `带篮子成功语录`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子成功语录](https://www.bilibili.com/video/BV1bK4y1s7SU/)
99. `大专人，大专魂`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人，大专魂](https://www.bilibili.com/video/BV1JQ4y1T7jJ/)
100. `大专也是人上人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人，大专魂，大专也是人上人！](https://www.bilibili.com/video/BV1VT4y1V7MW/)
101. `吃饱喝足去（）`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去（）](https://www.bilibili.com/video/BV1at4y127Nt/)
102. `吃饱喝足去……`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去……](https://www.bilibili.com/video/BV1VE411F7GB/)
103. `男人没有切尔西`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[男人没有切尔西，就像女人没有（ ）](https://www.bilibili.com/video/BV11E411L7Zg/)
104. `吃饱喝足 去考研`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足 去考研。](https://www.bilibili.com/video/BV1514y1K7oW/)
105. `感叹时间飞逝……`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子回顾拍三件套的历史，感叹时间飞逝……](https://www.bilibili.com/video/BV18B4y1B7Ra/)
106. `怎么正确穿三件套`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[怎么正确穿三件套，才能套住姑娘的心？](https://www.bilibili.com/video/BV19h411t7Le/)
107. `才能套住姑娘的心`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[怎么正确穿三件套，才能套住姑娘的心？](https://www.bilibili.com/video/BV19h411t7Le/)
108. `吃饱喝足，去逃避`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足，去逃避](https://www.bilibili.com/video/BV1PucczFEVe/)
109. `Playlist`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[Playlist | 早安打工人 您的续命歌单已送达 | 40分钟Kpop通勤歌单 | 上班Ver.](https://www.bilibili.com/video/BV1L71yYuECj/)
110. `吃饱喝足去（ ）`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去（ ）](https://www.bilibili.com/video/BV1Je8qegEUW/)
111. `【带篮子】“e哥`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“e哥，你现在怎么评价华晨宇？”](https://www.bilibili.com/video/BV1Ws4y127VH/)
112. `【带篮子】“小e`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“小e，你能接受女朋友的男闺蜜嘛”](https://www.bilibili.com/video/BV1Qm4y197uM/)
113. `吃饱喝足去...`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去...](https://www.bilibili.com/video/BV1Pp4y1b7zw/)
114. `早安，单身人！！`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[早安，单身人！！](https://www.bilibili.com/video/BV1uA411j7Ni/)
115. `辞职了奥 开公司`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子，打工人，打工魂，打工永远难称神！辞职了奥 开公司，发工资，早晚变成瞧不起！](https://www.bilibili.com/video/BV1bp4y1Y7YJ/)
116. `看完都想本升专了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂大专都是人上人，还搞啥专升本，看完都想本升专了！](https://www.bilibili.com/video/BV1ZA411b74x/)
117. `【带伤感】大专人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带伤感】大专人、大专魂、大专都是人上人！](https://www.bilibili.com/video/BV1sz411b7vM/)
118. `吃饱喝足原声大碟`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足原声大碟](https://www.bilibili.com/video/BV1ct4y1U7uJ/)
119. `【带篮子】吃饱喝足`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】吃饱喝足，去逃避](https://www.bilibili.com/video/BV1sy4y1c7oQ/)
120. `吃饱喝足 去考研。`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足 去考研。](https://www.bilibili.com/video/BV1514y1K7oW/)
121. `抽象带篮子金典语录`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象带篮子金典语录](https://www.bilibili.com/video/BV13b411G7vc/)
122. `【带篮子】最后一舞`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】最后一舞，顶级狠活！](https://www.bilibili.com/video/BV1AckVBEEqC/)
123. `穿杰克琼斯有排面嘛`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】e哥，穿杰克琼斯有排面嘛？](https://www.bilibili.com/video/BV1TT4y1s7YJ/)
124. `【带篮子】小陈侃片`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】小陈侃片-细说日本剧情片](https://www.bilibili.com/video/BV11u411H7kA/)
125. `【带篮子】美国往事`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】美国往事](https://www.bilibili.com/video/BV1Pd4y1B7S7/)
126. `带篮子｜经典名场面`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子｜经典名场面](https://www.bilibili.com/video/BV1mU4y1F71t/)
127. `舒服是留给有钱人的`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子，累就对了，舒服是留给有钱人的，早安打工人！](https://www.bilibili.com/video/BV1BZ4y157CM/)
128. `我tm直接吃饱喝足`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[我tm直接吃饱喝足](https://www.bilibili.com/video/BV1NK411L7Jd/)
129. `吃 饱 喝 足 去`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃 饱 喝 足 去](https://www.bilibili.com/video/BV1S741117TX/)
130. `就像女人没有（ ）`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[男人没有切尔西，就像女人没有（ ）](https://www.bilibili.com/video/BV11E411L7Zg/)
131. `吃饱喝足就原声大碟`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足就原声大碟](https://www.bilibili.com/video/BV14E411J7yF/)
132. `吃饱喝足去%*&＃`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去%*&＃](https://www.bilibili.com/video/BV1R4411d7bR/)
133. `有人七八个闹钟起不来`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[有人相爱，有人夜里看海，有人七八个闹钟起不来。早安打工人! -- 《打工人语录》](https://www.bilibili.com/video/BV14Y411z7EU/)
134. `【带蓝子】复出后首播`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带蓝子】复出后首播！物是人非！2026年3月15日](https://www.bilibili.com/video/BV1LSwgz2E93/)
135. `2026年3月15日`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带蓝子】复出后首播！物是人非！2026年3月15日](https://www.bilibili.com/video/BV1LSwgz2E93/)
136. `吃饱喝足去…[思考]`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[不管三七二十一，吃饱喝足去…[思考]](https://www.bilibili.com/video/BV13bmcBuEyp/)
137. `赛博人物志（带篮子）`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[赛博人物志（带篮子）](https://www.bilibili.com/video/BV1Yhh3zSEU2/)
138. `比其他两个人领先太多`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价三小只易烊千玺新电影小小的我，比其他两个人领先太多！](https://www.bilibili.com/video/BV1Br6DYEEE9/)
139. `吃饱喝足一小时纯享版`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足一小时纯享版](https://www.bilibili.com/video/BV1ya4y1y7Va/)
140. `你现在怎么评价华晨宇`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“e哥，你现在怎么评价华晨宇？”](https://www.bilibili.com/video/BV1Ws4y127VH/)
141. `爱情不是我生活的全部`
   - style_labels：`反差句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[爱情不是我生活的全部，打工才是。早安，打工人！](https://www.bilibili.com/video/BV1iG4y127a4/)
142. `开启元气满满的一天吧`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[早安，打工人，开启元气满满的一天吧！](https://www.bilibili.com/video/BV1VG4y1B7tK/)
143. `【带篮子】评价权志龙`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价权志龙](https://www.bilibili.com/video/BV1yR4y1G71c/)
144. `带篮子看《热血忻州》`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子看《热血忻州》，把篮子整笑了](https://www.bilibili.com/video/BV1Ph411a7s4/)
145. `女人一直吊着我怎么办`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】E，女人一直吊着我怎么办](https://www.bilibili.com/video/BV1B54y1t7Hh/)
146. `带篮子评价1米5身高`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价1米5身高！](https://www.bilibili.com/video/BV1Qt4y1v7nj/)
147. `篮子：吃饱喝足去上课`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子：吃饱喝足去上课](https://www.bilibili.com/video/BV1Fa4y1e73y/)
148. `[第三期]抽象带篮子`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[[第三期]抽象带篮子，邦尼表白篮子哥，场面一度尴尬，委婉被拒。](https://www.bilibili.com/video/BV1Uf4y117cs/)
149. `吃饱喝足去R.I.P`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[吃饱喝足去R.I.P](https://www.bilibili.com/video/BV1Ae411x7pb/)
150. `自考本科现场也太卷了吧`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，自考本科现场也太卷了吧！](https://www.bilibili.com/video/BV1wL411e777/)
151. `带篮子吃饱喝足最全合集`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子吃饱喝足最全合集](https://www.bilibili.com/video/BV14Y411L7ra/)
152. `带蓝子经典语录（原版）`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带蓝子经典语录（原版）](https://www.bilibili.com/video/BV1jk6mBhEo4/)
153. `【带篮子】评价四字弟弟`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价四字弟弟，一针见血！？（补档）](https://www.bilibili.com/video/BV1DR4y1B7mA/)
154. `能把你腾顿方便屋卖我不`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[《带篮子》“E，能把你腾顿方便屋卖我不”](https://www.bilibili.com/video/BV1cd4y1d7vr/)
155. `女朋友不是第一次怎么办`
   - style_labels：`反差句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“e，女朋友不是第一次怎么办？”](https://www.bilibili.com/video/BV1LF411x7Uj/)
156. `【带篮子】北面能机洗么`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】北面能机洗么？](https://www.bilibili.com/video/BV1oT4y1P7bK/)
157. `【带篮子】评价推猫的人`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价推猫的人](https://www.bilibili.com/video/BV1Nz4y1D7KX/)
158. `带篮子评价1米5身高！`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价1米5身高！](https://www.bilibili.com/video/BV1Qt4y1v7nj/)
159. `抽象带篮子（几乎原版)`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象带篮子（几乎原版)](https://www.bilibili.com/video/BV1EC4y1a7hR/)
160. `抽象带篮子要追口子姐了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象带篮子要追口子姐了？？！](https://www.bilibili.com/video/BV1DC4y1W7jM/)
161. `带篮子评价山西各个城市`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子评价山西各个城市](https://www.bilibili.com/video/BV1Mp4y1C7Wb/)
162. `篮子哥吃饱喝足原声大碟`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子哥吃饱喝足原声大碟](https://www.bilibili.com/video/BV1W7411b7dJ/)
163. `【带篮子】吃饱喝足最重要`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】吃饱喝足最重要](https://www.bilibili.com/video/BV16t421w7Ch/)
164. `带篮子回顾拍三件套的历史`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子回顾拍三件套的历史，感叹时间飞逝……](https://www.bilibili.com/video/BV18B4y1B7Ra/)
165. `老子直接一把开衫放在桌上`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子补档】山西太子爷吃饭需要AA制？老子直接一把开衫放在桌上！](https://www.bilibili.com/video/BV1q3411c75D/)
166. `带蓝子吃饱喝足，去上课了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带蓝子吃饱喝足，去上课了](https://www.bilibili.com/video/BV14N411Z7Rb/)
167. `直播间大秀English`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子直言没过四级是节目效果，直播间大秀English](https://www.bilibili.com/video/BV1vE411T7m9/)
168. `【抽象带篮子】评价东百人`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【抽象带篮子】评价东百人](https://www.bilibili.com/video/BV1u741147Ak/)
169. `【带篮子】吃饱喝足追妹妹`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】吃饱喝足追妹妹](https://www.bilibili.com/video/BV157411i79Z/)
170. `带篮子锐评《香香瑜伽裤》`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子锐评《香香瑜伽裤》](https://www.bilibili.com/video/BV1FYcCzCE1L/)
171. `40分钟Kpop通勤歌单`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[Playlist | 早安打工人 您的续命歌单已送达 | 40分钟Kpop通勤歌单 | 上班Ver.](https://www.bilibili.com/video/BV1L71yYuECj/)
172. `抽象网红带篮子评价Psy`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象网红带篮子评价Psy.P：他就是个傻篮子，太TM能装逼了](https://www.bilibili.com/video/BV17w4m1k7iu/)
173. `都给你们拷起来 啊米诺斯`
   - style_labels：`命令句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[都给你们拷起来 啊米诺斯](https://www.bilibili.com/video/BV1ys421w7qw/)
174. `带篮子初入狼人杀持续高能`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子初入狼人杀持续高能](https://www.bilibili.com/video/BV1Mu4y1v7Cx/)
175. `带篮子｜评价一下山西大同`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子｜评价一下山西大同](https://www.bilibili.com/video/BV1p8411M7jK/)
176. `【带篮子】“考了三年驾照`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“考了三年驾照，挂了十几次，终于拿到本”](https://www.bilibili.com/video/BV1eK411z7yt/)
177. `你能接受女朋友的男闺蜜嘛`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】“小e，你能接受女朋友的男闺蜜嘛”](https://www.bilibili.com/video/BV1Qm4y197uM/)
178. `带哲学家带篮子的经典语录`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[带哲学家带篮子的经典语录](https://www.bilibili.com/video/BV1Fb4y1R7Mf/)
179. `【带篮子】北面能机洗么？`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】北面能机洗么？](https://www.bilibili.com/video/BV1oT4y1P7bK/)
180. `【带篮子】陈义真实身高暴露`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】陈义真实身高暴露！](https://www.bilibili.com/video/BV1AD421s7e2/)
181. `【带篮子】吃饱喝足，去逃避`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】吃饱喝足，去逃避](https://www.bilibili.com/video/BV1sy4y1c7oQ/)
182. `竟然养胃了：“柏拉图这一块`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】讲述第一次和灿发生关系，竟然养胃了：“柏拉图这一块”](https://www.bilibili.com/video/BV1kVYWzqENS/)
183. `【带篮子】男的长得丑怎么办`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】男的长得丑怎么办？](https://www.bilibili.com/video/BV1bp421Q7Ce/)
184. `【带篮子】e哥评价拉夫劳伦`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】e哥评价拉夫劳伦](https://www.bilibili.com/video/BV1AC4y1R78e/)
185. `大专人大专魂，各自努力吧。`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，各自努力吧。](https://www.bilibili.com/video/BV1UQ4y1m7aL/)
186. `【带篮子】小陈评价舌钉女孩`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】小陈评价舌钉女孩](https://www.bilibili.com/video/BV1yf4y1v7G8/)
187. `大专人大专魂大专都是人上人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂大专都是人上人](https://www.bilibili.com/video/BV1AK4y1h7CD/)
188. `【带篮子】我将持续关注本群`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】我将持续关注本群](https://www.bilibili.com/video/BV1d441127hz/)
189. `篮子哥日常吃饱喝足带专生活`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子哥日常吃饱喝足带专生活](https://www.bilibili.com/video/BV1T4411w7PA/)
190. `大专人大专魂，大专都是人上人`
   - style_labels：`身份反讽; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[大专人大专魂，大专都是人上人](https://www.bilibili.com/video/BV1JxDQYyEdK/)
191. `【带篮子】陈义真实身高暴露！`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】陈义真实身高暴露！](https://www.bilibili.com/video/BV1AD421s7e2/)
192. `【带篮子】评价赵雷：“不让夸`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】评价赵雷：“不让夸？没必要吧？”](https://www.bilibili.com/video/BV1Ha411r7Ns/)
193. `十年寒窗苦读不如一句吃饱喝足`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[“十年寒窗苦读不如一句吃饱喝足”](https://www.bilibili.com/video/BV1B3411B7fq/)
194. `带篮子直言没过四级是节目效果`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子直言没过四级是节目效果，直播间大秀English](https://www.bilibili.com/video/BV1vE411T7m9/)
195. `【带篮子】男的长得丑怎么办？`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[【带篮子】男的长得丑怎么办？](https://www.bilibili.com/video/BV1bp421Q7Ce/)
196. `篮子吃饱喝足去r合集最全版本`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：0`
   - 风险原因：低风险
   - 来源：[篮子吃饱喝足去r合集最全版本](https://www.bilibili.com/video/BV1bV411B7NX/)
197. `（带篮子经典老番）篮子想爹了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[（带篮子经典老番）篮子想爹了](https://www.bilibili.com/video/BV15f4y1i7Wq/)
198. `公主集体向你行请安行公主礼拉`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[公主集体向你行请安行公主礼拉，早安打工人](https://www.bilibili.com/video/BV1wD4y1R7QT/)
199. `抽象带篮子要追口子姐了？？！`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：0`
   - 风险原因：低风险
   - 来源：[抽象带篮子要追口子姐了？？！](https://www.bilibili.com/video/BV1DC4y1W7jM/)
200. `带篮子叔叔不约12月5日直播`
   - style_labels：`一般梗句; scene_labels：直播口播; risk_score：0`
   - 风险原因：低风险
   - 来源：[带篮子叔叔不约12月5日直播](https://www.bilibili.com/video/BV1iJ411B7n6/)

## 中风险样本（Top 120）

1. `上司の诱惑`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：2`
   - 风险原因：成人暗示词
   - 来源：[全程高能！【带蓝子】大战寂寞人妻，上司の诱惑?!](https://www.bilibili.com/video/BV1j5F3zkEVg/)
2. `带篮子怒喷装逼女`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[带篮子怒喷装逼女](https://www.bilibili.com/video/BV1HH4y157R9/)
3. `【带蓝子】大战寂寞人妻`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：2`
   - 风险原因：成人暗示词
   - 来源：[全程高能！【带蓝子】大战寂寞人妻，上司の诱惑?!](https://www.bilibili.com/video/BV1j5F3zkEVg/)
4. `全程高能！【带蓝子】大战寂寞人妻，上司の诱惑?!`
   - style_labels：`一般梗句; scene_labels：短视频切片; risk_score：2`
   - 风险原因：成人暗示词
   - 来源：[全程高能！【带蓝子】大战寂寞人妻，上司の诱惑?!](https://www.bilibili.com/video/BV1j5F3zkEVg/)
5. `P：他就是个傻篮子`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[抽象网红带篮子评价Psy.P：他就是个傻篮子，太TM能装逼了](https://www.bilibili.com/video/BV17w4m1k7iu/)
6. `【带篮子】“怒喷嘴臭女`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[【带篮子】“怒喷嘴臭女，最烂嘴的一集”](https://www.bilibili.com/video/BV1YH4y1w7qp/)
7. `【带篮子】“怒喷嘴臭女，最烂嘴的一集`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[【带篮子】“怒喷嘴臭女，最烂嘴的一集”](https://www.bilibili.com/video/BV1YH4y1w7qp/)
8. `【带篮子】小陈你是什么傻b东西指点我`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[【带篮子】小陈你是什么傻b东西指点我？](https://www.bilibili.com/video/BV1ab4y1C7Pb/)
9. `【带篮子】小陈你是什么傻b东西指点我？`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[【带篮子】小陈你是什么傻b东西指点我？](https://www.bilibili.com/video/BV1ab4y1C7Pb/)
10. `因你倾城的美#狗史#炸裂#李老八#抽象带篮子#孙笑川`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：2`
   - 风险原因：攻击/辱骂词
   - 来源：[#郭德纲#抽象#史#因为他善#找史专家#我沉沦几回，因你倾城的美#狗史#炸裂#李老八#抽象带篮子#孙笑川](https://www.bilibili.com/video/BV1DvbaegEKv/)
11. `早安打工人公主也是打工人见到了老板的女王也的跟俩耗子行礼哎`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：2`
   - 风险原因：暴力语义词；句长偏长可读性风险
   - 来源：[早安打工人公主也是打工人见到了老板的女王也的跟俩耗子行礼哎](https://www.bilibili.com/video/BV17f4y1q774/)
12. `#早安打工人 #为千千万万的打工人加油 #忙碌的一天从微笑开始`
   - style_labels：`苦感口号; scene_labels：通用; risk_score：2`
   - 风险原因：暴力语义词；句长偏长可读性风险
   - 来源：[#早安打工人 #为千千万万的打工人加油 #忙碌的一天从微笑开始](https://www.bilibili.com/video/BV1ZK1JYzExi/)

## 高风险样本（Top 80）

1. `抽象网红带篮子评价Psy.P：他就是个傻篮子，太TM能装逼了`
   - style_labels：`一般梗句; scene_labels：通用; risk_score：3`
   - 风险原因：攻击/辱骂词；句长偏长可读性风险
   - 来源：[抽象网红带篮子评价Psy.P：他就是个傻篮子，太TM能装逼了](https://www.bilibili.com/video/BV17w4m1k7iu/)

## 使用规则（建议写入 Skill 执行层）

1. 默认仅采样 `risk<=1` 的语料。
2. 当用户明确要求更冲时，可放开到 `risk=2`，仍需给稳妥版。
3. `risk>=3` 仅做风格参考，不直接复用。
4. 品牌/商务语境强制 `risk<=1`。