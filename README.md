Publican 工具使用手册
====================


如何生成用户手册：

1. 安装 publican 工具 ( [安装方法](http://jfearn.fedorapeople.org/en-US/Publican/2.7/html/Users_Guide/chap-Users_Guide-Installing_Publican.html) )

2. 获取本项目

    git clone git://github.com/luoyun/PublicanUserGuide.git

3. 进入 PublicanUserGuide 目录，发布 html 格式：

    publican build --formats html --lang zh-CN --common_content=Common_Content/
