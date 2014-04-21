
# Family Tree Builder 中文语言包

----

> 注：因为 v4.0 已经流露出太多的流氓气质，本语言包将可能不再更新。
> 不过 v3.0 同样可以用在 v4.0 中，大部分常用功能都已正常汉化，少量新增功能
> （一般很少用）可能会显示成为“TODO”。你也可以自己手动汉化，
> 欢迎你提交分享自己的语言包文件。

这些流氓气质包括：

* 安装文件实质上只是一个下载器，安装过程中需要联机下载真正的安装文件
* 安装过程中，无法取消安装针对IE和Firefox的插件，其甚至修改IE和FF浏览器的默认页和默认搜索引擎
* 运行前需要登录到服务器，甚至默认选中上传族谱资料到服务器不过就软件本身来说，还是相当不错的。

![logo](http://a.myheritageonline.com/FP/Assets/Images/Header/MyHeritageLogoBig.gif)

## 简介

族谱软件Family Tree Builder( [myheritage.com](http://www.myheritage.com) )
虽有中文站( [myheritage.cn](http://www.myheritage.cn) )，但是软件本身没有中文化，
基于需要和个人兴趣，将自己随手汉化部分的文件托管与此，抛砖引玉。

## 汉化原理

* 备份软件安装目录下，Lang子目录中的English.lang（也可以是其他国家的语言文件）。
* English.lang其实属于一种属性文件（properties），将每一行的第二部分翻译成中文
  （或合适的文本）即可。
* 备份安装目录下，Res子目录中的English.bmp图片。
* 制作一张32×28（v2.0）或155×28（v3.0）像素，bmp 格式的中国国旗图片，
  命名为English.bmp，放到Res（v2.0）或Res/Flag（v3.0）目录。
* 启动程序，菜单“工具(Tools)”-“选项(Options)”，
  * `名字(Names)`-`Display people’s names`设置为`Last First (Armstong John)`，
    即让姓氏(Last Name)放在名字(First Name)之前，符合中文习惯。
  * `日期(Dates)`，`Day/Month/Year format`设置为`%y%-%m%-%d%`，
    `Month/Year format`设置为`%y%-%m%`。可以根据自己的习惯设置，
    其中%m%是使用英文短格式，如Mon，在语言资源文件中改为数字即可。


## 翻译注意事项

部分文本不可以翻译为中文，如日期选择按钮类的小型按钮，提示文本为中文时，显示乱码。
另外程序本身左侧的列表(List)的姓名列和家庭树(Tree)的部分，使用中文也显示乱码
（好像所有List View都不支持中文）。


## 安装方法

### 针对 v3.0

* 下载 [v3.0语言包](http://code.google.com/p/familytreebuildercn/downloads/detail?name=Family.Tree.Builder.Lang.3.0.zip&can=2&q=#makechanges)
* 备份 English.lang 文件（如果你不想覆盖英语语言包，可以改为其他已存在的语言包文件，
  例如如 Hebrew.lang）
* 解压至软件安装目录下的Lang目录，覆盖原文件即可

### 针对 v2.0

* 下载 [http://code.google.com/p/familytreebuildercn/downloads/detail?name=MyHeritage.rar&can=2&q=#makechanges v2.0语言包]
* 备份 English.lang 文件（如果你不想覆盖英语语言包，可以改为其他已存在的语言包文件，
  例如如 Hebrew.lang）
* 解压到安装目录，覆盖原文件即可


p.s. 这个汉化语言文件现有两个版本，分别是基于Family Tree Builder 2.0和3.0的
英文语言资源文件翻译而成。这里提供下载的文件，只翻译了常用的部分。
