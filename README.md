maven_project
=============

maven的web开发案例
该项目中包含了一个简单的maven结构方式的web app应用代码。 必须理解以下几点：
* 1.maven结构方式的web app应用目录，理解pom.xml的web配置( 有两个，父子关系)。
* 2.能够在IDEA下，新建导入maven project方式打开该案例，并运行通过浏览器顺利打开页面。
* 2.1 先在Lifecycle中执行install命令
* 2.2 在plugins下执行jetty:run命令 （前提已在pom.xml下配置完毕）
* 3