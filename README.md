#DrrrBotHelper（by こおり）

##功能简介
###点歌
+ 支持网易云音乐、酷狗音乐
+ 支持搜索与点播单曲、专辑和歌单
+ 支持随机播放、顺序播放
+ 支持切歌、插歌  
ps:有时无法播放，通常是因为歌曲已下架

###聊天
鉴于没有找到合适的开放聊天机器人API，暂不考虑。  
况且我们来聊天室也不是为了跟Bot聊天吧？

###主持游戏（狼人）
计划中...

###留言
给指定的某人留言。Bot会代你转达。  
计划中...

##指令示例
+ -网易 Diver  
在网易云音乐中搜索单曲 Diver
+ -第二个  
从返回的搜索结果中点播第二个单曲或专辑或歌单
+ -第二个 置顶  
从返回的搜索结果中点播第二个单曲或专辑或歌单，并置顶
+ -上一页  
在返回的搜索结果中翻页
+ -网易 Diver 第一个 置顶  
在网易云音乐中搜索单曲 Diver，并点播搜索结果中的第二个，并置顶到播放列表中
+ -网易歌单 动漫  
在网易云音乐中搜索歌单 动漫
+ -酷狗专辑 冰菓  
在酷狗音乐中搜索专辑 冰菓
+ -切歌  
立即播放下一首歌。
+ -暂停  
暂停播放列表。
+ -随机播放  
更改播放模式为随机播放。  

##指令帮助
指令具有严格的格式要求，所有指令的格式均为：

>-指令名 参数1 参数2...

有的指令没有参数。  
发送指令需要@或者私聊Bot，**私聊时请勿@。**  
**指令名前的-，指令与参数、参数与参数之间的空格，均不可省略。  
所有指令均支持繁体中文，均不支持英文或阿拉伯数字。**

以下为可用指令：  
+ 网易  
在网易云音乐中搜索单曲。  
**参数1**：必须参数，要搜索的单曲的关键字  
**参数2**：可选参数，要点播的单曲的序号（第一个/第二个/第三个/第四个/第五个）  
**参数3**：可选参数，是否置顶。仅当存在参数2时有效。
+ 网易专辑  
在网易云音乐中搜索专辑。  
参数与指令‘网易’完全相同。
+ 网易歌单  
在网易云音乐中搜索歌单。  
参数与指令‘网易’完全相同。
+ 酷狗  
在酷狗音乐中搜索单曲。  
参数与指令‘网易’完全相同。
+ 酷狗专辑  
在酷狗音乐中搜索专辑。  
参数与指令‘网易’完全相同。
+ 酷狗歌单  
在酷狗音乐中搜索歌单。  
参数与指令‘网易’完全相同。
+ 第一个/第二个/第三个/第四个/第五个  
**参数1** 可选参数，是否置顶  
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
