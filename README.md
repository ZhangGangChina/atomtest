---


---

[TOC]

------



## atom简要说明

------

​	atom是跨平台文本编辑器。可以在windows、linux、mac等操作系统上进行文本编辑，前后端代码编写和管理。

​	强大的插件提供了完美的用户体验、git与github管理、多种语言编程。

​	特别是markdown格式语言。

​	让我使用组合工具开始atom奇妙之旅吧！

​	请诸神见证。

------





## 1.工具列表及说明

​	atom+typora+git+github工具组合完成项目文件的管理工作。

- atom
- typora
- git
- github

------



## 2.工具安装及配置

### typora安装及配置

- Typora - 颠覆写作体验的免费极简 Markdown 编辑器！好用的 MD 格式阅读器
- 官网：<https://www.typora.io/>
- 简介：<https://www.iplaysoft.com/typora.html>
- 下载版本：typora-setup-x64.exe，0.94.8

### atom安装及配置

- Atom 更为先进的文本代码编辑器 - 由 Github 打造的下一代编程开发利器
- 官网：<https://atom.io/>
- 简介：<https://www.iplaysoft.com/atom-editor.html>
- ATOM中文手册：http://wiki.jikexueyuan.com/project/atom/overview.html>
- Atom：AtomSetup-x64.exe，1.26.0
- 通信协作插件：teletype需要如下软件
- To run teletype tests locally, you'll first need to have:
  Atom 1.22 or laterNode 7+PostgreSQL 9.x
- node.js：https://nodejs.org/en/download/，node-v8.11.1-x64.msi
- postgreSQL：<https://www.postgresql.org/download/>，postgresql-10.3-2-windows-x64.exe，参见evernote之markdown编辑器

### git安装及配置

- Git extensions - Visual Studio 和 Windows 资源管理器的 Git 扩展程序

  发布这一程序的目的是希望它有使用价值，但并不做任何担保，没有针对特定用途适用性的隐含保证

- 下载版本：2.51.01,GitExtensions-2.51.01-SetupComplete.msi

- 安装.net framework 4.6.1,NDP461-KB3102436-x86-x64-AllOS-ENU.exe

- 使用认证方案:https，不支持ssh

- 克隆github工程，注意选择分支与客户端要一致，如服务器端是master；客户端应为origin/master:master

- 注意：如使用ssh方案克隆工程，会提示不支持。


### github配置

- 注册帐户
- 创建仓库
- 设置仓库权限https读写权限，否则只有读权限，不能push.
- 使用git extensions克隆仓库
- 使用typora编辑一下readme.md
- 使用atom的git插件提交
- 查看github官方帐户仓库提交文件
- 再用git extensions获取仓库，有内容更新
- 验证成功。

## 3.业务场景

- 对事件进行记录和跟踪，typora。
- 对服务端的配置文件进行编辑，atom。
- 使用文本编辑器进行编程调试，atom。
- 其他场景待补充。



## 4.使用流程

- github创建仓库，并设置帐户读写权限；
- 复制https的仓库链接
- 使用git客户端克隆仓库
- 使用工具创建、编辑文件
- 使用工具向github提交修改和创建文件，可以是atom,或git extensions，或eclipse。


## 5.仓库的目录结构

- atomtest
  - README.md
  - img
  - files
  - subproject
    - readme.md
    - img
    - fileware
    - other files

## 6.阅读工具

- 建议使用typora.

