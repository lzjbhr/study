# study
# 基础入门教程
## VS Code 必要熟练掌握两个基本技能：

1. 基本的熟练键盘盲打，这是基本代码输入能力，打字速度太慢，代码输入效率就会太低. 
* 打字速度提升可以通过金山打字通的每天坚持练习来提高。金山打字通下载地址
2. 对英语的有一定的掌握程度，不一定是要能达到英语4-6级能力，但起码对常见的编程方面的用到的单词要熟练掌握。
* 英语水平的提高需要时间的积累，并非短期可以提高，靠谱的学习方法在于每天坚持学习一点点，慢慢提升单词量（每天把自己遇到的不认识单纯抄下来，通过金山词霸等类似学习软件学习读音和词意）和语感。
***
# VS Code 简介
* VSCode是微软出的一款轻量级代码编辑器，免费而且功能强大，对JavaScript和NodeJS的支持非常好，自带很多功能，例如代码格式化，代码智能提示补全、Emmet插件等。
***
# 常用快捷键
### Ctrl + Shift + E 资源管理器
### Ctrl + Shift + F 搜索
### Ctrl + Shift + G 源代码管理器
### Ctrl + Shift + D 调试
### Ctrl + Shift + X 插件扩展
### F1 或 Ctrl+ Shift + p 打开命令面板
### Shift + Alt + F 代码格式化
### Ctrl+ F 查找
### Ctrl+ H 查找替换
### Ctrl+ N 新建文件
### Ctrl+ S 保存
### Alt + ↑ 或 Alt + ↓ 上下移动一行
### Shift + Alt + ↑ 或 Shift + Alt + ↓ 向上向下复制一行
***
# 常用的插件
* 中文语言包 Chinese (Simplified) Language Pack for Visual Studio Code 
* MarkDown预览增强 Markdown Preview Enhanced 
* 代码拼写检查器 Code Spell Checker 
* 浏览器预览增强 open in browser
* 检查英文语句中的中文符号 sneak mark 
* VS Code图标 vscode-icons 
* 格式化代码工具 beautify 
* HTML代码提示器 HTML Snippets 
* CSS样式提升器 HTML CSS Support 
* 各种皮肤主题 例如：One Dark Pro，Bimbo，Atom One Dark Theme 
***
# MarkDown
## MarkDown简介:
* Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。Markdown具有一系列衍生版本，用于扩展Markdown的功能(如表格、脚注、内嵌HTML等等)，这些功能原初的Markdown尚不具备，它们能让Markdown转换成更多的格式，例如LaTeX，Docbook。Markdown增强版中比较有名的有Markdown Extra、MultiMarkdown、 Maruku等。
***
# MarkDown基础语法
1. 粗体和斜体
#### 代码:
 - *斜体*或者_斜体_
 - **粗体**
 - ***加粗体***
 - ~~删除线~~
## 显示效果:
#### *这是一段斜体*
#### **这是一段粗体**
#### ***这是一段加粗体*** 
#### ~~这是一段删除线~~
***
2. 分级标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
***
3.引用
# 示例：
> 这是引用的内容
>> 这是引用的内容
>>>>>>这是引用的内容
***
4.分割线
* 三个或者三个以上的 - 或者 * 都可以
# 示例：
1. ---
2. ----
3. ***
4. *****
***
5.图片
# 语法：
* ![图片alt](图片地址 ''图片title'')

* 图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
***
6.超链接
# 语法：
* [超链接名](超链接地址 "超链接title")
* title可加可不加
# 示例：
[百度](http://baidu.com)
***
7. 列表
* 无序列表:
# 语法：
无序列表用 - + * 任何一种都可以(注意：- + * 跟内容之间都要有一个空格)
# 示例：
- 列表内容
+ 列表内容
* 列表内容
***
* 有序列表:
# 语法：
数字加点(注意：序号跟内容之间要有空格)
# 示例：
1. 列表内容
2. 列表内容
3. 列表内容
***
8. 表格
# 语法：
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容
# 示例：
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
*** 
9. 代码
# 语法：
* 单行代码：代码之间分别用一个反引号包起来
# 示例：
 `代码内容`
****
* 代码块：代码之间分别用三个反引号包起来，且两边的反引号单独占一行
# 示例：
(```)
 代码...
  代码...
  代码...
(```)
***
10.高亮
* 文本的高亮：
# 示例：
==文本的高亮==
***
# Git 简介
* Git是什么？Git 是 Linux 的创始人 Linus Torvalds 开源的一款分布式版本控制系统，以帮助开发者更好的对项目进行版本管理。每一个优秀的开发者在进行项目开发时都会第一时间给自己的项目加上 Git，以便能更好的追踪代码修改，进行版本回溯等操作。在多人协作的开发过程中，Git 更是必不可少的。
---
* git基本原理：
#### git版本管理工具，有3个工作区：
1. 工作目录 
2. 暂存区-----存放工作中更改的文件，避免项目代码丢失。 
3. 代码仓库-----当开发功能足够成为一个版本时，提交到仓库。其实就是将暂存区中代码复制一份存储到代码仓库中。 
---
#### git bash 命令行模式的基本特点：
* 简洁，迅速，高效
* git bash 基础命令
---
# GitHub 简介
* GitHub是什么？Github是一个基于it的代码托管平台，Github 由Chris Wanstrath, PJ Hyett 与Tom Preston-Werner三位开发者在2008年4月创办。这个星球上最流行的开源托管服务。目前已托管上百万的git项目，很多知名开源项目迁入GitHub，比如Ruby on Rails、jQuery、Ruby、Erlang/OTP；近年流行的开源库往往在GitHub首发，例如：BootStrap、Node.js、CoffeScript等。
---
## 注册GitHub账号步骤：
1. 首先我们登陆GitHub官网按照提示一步一步申请免费的账号，并且初始化仓库。 
2. 然后打开Git Bash 在命令行模式下通过cd 命令进入对应目录，在下图我进入的桌面(Desktop)目录 
3. 我们首先设置对应GitHub账号用户名和邮件 
* git config --global user.name 你自己的注册名
* git config --global user.email 你自己的注册邮件
4. 从远程GitHub仓库克隆刚刚初始化的项目
* git clone https://github.com/你自己的仓库地址

5. 进入克隆目录，然后当完成对文件的编辑保存好之后，我们先将修改后的文件添加到缓存区。 
* git add .
* git commit -m "代码提交的信息"
6. 将提交的结果推送代码到远程GitHub仓库(（在这个过程，系统会要求我们输入远程GitHub的账号和密码，按提示输入即可，由于还原系统的问题，我们就不使用SSH方式登录，但是在后面我们会在单独介绍SSH免密登录）。) 
* git push origin master



---
# 码云
#### 简介：禅码云是开源中国社区2013年推出的基于 Git 的完全免费的代码托管服务，这个服务是基于 Gitlab 开源软件所开发的，我们在 Gitlab 的基础上做了大量的改进和定制开发，目前已经成为国内最大的代码托管系统，致力于为国内开发者提供优质稳定的托管服务。
# 功能介绍
1. 登录禅道后找到 后台=>码云集成，在这个页面上有集成码云需要用到的所有信息
* Client ID、Client Secret 和 回调地址用于码云的OAuth登录以及API调用， 代号、密钥和请求入口用于码云向禅道验证任务有效性及同步信息。
2. 在码云的个人设置页面找到第三方应用，新建一个应用，在应用回调地址中填入上一步获取的回调地址，勾选应用需要用户赋予的权限，创建应用。
3. 创建应用后，打开应用可以看到码云生成的Client ID和Client Secret，把这两项的值填到第一步的禅道码云集成页面中，然后保存。
