#DrrrBotHelper（by こおり）

##功能简介
###点歌
+ 支持网易云音乐、酷狗音乐
+ 支持搜索与点播单曲、**专辑和歌单**
+ 支持随机播放、顺序播放
+ 支持切歌、插歌  
ps:推荐使用酷狗音乐，网易云音乐的付费及版权限制歌曲无法播放，Bot会自动跳过。  
ps2:非中国大陆地区可能无法听到网易云音乐的歌曲。  
ps3:Bot可视为一个公用的音乐播放器，点歌切歌时请自重和尊重他人。

###聊天
觉得跟Bot聊天比跟活人聊天有意思？  
自己选一个吧，慢走不送：  
[图灵机器人](http://www.tuling123.com/plugin/proexp.html)
[微软小冰](http://www.msxiaoice.com/)
[simsimi（小黄鸡）](http://www.simsimi.com/)

###主持游戏（狼人）
等待DRRRKIT完成。

##指令示例
+ -酷狗 Diver  

>在酷狗音乐中搜索单曲 Diver

+ -第二个  

>从返回的搜索结果中点播第二个单曲或专辑或歌单

+ -第二个 置顶  

>从返回的搜索结果中点播第二个单曲或专辑或歌单，并置顶

+ -上一页  

>在返回的搜索结果中翻页

+ -酷狗 Diver 第一个 置顶  

>在酷狗音乐中搜索单曲 Diver，并点播搜索结果中的第二个，并置顶到播放列表中  
  
+ -酷狗歌单 动漫  

>在酷狗音乐中搜索歌单 动漫  

+ -网易专辑 冰菓  

>在网易云音乐中搜索专辑 冰菓  

+ -切歌  

>立即播放下一首歌。

+ -暂停  

>暂停播放列表。

+ -随机播放  

>更改播放模式为随机播放。  


##指令帮助
指令具有严格的格式要求，所有指令的格式均为：

>-指令 参数1 参数2...

有的指令没有参数。  
发送指令需要@或者私聊Bot，**私聊时请勿@。**  
**指令名前的-，指令与参数、参数与参数之间的空格，均不可省略。  
所有指令均支持繁体中文，均不支持英文或阿拉伯数字。**

以下为可用指令：  
+ 网易  
**参数1**：必须参数，要搜索的单曲的关键字  
**参数2**：可选参数，要点播的单曲的序号（第一个/第二个/第三个/第四个/第五个）  
**参数3**：可选参数，是否置顶。仅当存在参数2时有效。  

>在网易云音乐中按关键字搜索单曲；如果存在参数2，将同时点播指定曲目，也就是搜索和点播只需一条指令。

+ 网易专辑  

>在网易云音乐中搜索专辑。  
参数与指令‘网易’完全相同。

+ 网易歌单  

>在网易云音乐中搜索歌单。  
参数与指令‘网易’完全相同。

+ 酷狗  

>在酷狗音乐中搜索单曲。  
参数与指令‘网易’完全相同。

+ 酷狗专辑  
在酷狗音乐中搜索专辑。  
参数与指令‘网易’完全相同。
+ 酷狗歌单  
在酷狗音乐中搜索歌单。  
参数与指令‘网易’完全相同。
+ 第一个/第二个/第三个/第四个/第五个  
**参数1**：可选参数，是否置顶  
在返回的搜索结果中点播第一/二/三/四/五个单曲或专辑或歌单。
+ 上一页  
在返回的搜索结果中翻到上一页。
+ 下一页  
在返回的搜索结果中翻到下一页。
+ 切歌  
立即播放下一首。
+ 清空列表  
清空播放列表中的所有曲目。
+ 随机播放  
更改播放模式为随机播放（shuffle）。
+ 顺序播放  
更改播放模式为顺序播放（order）。
+ 暂停  
暂停播放列表
+ 恢复  
从暂停中恢复播放列表
+ 列表信息  
查询播放列表中的剩余曲目数，当前播放模式及下一首。
+ 离开  
让Bot离开当前房间，Bot将会自己选择另一个房间重新加入。  
ps：只有当前房间的房主和聊天室管理员可以执行此指令。
+ 进入  
**参数1**：必须参数，房间名关键字  
让Bot离开当前房间并进入房名中含有指定关键字的房间。  
ps：只有当前房间的房主和聊天室管理员可以执行此指令。  
ps2：如果有多个房间含有指定关键字，或者试图进入房间时出错，Bot可能会进入别的房间。
+ 推荐  
让Bot推荐歌曲，歌曲来自网易云音乐的每日歌曲推荐（每天6点更新一次）。  
注意，Bot会自动将推荐的歌曲置顶。
+ 随便听听  
让Bot随机选择一些歌曲播放，歌曲来自酷狗音乐的几大排行榜（大概每周更新一次）。   
注意，Bot会自动将随机选择的歌曲置顶。
