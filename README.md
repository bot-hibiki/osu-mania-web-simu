使用gameCanvas实现的仿osu!mania下落式音游模拟器，球皮风格，基本上由LLMs写成。

A mania rythmgame simulator parody from osu!mania, mainly credits to LLMs.


### [在线试玩点这里](https://bot-hibiki.github.io/osu-mania-web-simu/main.html])

### 原作者：[Bilibili@Tyarnl_679](https://space.bilibili.com/548916524/)

[基于网页浏览器的4k音游测试 - bilibili](https://www.bilibili.com/video/BV1KRysBZEn9/)

[你现在真的可以在网页游玩4k音游 - bilibili](https://www.bilibili.com/video/BV1KRysBZEn9/)

### 本仓库改进
#### 游戏页（main）
- 修改判定逻辑，按键时刻从帧生成相关时刻```gameTime```改为触发处理的时刻```performance.now()```虽然个人感觉改完之后更不好抓彩了，但这样也没有结算时误差分布条带了（
- 增加快捷键：快速重试，流速调整，偏移调整
- 修正COMBO的位置，使得无论是几位都居中显示
- 更改了轨道宽度&底色&轨道分隔线颜色、音符大小
- 修改fail与否的停止播放时机
- 部分汉化、调整界面，新增提示框

#### 结算页（result）
- 添加平均误差栏

### 仍有问题
部分谱面音符靠前，开始游戏即在屏幕中间。

### TODO
- 砖皮、钉皮
- 按轨道分类音符颜色（服务于多K）

### NOTDO
- SV
- 变BPM？

### LISENCE
群主（Tyarnl_679）说现在不太想管，你们想玩啥叫ai自己加。

