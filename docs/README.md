## 【用前须知】

> <font color= red><b>ACT并非官方允许的第三方软件。请不要使用该软件数据攻击其余玩家或挑衅官方。</b></font>
>
> 请将你的系统升级至win10 1903及以上
> 
> 请使用DX11运行游戏

---
## 【必需插件】

#### FFXIV解析插件

> <font color= red>此为ACT的核心插件，请不要擅自删除或移动该DLL文件。</font>
>
> * 正常情况下，玩家只需要做解析范围的相关设置。电脑比较好的玩家可以选择团队范围，稍差的则可以选择小队或者只监控自己。
> * 为确保运行稳定性，强烈建议使用进程注入模式。（Cafe ACT需手动开启，ACT.Diemoe默认自动开启）

---
## 【主流插件】

#### NGLD悬浮窗插件（OverlayPlugin悬浮窗插件）

> 提供基于网页的悬浮窗显示功能。
>
> 可基于此插件设置各种各样的悬浮窗。
>
> 注：无法在**全屏游戏**下显示悬浮窗，可切换至**窗口全屏**. ~~或将悬浮窗推流至局域网下其他设备~~

#### cactbot（凯科特爆特）

> [源仓库](https://github.com/quisquous/cactbot) 
>
> 是一个提供基于ngld悬浮窗插件的高级悬浮窗模板的插件。
>
> 由于翻译及眼拙等问题，拥有各式各样的别名，包括但不限于：凯科特爆破、仙人掌机器人、catbot...
>
> 自带各种风格的DPS悬浮窗美化、副本时间轴、Boss技能提醒、钓鱼计时等功能。
> 
> FF14客户端需以DX11启动方可使用此插件功能
> 
> **除DPS统计美化外，仙人掌下的悬浮窗口必须锁定。**
>
> <details><summary>拥有各种模块，并提供对应的功能：</summary>
>
> - DPS统计美化窗口
>* 狩猎雷达（Cactbot Radar）：可监控并播报自身周围S A B狩猎怪的具体位置及相对方位
> * 职业监控（Cactbot Jobs）：可监控自身职业量谱，重要buff，及长CD技能
>* 副本时间轴（Cactbot Timeline）：提供参考用副本时间轴
> * 副本触发提示（Cactbot Alerts）：提供参考用副本触发器
>* 犯错监控（Cactbot OopsyRaidy）：监控自身及队友的犯错，如副本死亡，食物效果过期，吃到不应该的伤害等（注：不包括操作手法）
> * 钓鱼计时器（Cactbot Fisher）：提供渔场数据，钓鱼计时等功能
>* 优雷卡监控（Cactbot Eureka）：可监控并提供**当前**优雷卡岛内NM刷新&天气，和**当前**博兹雅岛内SM、CE刷新&天气 
> 
></details>

#### 抹茶Matcha（排本fate通知）

> FFCafe出品，[源仓库](https://github.com/thewakingsands/matcha)
>
> <details><summary>提供的功能：</summary>
>
> 播报功能（可选tts播报或/和消息中心通知播报）
>
> - 过图播报：播报你即将到达哪张地图（可选只副本或全部地图）
> - 排本播报：排到副本后播报通知（随机副本无法透视）
> - 咬钩提示：钓鱼时播报咬钩（可选开启咬钩力度）
> - F.A.T.E播报：监控播报本地图刷新的已勾选的fate、NM(优雷卡)、SM(博兹雅)（可选名称、等级），可加载模板，默认模板为古武的9本小黄书
> - 博兹雅CE播报：监控播报本地图刷新的紧急遭遇战（Critical Engagement, CE）
>
> 悬浮窗功能（与NGLD悬浮窗插件联合使用）
>
> - 物价记录：记录当前市场交易板的物品最低价格（打开universalis集成后，可上传物价并查询其他服务器的物价）（可选hq过滤）
> - 配装比较：记录自身配装与目标配装（需打开一次目标装备界面）
> - 仙人微彩：刮刮乐计算器，根据期望计算，提供金碟刮刮乐建议
> - 宝物地图：快速查看已开启的藏宝图对应点位
>
> Webhook（需要一定的使用技巧）
>
> - [优雷卡自动史记](https://bbs.nga.cn/read.php?tid=28547954)
> - ...
>
> </details> 

#### 银山雀儿

>提供狩猎怪、F.A.T.E.跨服订阅通知
>
>可在设置里选择通知方式：`TTS` `toast通知`

#### Triggernometry（高级触发器）

> 高级轮椅
>
> 导入网上发布的后缀为.xml的触发器脚本，勾上复选框便可以启用相应功能。
>
> *在导入xml文件之前，请先确认是否为触发器脚本，无关的xml文件会导致报错。*
>
> 当你不使用某些触发提示时，请将其相应提示禁用。

#### 网络延迟显示

> noisyfox出品，[源仓库](https://github.com/Noisyfox/ACT.FFXIVPing)
>
> ~~显示你的网有多差~~
>
> 显示你的客户端到服务器的网络延迟，可用来判断滑步

#### TTS插件
> 用在线语音或系统语音合成引擎为其他插件的语音播报提供TTS功能
> - Fox语音合成 （noisyfox出品，[源仓库](https://github.com/Noisyfox/ACT.FoxTTS)）
> - TTS_CN （呆萌老师出品，暂不可用，等待修复）
> 
> 两者皆为简单易用的TTS插件，自带音量调节、语速调节、同音词发音替换等功能，多种语言、人声可选
> 
> 二选一使用即可

---
## 【其他插件】

#### triggernometry-pro

> 尼尼科技专业版增强触发插件，使用方法及插件介绍见[源仓库](https://github.com/pipirapira/triggernometry-pro)

#### 尼尼科技指挥插件

> 尼尼科技出品，使用方法及插件介绍见[源仓库](https://github.com/pipirapira/NiNiTechnology)

#### WebSocket（另一个悬浮窗插件）

> 完全可以被ngld替代的悬浮窗插件

#### Universalis

> 把物价上传到universalis的插件（呆萌act自带）

#### FishersInstinct（渔人的直感）

> 提供**咬钩计时**和**咬钩力度提醒**的插件（呆萌act自带）

#### FFXIVTranslate

> 还是noisyfox大佬出品，[源仓库](https://github.com/Noisyfox/ACT.FFXIVTranslate)
>
> 翻译最终幻想14国际服玩家聊天内容

---
## 【过时插件】

#### ACT时间轴



#### FZ时间轴

---
## 【不推荐的插件】

#### Hojoring系列
