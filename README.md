# 根据番号快速搜索
在线安装 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/423350)

#### 功能
在网页标注所有番号,显示绿色  
鼠标划过可以激活搜索菜单  
点击番号可以直接复制  

#### 不足
1. 才疏学浅,知道的网站就几个,但有番号的网站千千万,,所以默认是对所有网站开启的 
2. 有时简介会被重复两次  
3. 当番号处于换行时,搜索菜单会显示在第二行 
4. 带链接番号会识别错误
5. 虽然使用的是谷歌翻译,但是翻译的很差。不懂日语,纯粹从翻译结果的可读性来看,相较于有道和百度, 它的表现是最烂的。
6. 关于番号:
只能识别 字母-数字 的番号,  
带日期的不识别 : Carib-020913-xxx,  
3d的不识别 : SM3D2DBD-xx,  
fc2不识别 : FC2-PPV-1234567,  
一本道的不识别 : 031721-xxx  
C0930番号不识别 : C0930-pla xxxx  
MuraMura番号不识别 : muramura 031721_xxx  
Jukujo-Club番号识别错误 : Jukujo-Club-xxxx  
Mesubutaメス豚 番号不识别 : mesubuta 131122_732_xx  
AV9898 AV-酒吧番号 : AV9898-xxxx  
G-Queen言番号 : G-Queen-xxx  
pacopacomama : pacopacomama-031721  
Gachinco : gachixxx-HD  
10musume 识别错误 : 10musume-发行日期_01 ，如10musume-010414_01  
1000giri : 1000giri+发行日期，如 1000giri-130906  
H0930  
H4610  
以上番号知识参考网址 https://www.unvone.com/55618.html

  
<!-- ## 以下为各版本的区别  
 > version: 0.1.1  
![动图](https://github.com/qxinGitHub/searchAV/blob/main/img/searchav0.1.1.gif)  

 > version: 0.2.0  增加相关简介
![动图](https://github.com/qxinGitHub/searchAV/blob/main/img/searchav0.2.0.gif)  

 > version: 0.3.0  增加标题翻译
![动图](https://github.com/qxinGitHub/searchAV/blob/main/img/searchav0.3.0.gif)   -->
  
## 更新历史
 > v0.7.9 2021-11-05
  - 改进: 排除显卡型号和帧率 例: xfx588, fps150
 > v0.7.8 2021-10-30
  - 改进: 排除手机镜头型号 例: imx586
 > v0.7.7 2021-09-26
  - 改进: 排除知乎
 > v0.7.6 2021-09-16
  - 修复: v2ex的网址不全
 > v0.7.5 2021-09-07
  - 改进: 排除一些购物网站。商品名很容易“字母+数字”
 > v0.7.4 2021-09-04
  - 修复: 将hp识别成番号的问题 例:hp-450
 > v0.7.3 2021-08-20
  - 修复: 网页延迟载入时,无法识别的问题
  - 修复: 将nc识别成番号的问题 例:NC-17
  - 修复: jellyfin无法识别的问题(理论上emby也可以,但是我没用emby,具体还不清楚)
  - 改进: 锁定字体颜色为黑色,增加圆角
 > v0.7.2 2021-08-18
  - 修复: 将AES识别成番号的问题 例:AES-256
 > v0.7.1 2021-08-11
  - 修复: javbus链接错误
  - 修复: 图片在页面底部看不到的问题(仅限于已浏览过的番号, 第一次重新加载图片的情况)
 > v0.7.0 2021-08-10
  - 修复: 经常被遮挡的问题
  - 修复: 当番号在页面底部会导致无法查看和操作的问题, 感谢[jywyf](https://greasyfork.org/zh-CN/scripts/423350/discussions/93317)老哥一直源源不断的建议
  - 改进: 当背景是图片时,看不清字的问题; 固定字的大小
  - 不知被哪位司机翻牌, 该脚本从一天十几的下载量猛增到一天一千多,愿称你为车神。特此处理几个影响使用体验的问题
 > v0.6.3 2021-07-24
  - 修复: btsow 的网址 调整为 btsow.com 
 > v0.6.2 2021-07-24
  - 修复: 将error识别成番号的问题 error522
 > v0.6.1 2021-07-12
  - 修复: 将cpu识别成番号的问题 cpu100%
 > v0.6.0 2021-06-30
  - 增加: 根据建议给演员增加了链接(半成品)
 > v0.5.6 2021-06-27
  - 修复: nas型号识别为番号的问题: ds-220
 > v0.5.5 2021-06-24
  - 改进: 排除抖音
  - 修复: xslist网站不识别的问题
 > v0.5.4 2021-06-23
  - 修复: 手表型号识别为番号的问题: gbx-100
 > v0.5.3 2021-06-18
  - 修复: 网卡识别为番号的问题: ax200
 > v0.5.2 2021-06-15
  - 修复: 相机名词识别成番号的问题: iso ILC
 > v0.5.1 2021-06-09
  - 修复: 英文日期识别成番号的问题 例:21-Jan-2021
 > v0.5.0 2021-06-04
  - 修复: 无法加载图片的问题。javbus的图片使用了防盗链,应该是网站正常升级,只是被误伤
 > v0.4.9 2021-06-01
  <!-- - 修复: 之前的版本更新导致依旧将covid等关键词识别为番号 -->
  - 修复: 关键词后的数字识别为番号的问题
 > v0.4.8 2021-05-31
  - 改进: 自动识别番号的时候,排除两位和四位数字,只识别三位数字
  - 改进: 默认排除一些网站,主要是用户名的问题,在这些网站上将不会生效: 52pojie.cn、appinn.net、v2ex.com、greasyfork.org、bilibili.com
 > v0.4.7 2021-05-25
  - 修复: 排除cat、hao
 > v0.4.6 2021-05-06
  - 修复: 排除shp
 > v0.4.5 2021-05-06
  - 修复: 继续排除一些特殊简写:dos|win|os|osx|ipad|lumia|miui|flyme|emui|note|snh|bej|gnz|ckg|akb|gp|gt|gts|gtx|covid|html|css|aptx|rx|mh|bmw|sn|au|cc|cctv|df|qbz|qsz|ak
 > v0.4.4 2021-05-03
  - 修复: 将 covid-19 识别成番号的问题
 > v0.4.3 2021-04-28
  - 修复: 重新打开页面,如果悬停的第一个番号是之前已浏览过的番号,不会重新获取信息的问题
 > v0.4.2 2021-04-28
  - 改进: 鼠标在番号停留2s,可以重新获取信息
 > v0.4.1 2021-04-28
  - 修复: 把一些网站排行榜也识别成番号的问题。 类似 top10 这种
 > v0.4.0 2021-04-28
  - 增加: 第一次打开番号的时候会加载封面, 后续不会(从0.4.2开始,鼠标在番号处停留2s以上,会重新加载图片)
  - 修复: 日期识别成番号的问题
 > v0.3.1 2021-04-28
  - 改进: 可以忽略番号之间的横杠。直接英文加数字也可以识别
  - 改进: 正则匹配中增加了[否定环视](https://www.zhihu.com/question/21015580/answer/16902391), 能排除一些中英文混用的用户名和网址。
  - 想法: 本想用精确的番号匹配,但是识别率更差。哪怕用[番号大全](https://github.com/imfht/fanhaodaquan)导入了不重复的5458个番号的英文, 依旧漏拉严重
 > v0.3.0 2021-03-19
  - 增加: 翻译标题功能 翻译函数取自于作者 Johnny Li 的脚本[ “网页翻译助手” version:1.2.9,](https://greasyfork.org/zh-CN/scripts/389784) 许可协议MIT
 > v0.2.0 2021-03-17
  - 增加: 增加相关简介,第一次浏览时从javbus获取, 再次浏览时从本地获取
 > v0.1.1 2021-03-17
  - 修复:显示位置错误
 > v0.1 2021-03-16
  - hello world 


图片仅为版本v0.1.x:  
![例图](https://github.com/qxinGitHub/searchAV/blob/main/img/searchav.png)