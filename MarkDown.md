# MarkDown
三个问题集
# Github 问题集（1）
## 1.github是什么    
1 是一个面向开源及私有软件项目的托管平台
2 it社交平台
1 写小说
## 2.git是什么
是唯一的版本库格式
## 3.github的5个好处
具有基本的web管理界面 提供了订阅 讨论组 文本渲染 在线文本编辑器 协作图谱 （报表） 代码片段分享等功能 可以参与
## 4.github的优势
Github对git版本库提供了完整的写协议支持，支持HTTP智能协议Git-daemon。SSH协议
具有基本的web管理界面 提供了订阅 讨论组 文本渲染 在线文本编辑器 协作图谱 （报表） 代码片段分享等功能、
将社交网络引入项目托管平台是Github的创举，用户可以关注项目关注其他用户的进而了解项目和开发者动态
## 5.通过github年度报告让你记忆最深刻的信息有哪些
一些高级语言的使用率以及一些问题的回复
## 6.github上有可以个人账号 还可以有（）账号
企业 Github Pages
## 7.github上面的两个组成要素是什么
仓库（项目）或 个人主页
## 8.github上两个重要页面
个人主页 项目页面
## 9.主页菜单都包含什么
个人资料 概述  库 
## 10.仓库的心跳线代表什么
仓库的活跃程度
## 11.star的作用是？
持续关注别人项目更新
## 12.fork的作用是？
拷贝他人的项目到自己账号下 ，参与其项目
## 13.watch的作用是？
设置接收邮件提醒的
## 14.搜索结果分别有哪些类别
用户 仓库 代码 
## 15.你在github上挖到什么宝
# Github 问题集（2）
## 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
创建新的仓库 引入一个仓库   发起新的组织
## 2.如何能将仓库中的html文件直接解析成页面？
setting github pages master branch
## 3.如何删除仓库
setting  delete this respository按钮
## 4.Bash是什么操作系统的命令
Linux
## 5.Pwd是什么命令
显示当前目录
## 6.Cd是什么命令
改变目录
## 7.Echo是什么命令
打印 输出
## 8.配置git用户名的命令
git config --global user.name "Your Name Comes Here" 
## 9.配置邮箱的命令
git config --global user.email you@yourdomain.example.com 
## 10.命令行换行方式
\
## 11.命令行终结方式
ctrl+C
## 12.使用命令行比GUI方式有何优势
 GUI 可视化的窗口
两种都可以 
## 13.提交到本地仓库时为什么有暂存区
当对工作区修改（或新增）的文件执行 "git add" 命令时，暂存区的目录树被更新，同时工作区修改（或新增）的文件内容被写入到对象库中的一个新的对象中，而该对象的ID 被记录在暂存区的文件索引中。
当执行提交操作（git commit）时，暂存区的目录树写到版本库（对象库）中，master 分支会做相应的更新。即 master 指向的目录树就是提交时暂存区的目录树。
当执行 "git reset HEAD" 命令时，暂存区的目录树会被重写，被 master 分支指向的目录树所替换，但是工作区不受影响。
当执行 "git rm --cached <file>" 命令时，会直接从暂存区删除文件，工作区则不做出改变。
当执行 "git checkout ." 或者 "git checkout -- <file>" 命令时，会用暂存区全部或指定的文件替换工作区的文件。这个操作很危险，会清除工作区中未添加到暂存区的改动。
当执行 "git checkout HEAD ." 或者 "git checkout HEAD <file>" 命令时，会用 HEAD 指向的 master 分支中的全部或者部分文件替换暂存区和以及工作区中的文件。这个命令也是极具危险性的，因为不但会清除工作区中未提交的改动，也会清除暂存区中未提交的改 动。
14.新建代码仓库的命令  git init
 mkdir   code;
 cd code;
 git init   初始化一个新的空仓库
15.git clone [url] 这个命令的作用是 克隆仓库 
 在使用git来进行版本控制时，为了得一个项目的拷贝(copy),我们需要知道这个项目仓库
 的地址(Git URL). Git能在许多协议下使用，所以Git URL可能以ssh://, http(s)://, git://,
 或是只是以一个用户名（git 会认为这是一个ssh 地址）为前辍.
16.添加指定文件到暂存区的命令
 git add [file1] [file2]
17.删除工作区文件，并且将这次删除放入暂存区的命令
 git rm [file1] [file2]
18.改名文件，并且将这个改名文件放入暂存区的命令
 git mv [file-origin] [file-renamed]
19.提交暂存区到仓库的命令
 git commit -m [message]
20.直接从工作区提交到仓库的命令
git commit -a -m [message]
21.显示变更信息的命令
git statys
22.查看历史信息的命令
git 
23.Commit的意义是
提交信息
24.Pull的意义是
将远程的仓库放到本地并进行合并
25.Push的意义是
将本地的仓库放到远程并进行合并
