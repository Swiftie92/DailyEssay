# DailyEssay : 日常随笔

- ### [01-Nginx&uWSGI&CORS「部署前后端分离项目与跨域请求限制」](https://github.com/kerbalwzy/DailyEssay/blob/master/01-Nginx%26uWSGI%26CORS.md)

  - ##### 快速使用Nginx和uWSGI两个服务器部署一个前后端分离的项目

    - ##### Nginx服务器同一端口设置多个服务节点

    - ##### uWSGI服务器的基本使用

  - #### 解决跨域请求限制的简单方法，认识浏览器的同源策略

    - ##### 浏览器的同源策略是造成跨域请求限制的主要原因

    - ##### 通过响应头信息告知浏览器当前服务器允许来自某个域名的跨域请求

----

- ### [02-Mateclass&ORM.md 「Python中的元类与ORM」](https://github.com/kerbalwzy/DailyEssay/blob/master/02-Mateclass%26ORM.md)

  - #### 了解我们使用的ORM模块是如何通过我们定义的模型类获取到字段信息的

    - ##### 元类，创建类的多种方式

    - ##### 实现父类自动注册它的子类

----

- ### [03-CustomWebFramework.md 「自定义一个WEB框架」](https://github.com/kerbalwzy/DailyEssay/blob/master/03-CustomWebFramework.md)

  - #### 基于uWSGI服务器和WSGI协议构建一个功能相对较为齐全的专门适用于前后端分离的WEB框架

  - #### 设计我们想要的项目初始结构，和文件内容

  - #### 安装miniFrame框架到site-packages中，并完善好框架需要提供的shell命令

----

- ### [FlaskKonwledgeGmae 「Flask趣味知识竞赛工具」](https://github.com/kerbalwzy/aboutPython/tree/master/FlaskKnowledgeGame)

  - ##### 包含一个网页交互界面,启动时请使用服务器模式提供静态文件, 不要直接通过File协议通过浏览器打开

  - ##### 实现读取本地JSON格式题库文件, 切换题目, 查看答案, 结束答题时自动根据积分重新排序积分榜等功能

  - ##### JS部分代码纯使用 Vue 和 axios 完成

----

- ### [KnowledgeSummary 「WEB框架知识总结」](https://github.com/kerbalwzy/aboutPython/tree/master/KnowledgeSummary)

  - ##### 主要用于末位辅导工作的框架知识点总结

  - ##### 鉴于前后端分离的大趋势, 总结中忽略了部分前后端不分离使用知识

  - ##### Flask框架必知必会、Django框架必知必会、DjangoRestFramework框架必知必会

----

- ### [Windows10Subsystem.md 「WIN10系统安装Linux子系统教程」](https://github.com/kerbalwzy/aboutPython/blob/master/Windows10Subsystem.md)

  ##### 在Windows上使用Linux子系统的主要目的是为了使用Linux环境下的数据库, 和在将要部署时方便快速的子系统上去预演一遍.使用了子系统之后,在开发中就可以避免直接在Window上装各种数据库或第三方服务的麻烦和避免使用Linux虚拟机占用大量的内存

----

- ### [InstallDockerOffline 「离线安装适配Ubuntu18的Docker」](https://github.com/kerbalwzy/aboutPython/tree/master/InstallDockerOffline)

  ##### 在Ubuntu18中离线安装Docker19.08稳定版, 内附 快速安装教程 和 详细安装教程

---

- ### [使用djangorestframework-jwt和自定义backend做用户登录验证源代码浅析](https://github.com/kerbalwzy/aboutPython/blob/master/UseDRF-JWTtoAHUTwithOwnBackend.md)

  - ##### 了解前提: 扎实的Django、DRF框架基础

  - ##### 只简单的分析了处理用户登录验证时是如何找到我们自定义的backend对象的

