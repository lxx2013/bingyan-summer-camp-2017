## 冰岩作坊夏令营前端组任务

首先，欢迎你来到冰岩作坊 2017 暑期夏令营！

紧张而刺激的娱（xue）乐（xi）进程即将开始，少侠，扛上你的开天辟地合金键盘和你的倚天屠龙大鼠标迎接挑战吧！

### 入门指引（选做）

在本阶段，将通过几个小任务帮助你熟悉前端开发流程、工具以及巩固基础，借此来使你在大任务的开发中更加轻松。

#### 任务 1

##### 前言

在这个任务的学习中，我们希望你能够：

1. 入门日常开发时所使用的工具。
2. 安装 Git，了解 Git 命令的基本使用方法。
3. 了解 Github 的基本使用方法。

##### 任务简介

挑选出个人喜欢的开发工具，并且尝试用 Markdown & Git 来写属于你的第一篇日志.

推荐完成时间：`1 天`

##### 任务要求

1. 下载 Visual Studio Code，Sublime，Atom，Webstorm（必须用学校邮箱申请免费 lisence），尝试在其中新建一个新项目，文件夹名为 `bingyan-camp-[你的名字全拼]`。
2. 安装 Git，使用 git-bash 将上述文件夹转换成 Git 仓库。
3. 在其中新建一个文件，名为 `Readme.md`，并在其中按照 Markdown 语法写入你的个人简介。
4. 尝试用 Git 进行提交。
5. 注册 Github 账号，新建与文件夹同名仓库，并将本地文件上传到 Github 仓库，并将仓库地址发于导师。

##### 参考资料

[廖雪峰的 Git 教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

[利用 SSH 连接 Github](https://help.github.com/articles/about-ssh/)

#### 任务 2

##### 前言

在这个任务的学习中，我们希望你能够：

1. 初始 node.js，并基本了解 npm 的简单用法。

##### 任务简介

安装 node.js 最新 LTS 版，并尝试使用 npm 下载指定包实现简单的命令行效果。

推荐完成时长：`.5 天`

##### 任务要求

1. 要求使用 Git 进行版本管理，须在 `bingyan-camp-[你的名字全拼]` 下的 `task3` 文件夹中编写代码。
2. 使用 npm 命令，初始化 `package.json` 并安装 `colors` 包。
3. 新建 index.js 文件，使用 node.js 运行，并尝试用代码在其中输出彩虹色的 `Geek is the new sexy!`。 

##### 参考资料

[color 库（使命令行输出充满少女情怀）](https://www.npmjs.com/package/colors)

#### 任务 3

##### 前言

在这个任务的学习中，我们希望你能够：

1. 掌握更多的 HTML 元素及其属性。
2. 了解元素是如何在网页中被定位的。
3. 通过实践深入了解 CSS 盒模型，以及块级元素与行内元素的默认行为及其用法。
4. CSS 过渡、动画、伪类、伪元素的用法及其神奇的效果。
5. 初步了解如何使用原生 JavaScript 或 JQuery 与页面元素进行交互。

##### 任务简介

根据提供图片，重构[小米官网](http://www.mi.com)，完成基本样式及要求的交互效果。

推荐完成时长：`3 天`

##### 任务要求

1. 要求使用 Git 进行版本管理，须在 `bingyan-camp-[你的名字全拼]` 下的 `task2` 文件夹中编写代码。
2. 效果图如下图所示，可以参考小米官网上对应区域进行开发。
3. 保证在内容宽度固定的情况下，内容整体于页面居中，当窗口宽度小于内容宽度时才允许出现横向滚动条。
4. 参考或自行分析页面结构，完成 HTML 文件的编写，以下提出的样式表及脚本文件需要外部引用。
5. 根据图片或原网站，完成静态无任何交互的样式（鼠标悬浮、页面切换等）；如选购手机，企业团购部分的图标，可以尝试使用 [Iconfont](http://www.iconfont.cn/) 上的字体 icon 实现。
6. 在商品元素卡片上利用 CSS 实现鼠标悬浮时的动画效果。
7. 利用 JavaScript，实现在鼠标单击轮播图左右按钮时切换展示页。
8. 参考原网站实现，尝试利用 CSS 或 JavaScript 其中一种方法实现鼠标滑过时显示分类所属商品效果（如果有时间可以都尝试一下）。

![](http://pic.yupoo.com/tiancaigaohua/GxGhAl2t/e4Diq.png)



#### 任务 4

##### 前言

在这个任务的学习中，我们希望你能够：

1. 进一步巩固 HTML、CSS，及 JavaScript 基础。
2. 深入了解 CSS 各种尺寸单位。
3. 基本了解移动端适配原理。
4. 基本了解如何向服务器请求数据。

##### 任务简介

实现一个移动端的最热电影信息列表。

推荐完成时长：`3 天`

##### 任务要求

1. 要求使用 Git 进行版本管理，须在 `bingyan-camp-[你的名字全拼]` 下的 `task4` 文件夹中编写代码。
2. 根据设计图，实现移动端全屏的基本页面结构和样式（重复元素如列表暂实现一个即可）。
3. 学习如何使用 rem 单位，并在除字体之外的尺寸中使用，并使用 lib-flexible 库，要求适配 iPhone 5 - 6 Plus，Galaxy S5，Nexus 6P（使用浏览器模拟）。
4. 在 JavaScript 获取豆瓣前 250 电影信息（`GET http://api.douban.com/v2/movie/top250`），选取前 10，传入到函数中创建上述 HTML 元素列表项，并插入到页面中。

![](http://pic.yupoo.com/tiancaigaohua/GxGhAoOH/y4kdJ.png)

##### 参考资料

[使用 Flexible 实现移动端适配](https://github.com/amfe/article/issues/17)

谷歌关键字：http verb, ajax, fetch, javascript create element

#### 任务 5

##### 前言

在这个任务的学习中，我们希望你能够：

1. 了解服务器的基本工作原理。
2. 了解 HTTP 请求的基本工作原理。
3. 了解如何使用 Express 框架搭建一个简单的服务器。

##### 任务简介

使用 Express 框架搭建简单服务器，并伺服任务 4 中网页，手动实现其 api 。

推荐完成时长：`1.5 天`

##### 任务要求

1. 要求使用 Git 进行版本管理，须在 `bingyan-camp-[你的名字全拼]` 下的 `task5` 文件夹中编写代码。
2. 安装 express 包，按官方教程创建静态文件服务器，将任务 4 中的网站复制到本任务中，使其可本地访问。
3. 创建本地 api，路径为 `/api/v1/movie/top250` ，返回与任务 4 中豆瓣 api 相同的 json 格式的数据，测试 api 可使用 postman。
4. 修改网站，使其请求自己实现的 api 并正常工作。

##### 参考资料

[Express Getting Started](http://expressjs.com/en/starter/installing.html)

谷歌关键字：http request, chrome Network, express.js, express static server, express response json

### 主任务

以下任务任选其一完成，允许使用 Vue、React 等框架。仅需兼容最新版 Chrome 即可。建议尝试 Webpack、Gulp 等工具加速开发。

其中，标记 ** 的为推荐但不强制功能，未提及功能可选择实现。

#### 论坛系统

##### 任务简介

模仿 [该社区](https://vivaldi.club/t/pool) 实现一个论坛系统。

##### 功能模块

1. 用户系统
   1. 登陆注册
   2. 个人信息编辑
   3. **邮箱验证
   4. **通知
      1. 回复通知
      2. 帖子内 @
2. 发帖系统
   1. 版块分区、子板块
   2. 发帖
   3. 帖子浏览排序
   4. 回复楼主
   5. 回复层主
   6. **用户个人签名
   7. **插入外链图片/富文本
   8. **帖子列表定时/及时更新提示

##### 参考资料

谷歌关键字：mongodb, mysql, mariadb, express mongodb

#### 你画我猜

##### 任务简介

实现一个移动端/网页端均可用的你画我猜游戏

##### 功能模块

1. 用户系统
   1. 登录注册
   2. **微信端注册及登陆
2. 房间
   1. 随机进入现有房间
   2. 自行创建房间
   3. 浏览房间列表
   4. 玩家准备机制
   5. **观战模式
3. 游戏环节
   1. 按词库为每个玩家生成一个词
   2. 时间限制
   3. 鼠标滑动或手指滑动进行作画，作画过程同步
   4. 橡皮擦
   5. 聊天&猜测窗口（正确答案隐藏）
   6. **画笔属性（颜色，粗细）调整
   7. **丢鸡蛋/送花功能

##### 参考资料

谷歌关键字：canvas, websocket, mongodb, socket.io

#### 轻博客

##### 任务简介

模仿 [Tumblr](http://tumblr.com) ，实现文字、视频、图片、音频的发布。

##### 功能模块

1. 用户系统
   1. 登录注册
      1. 登陆注册页背景效果仿制
   2. 回复、转发等提示
   3. 关注其他人
   4. 个人博客/**一账号多博客
2. 博客系统
   1. 不限字数的文字发布
   2. 图片发布
      1. **多图发布
   3. 视频、音频发布
      1. 使用文件
      2. **直接调用电脑摄像头、录音机进行录制
   4. 转发
   5. 点赞
      1. 点过赞的列表
   6. 关键字搜索

##### 参考资料

谷歌关键字：轻博客, blog, mongodb, mysql

### 备注

1. 所有任务必须使用 Git 进行版本管理，并且传到 Github 上，将地址发到夏令营群内并私发给对应导师，必须有清晰、风格统一的 Commit。（可参考 [Commit message 和 Change log 编写指南](http://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html) ）
2. 请于每日完成开发日志，内容主要为学习了什么东西，感受可选，然后通过导师指定方式发给对应的导师。如果你认为你的 Commit 写的非常优秀，也可以直接发 Git Log 哦~
3. 5 日一次 Code Review，检查代码风格及明显错误，以及与导师和其他夏令营同学一起讨论。
4. 网站尽量兼容更多的屏幕尺寸，如果可以使用响应式进行开发就更好了。
5. 后台的部分，首先要熟悉数据库的基本用法，推荐 mongodb 的原因是其非关系型数据库，上手要更加简单些。
6. 如数据库链接一类的功能，在上手自己写之前先找有没有适合的 npm 包来加速开发。
7. 模仿网站的时候，页面结构和命名可以参考，但不允许直接复制粘贴（导师们一眼就能看出来是抄的还是写的），要思考为什么对方这样使用，答辩的时候也会提问。
