# SSM项目初始化的框架
这里提供两个初始化的ssm框架项目

## 一、 Lab/mixcontent
+ 说明
   - 这是一个整合了Spring SpringMVC Mybatis框架的一个初始化项目。
   
+ 使用
   - sql文件在src/db/lab.sql
   - generator目录是存放用于自动生成java的插件
   - 源码在main里面
   - 注意打包maven，clean-compiler-resources-war

+ 测试
  - 设置本项目到tomcat服务器，启动服务。
  - 浏览器输入http://localhost:8080/，测试调用jsp
  - 浏览器输入http://localhost:8080/user/jsontype/1，测试controller是否正常运行
  
  
 ## 二、 Lab/divcontent
 + 说明 
   -  与上面的不同是将各个文件分开了，初学者容易理解，但是碎片文件变多了。
   
+ 使用
   - sql文件在src/db/db.sql
   - 部署到tomcat启动服务

+ 测试
  - http://localhost:8080/book/allBook
  - http://localhost:8080/book/toAddBook
  - 测试页面是否可以正常访问