# Git学习

git是版本控制工具，能够跟踪整个软件的开发过程，减轻开发人学的负担，节省时间，通知降低人为错误。

### **快捷键**

1. 放大缩小：CTRL+shift+滚轮
2. 字体放大缩小：CTRL+滚轮

### 常见操作

![](https://github.com/ibusteri7/TASKS/blob/eb4f09af4ea2982f75a21301ddc53eee52aa3de4/photo/2.png)

> 
>
> Git配置

查看所有配置：==`git config -l`==

查看系统：==git config --global --list==

查看当前用户：==git config --system --list==



### git基本理论（核心）

四个工作区域 

- 工作目录
- 暂存区
- 资源库
- 远程的git仓库

![](https://github.com/ibusteri7/TASKS/blob/eb4f09af4ea2982f75a21301ddc53eee52aa3de4/photo/1.png)



- workspace：工作区，平时存放项目代码的地方。
- index/stage：暂存区，用于零食存放你的改动，事实上只是一个文件，保存即将提交到文件列表信息。
- repository：仓库去，安全存放数据的位置，有提交到所有版本的数据。
- remote：远程仓库，托管代码的服务器，可以简单认为是项目组中的一台电脑用于远程数据交换。

![](https://github.com/ibusteri7/TASKS/blob/eb4f09af4ea2982f75a21301ddc53eee52aa3de4/photo/3.png)

> 
>
> 工作流程

一般流程：

1. 在工作项目中添加、修改文件；
2. 将需要进行版本管理的文件放入暂存区域；git add .
3. 将暂存区域的文件提交到git仓库。git commit -m "这里是备注"

因此，git管理的文件有三种状态：已修改、已暂存、已提交。

### Git项目搭建

![](https://github.com/ibusteri7/TASKS/blob/eb4f09af4ea2982f75a21301ddc53eee52aa3de4/photo/QQ%E5%9B%BE%E7%89%8720211103185556.png)

> 本地仓库搭建

1. 创建全新的仓库：git init
2. 克隆远程仓库：git clone 加链接

```c
// git add .               添加所有文件到暂存区
// git commit -m "消息内容" 提交暂存区中的内容到本地仓库 -m 提交信息
```

### 忽略文件

![](https://github.com/ibusteri7/TASKS/blob/eb4f09af4ea2982f75a21301ddc53eee52aa3de4/photo/5.png)

