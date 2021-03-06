---
title: API文档工具-Swagger的集成
categories:
  - 运维部署
tags:
  - Swagger
date: 2016-9-10 18:24:17
toc: false

---

> 最近安装了API文档工具swagger，因为Github上已有详细安装教程，且安装过程中没有碰到大的阻碍，所以此文仅对这次安装做一份大致记录

### 相关网站

Swagger 官方地址： 
http://swagger.wordnik.com 

Github安装详解【springmvc集成swagger】:
https://github.com/rlogiacco/swagger-springmvc

网上安装教程【可配合Github安装教程使用】：
http://www.jianshu.com/p/5cfbe62a1569
http://blog.csdn.net/fengspg/article/details/43705537

Swagger注解详解：
https://github.com/swagger-api/swagger-core/wiki/Annotations#apimodel
http://www.cnblogs.com/java-zhao/p/5348113.html 【springboot + swagger】

<font style="color:red">API文档工具 RAML、Swagger和Blueprint三者的比较：</font>
http://www.cnblogs.com/softidea/p/5728952.html

<!-- more -->

---

### 错误记录

配置完并成功启动项目后，报如下错误：

![](http://7xvfir.com1.z0.glb.clouddn.com/API%E6%96%87%E6%A1%A3%E5%B7%A5%E5%85%B7-Swagger%E7%9A%84%E9%9B%86%E6%88%90/1.png?imageView2/0/q/75|watermark/1/image/aHR0cDovLzd4dmZpci5jb20xLnowLmdsYi5jbG91ZGRuLmNvbS8lRTYlQjAlQjQlRTUlOEQlQjAvJUU1JThEJTlBJUU1JUFFJUEyJUU2JUIwJUI0JUU1JThEJUIwLnBuZw==/dissolve/100/gravity/SouthEast/dx/10/dy/10|imageslim)

**原因**：在修改配置文件index.html时，ip和端口中间多了一个斜杠，去掉斜杠即可。

![](http://7xvfir.com1.z0.glb.clouddn.com/API%E6%96%87%E6%A1%A3%E5%B7%A5%E5%85%B7-Swagger%E7%9A%84%E9%9B%86%E6%88%90/2.png?imageView2/0/q/75|watermark/1/image/aHR0cDovLzd4dmZpci5jb20xLnowLmdsYi5jbG91ZGRuLmNvbS8lRTYlQjAlQjQlRTUlOEQlQjAvJUU1JThEJTlBJUU1JUFFJUEyJUU2JUIwJUI0JUU1JThEJUIwLnBuZw==/dissolve/100/gravity/SouthEast/dx/10/dy/10|imageslim)

PS：果不是以上原因造成，请移步 https://github.com/swagger-api/swagger-ui 查看此错误详细介绍:

![](http://7xvfir.com1.z0.glb.clouddn.com/API%E6%96%87%E6%A1%A3%E5%B7%A5%E5%85%B7-Swagger%E7%9A%84%E9%9B%86%E6%88%90/3.png?imageView2/0/q/75|watermark/1/image/aHR0cDovLzd4dmZpci5jb20xLnowLmdsYi5jbG91ZGRuLmNvbS8lRTYlQjAlQjQlRTUlOEQlQjAvJUU1JThEJTlBJUU1JUFFJUEyJUU2JUIwJUI0JUU1JThEJUIwLnBuZw==/dissolve/100/gravity/SouthEast/dx/10/dy/10|imageslim)





