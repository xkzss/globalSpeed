# 1、Spring

1、框架；半成品软件；

**`高度抽取可重用代码的一种设计；高度的通用性；`**

​     书城：WebUtils.java;BaseServlet;Filter....

​     打包：boostore.jar；（工具类）

​          commons-fileupload，commons-io（工具类），commons-dbutils（方便操作数据库的工具）

​     框架：抽取成一种高度可重用的；事务控制，强大的servlet，项目中的一些工具。，，，

​          框架：多个可重用模块的集合，`形成一个某个领域的整体解决方案`；

2、Spring；

​     容器（可以管理所有的`组件（类`））框架；

​     核心关注：IOC和AOP；

 <img src="https://gitee.com/efzy/tuchuang/raw/master/img/25c8e17f-1ef2-4a9f-90ec-ec336a0bfe6c.png" alt="25c8e17f-1ef2-4a9f-90ec-ec336a0bfe6c" style="zoom: 80%;" />

3、Spring（IOC和AOP ）

Test：Spring的单元测试模块；

   spring-test-4.0.0.RELEASE

Core Container：核心容器（IOC）；黑色代表这部分的功能由哪些jar包组成；要使用这个部分的完整功能，这些jar都需要导入

```
spring-beans-4.0.0.RELEASE、
spring-core-4.0.0.RELEASE、
spring-context-4.0.0.RELEASE、
spring-expression-4.0.0.RELEASE
```

AOP+Aspects（面向切面编程模块）

```
spring-aop-4.0.0.RELEASE、spring-aspects-4.0.0.RELEASE
```

数据访问：Spring数据库访问模块

```
  spring-jdbc-4.0.0.RELEASE、spring-orm(Object Relation Mapping)-4.0.0.RELEASE、
  spring-ox（xml）m-4.0.0.RELEASE、spring-jms-4.0.0.RELEASE、（Intergration）
  spring-tx-4.0.0.RELEASE(事务)
```

Web：Spring开发web应用的模块；

```
spring-websocket(新的技术)-4.0.0.RELEASE、
spring-web-4.0.0.RELEASE、和原生的web相关（servlet）
spring-webmvc-4.0.0.RELEASE、开发web项目的（web）
spring-webmvc-portlet-4.0.0.RELEASE（开发web应用的组件集成）
```

用哪个模块导哪个包（建议）；

------

开发Spring框架的应用，经常要写框架的配置文件，写起来复杂，我们需要提示；

需要给eclipse中安装插件；（提供提示功能）；

------

插件安装：

1）、不想装插件；使用Spring官方提供的sts开发工具（装好插件的eclipse）

2）、装插件；

​     1）、查看当前eclispe的版本；

​          Help->About Eclipse-->点击自己eclipse的图标

<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825220540670.png" alt="image-20230825220540670" style="zoom:67%;" />

​		2）、安装新软件

​     		1）、

​	<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825220630739.png" alt="image-20230825220630739" style="zoom:67%;" />

​			2）、看好选中插件

​			<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825220708382.png" alt="image-20230825220708382" style="zoom:67%;" />

​			3）、4.3.2可以装4.3.1；

​				<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825220737035.png" alt="image-20230825220737035" style="zoom:80%;" />

​			4）、选中带有SpringIDE的四项；

​				<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825220931409.png" alt="image-20230825220931409" style="zoom:80%;" />

​			5）、一路next

​			<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825221023101.png" alt="image-20230825221023101" style="zoom:67%;" />

3、安装成功的标志；

<img src="https://gitee.com/efzy/tuchuang/raw/master/img/image-20230825221121385.png" alt="image-20230825221121385" style="zoom: 67%;" />