# README-GUIDE

<a href="https://github.com/HDUMIL-Gao-Group"><img src="https://img.shields.io/badge/Organization-%20Gao%20Group%20@%20HDUMIL-blue"></img></a>

## Table Of Contents 
- [README-GUIDE](#readme-guide)
  - [Table Of Contents](#table-of-contents)
  - [Background](#background)
  - [工程项目说明](#%e5%b7%a5%e7%a8%8b%e9%a1%b9%e7%9b%ae%e8%af%b4%e6%98%8e)
    - [通用项目目录结构](#%e9%80%9a%e7%94%a8%e9%a1%b9%e7%9b%ae%e7%9b%ae%e5%bd%95%e7%bb%93%e6%9e%84)
      - [README 书写流程和内容块](#readme-%e4%b9%a6%e5%86%99%e6%b5%81%e7%a8%8b%e5%92%8c%e5%86%85%e5%ae%b9%e5%9d%97)
        - [项目标题](#%e9%a1%b9%e7%9b%ae%e6%a0%87%e9%a2%98)
        - [项目摘要](#%e9%a1%b9%e7%9b%ae%e6%91%98%e8%a6%81)
        - [项目徽章](#%e9%a1%b9%e7%9b%ae%e5%be%bd%e7%ab%a0)
        - [项目目录](#%e9%a1%b9%e7%9b%ae%e7%9b%ae%e5%bd%95)
        - [项目背景](#%e9%a1%b9%e7%9b%ae%e8%83%8c%e6%99%af)
        - [代码运行要求](#%e4%bb%a3%e7%a0%81%e8%bf%90%e8%a1%8c%e8%a6%81%e6%b1%82)
        - [代码运行方法](#%e4%bb%a3%e7%a0%81%e8%bf%90%e8%a1%8c%e6%96%b9%e6%b3%95)
        - [项目流程](#%e9%a1%b9%e7%9b%ae%e6%b5%81%e7%a8%8b)
        - [项目总结](#%e9%a1%b9%e7%9b%ae%e6%80%bb%e7%bb%93)
        - [相关工作及参考资料](#%e7%9b%b8%e5%85%b3%e5%b7%a5%e4%bd%9c%e5%8f%8a%e5%8f%82%e8%80%83%e8%b5%84%e6%96%99)
        - [项目贡献者](#%e9%a1%b9%e7%9b%ae%e8%b4%a1%e7%8c%ae%e8%80%85)
        - [版权声明](#%e7%89%88%e6%9d%83%e5%a3%b0%e6%98%8e)
  - [Calender 项目说明](#calender-%e9%a1%b9%e7%9b%ae%e8%af%b4%e6%98%8e)
  - [Report 项目说明](#report-%e9%a1%b9%e7%9b%ae%e8%af%b4%e6%98%8e)

## Background

为了更好的管理、协作和传承团队项目，防止低效的重复性实验和繁重的交流沟通成本，构建一个完备的团队内部项目协作和交流空间是必不可少的。因此，我们构建了这个 Github 团队仓库，主要针对于对内的私下交流，可以存放半成品和任何不严谨的代码，不当作正式的对外开源空间使用（像余组一样 [Vision and Language Group@ MIL](https://github.com/MILVLG)）。

如果后期有需要构建团队的开源贡献框架，就重新再建立一个专门对外的团队仓库， 类似于余组 [Vision and Language Group@ MIL](https://github.com/MILVLG) 。

希望团队成员都可以将与团队科研和项目相关的资料都共享在这个仓库里，而不是各自独立的建立在自己的 Github 下或者直接存放在本机或服务器上，不进行云存储。

Pin 项目只留给需要固定使用的通知类项目，在这个团队空间中，我们先 Pin 了两个固定的仓库， [Calendar](https://github.com/HDUMIL-Gao-Group/Calendar) 仓库和 [Report](https://github.com/HDUMIL-Gao-Group/Report)
仓库。


## 工程项目说明

### 通用项目目录结构

> 是文档而非代码，定义了一个模块的功能。
> 
> —— [Ken Williams, Perl Hackers](http://mathforum.org/ken/perl_modules.html#document)

README 文件是人们通常最先看到的第一个东西。它应该告诉人们为什么要使用、如何安装、以及如何使用你的代码。如果你的文档是完整的， 那么使用你代码的人就不用再去看代码了。README 文件标准化能够使得创建和维护 README 文件更加简单。 毕竟，要写好一个文档不是那么容易的。

#### README 书写流程和内容块

我们对我们团队的项目 README 文档书写进行标准化约定，要求在每一个项目的 README 文件中都出现如下几个内容块：

1. 项目标题
2. 项目摘要
3. 项目徽章
4. 项目目录
5. 项目背景
6. 代码运行要求
7. 代码运行方法
8. 项目流程
9. 项目总结
10. 相关工作及参考资料
11. 项目贡献者
12. 版权声明

##### 项目标题

项目标题使用**一级标题**，也是 README 文档的标题。

##### 项目摘要

项目摘要写在项目标题的后面，用于简单的说明这个项目的具体内容和主要目标。

##### 项目徽章

项目徽章实际上是一个 svg 图片，可以用 html 语法进行书写，定义一个 img 标签来展示它。写在项目摘要后面，其功能类似于 Tag 标签分类功能。我们使用 [shields.io](https://shields.io/) 来构建我们的徽章。

其语法说明如下：
```
https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>
```

为了约束话期间，我们对 COLOR 的用法进行了约定，将 COLOR 与 LABEL 进行了关联约束：


- `<Organization>` 组织名 : `<blue>`

- `<Auther>` 项目作者名 : `<yellow>`， 项目作者名统一使用中文名

- `<Topic>` 课题名：`<orange>`，课题名的分类有待一致约定继续说明

- `<Tag>` 关键词标签：`<brightgreen>`，所用到的关键模型和技术等

- `<Category>` 任务分类：`<green>`，用来说明当前任务是属于说明类别，是属于组会的论文讲解任务，进度汇报任务还是科研实验项目等。

- `<Grade>` 年纪：`<eb2f96>` 表示研三，`<f759ab>` 表示研二，`<ff85c0>` 表示研一，`<ffadd2>` 表示本科生。


如果后续使用到了当前没有定义的徽章类别，那么需要继续统一协商绝对，指定该类别对应的颜色。

##### 项目目录

项目目录可以由 markdown 编辑器根据 markdown 语法自动生成。在 VSCode 中，我们可以安装 [markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) 插件，来添加这个功能。它会跟你的语法自动更新你的目录。同时，也可以安装 [markdown-preview-github-styles](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) 插件，让你的 markdown 预览效果与 github 中的真实效果相同。

如果你没有初始化这个目录的话，你可以在 vscode 的命令输入框中（使用 `ctrl` + `shift` + `P`）打开，输入 `Crearte Table Of Contents` 选择对应的 markdown-all-in-one 插件的命令，来完成初次自动创建。

使用项目目录，可以让你在较长的文档中快速的定位到你想要的位置，介绍查询时间和阅读成本。

项目目录之下的内容，就是这篇文档的正文部分了。


##### 项目背景

项目背景，用来说明项目的产生原因，项目来源。更好的了解项目的来源，可以帮助你更好的规划项目的目标和流程。

##### 代码运行要求

用来说明可以复现你的项目代码所需要的基本环境参数：语言环境、相应的环境包的安装方法、所需要的软硬件要求（操作系统、GPU显存等）。

##### 代码运行方法

用来说明你的项目代码的使用方法，如果是算法模型，如何进行训练，如何进行测试等。哪个是训练文件、哪个是测试文件，以及训练文件的外部参数的默认值及其说明等。

##### 项目流程

用来书写你的项目的实现步骤，类似于 TODO 列表，可以的规划和梳理项目流程，可以帮助你更好的理解和实现你的项目内容。

在 Github markdown 语法中，我们除了可以使用列表语法来定义列表，还可以定义复选框和表情包。

定义复选框的语法如下：

```
- [ ] list name
```

- [ ] list name

任务完成后，选定复选框的语法如下：

```
- [x] list name
```

- [x] list name

GitHub 的 emoji 语法定义如下：

```
:emoji:
```

Github 的 emoji 对应输入列表为：[Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)

##### 项目总结

项目总结应该跟着项目流程走，根据你的项目流程（也就是，你的项目实验过程的子要求），对每一步子要求具体的说明实验过程和实验总结。可只有发挥。

需要说明的是，GitHub 中对于图片的展示，不支持 markdown 语法，需要使用 html 语法来定义，当然关于图片地址的说明，你可以使用以项目目录为根目录的绝对地址或相对地址说明。

html 的 img 语法为
：

```
<img src="img_file/img_name.png" alt="img name"/>
```

如果想要约定 img 的尺寸大小，可以对 img 标签添加 width 和 height 属性的说明。

如果想要居中显示 img，就可以使用 `<div>` 标签来包裹这个 img。

```
<div align=center>
<img src="img_file/img_name.png" alt="img name"/>
</div>
```

如果想要并排显示多张图片，就可以像 markdown 语法一样，在每个 img 标签之间不进行空一行处理（只换行不空行是被允许的）。

```
<div align=center>
<img src="img_file/img_name.png" alt="img name"/>
<img src="img_file/img_name.png" alt="img name"/>
</div>
```

如果想要换行显示，就在每个 img 标签之间空一行，即可。


##### 相关工作及参考资料

用来说明，你的工作使用的参考资料和基石，比如说是对原始的 SinGAN 模型做的改进，或者你的代码也是根据原始的 SinGAN 官方代码做的小修改，就对其进行相应的说明。


##### 项目贡献者

用来说明这个项目的主要贡献者，可以使用 github 的 @ 语法，来同时 @ 贡献者的 GitHub ID 进行具体指定说明。

##### 版权声明

用来说明该项目，是否允许他人直接使用，或者是否其他的使用要求。

## Calender 项目说明

Calendar 仓库用来存储导师给团队成员分配的任务列表，只有导师一个人具有操作权限。对于需要团队成员具体完成的任务，可以使用 Github 的清单语法：

```
- [ ] list name
```

- [ ] list name
- [ ] 

学生完成之后，可以对其进行标记，已完成：

```
- [x] list name
```

- [x] list name

对于不需要学生具体完成的，而只是做参考的项目可以使用普通的列表语法：

```
- list name
```

- list name

## Report 项目说明

Report 用来管理团队的文档（组会的论文讲解PPT，个人的每周总结，年度总结等。）由学生和老师共同管理，在每次组会前，将需要用到的资料上传到对应周目录下，并构建相应的标签和索引。

在仓库中按年+周的方式来定义文件夹，用来记录这是某年第几次组会的文档内容。对于其他的不适用于按周进行分类的文档，可以建立另外的仓库。

Report 的 readme 文档，就是对各个文件夹中的文件的索引目录表。

按照文件名（也就是周名）来定义 readme 标题。

其中的内容就是具体的索引文件的文件名，为了更好的说明文件，可以添加该文件的徽章来说明文件的类别，标签等。

为了方便的根据目录给出的文件 URL 地址直接下载对应的文件，可以下载安装 [enhanced-github](https://chrome.google.com/webstore/detail/enhanced-github/anlikcnbgdeidpacdbdljnabclhahhmd) chrome 插件，这样就可以实现对单个文件的下载，而不必要下载全部工程，来耗费下载资源了。






