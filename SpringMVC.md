# SpringMVC

![1616237865323](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616237865323.png)

## 1.开发步骤

1.导入springMVC包--坐标

2.配置共有servlet--DispatherServlet 前端控制器

3.编写Controller

4.将Controller使用注解配置到spring容器种（@Controller）--web层

5.开启注解组件扫描--- 配置spring-mvc.xml

6.执行访问测试

![1616238150951](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238150951.png)



2.  ![1616238279070](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238279070.png)

3.   编写UserController

   ![1616238419651](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238419651.png)

4. spring-mvc

   ![1616238537185](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238537185.png)

5. 引入spring-mvc xml 

   ![1616238614376](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238614376.png)

6. 测试 在地址输入@RequestMapping中的名字，就能执行对应的方法

**流程图**：

![1616238814212](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1616238814212.png)

![1616238896944](SpringMVC.assets/1616238896944.png)

![1616241373511](SpringMVC.assets/1616241373511.png)

##  2.springMvc组件解析

![1616241654360](SpringMVC.assets/1616241654360.png)

method  = Requestmethod.get/post

--------------------------------

![1616241524428](SpringMVC.assets/1616241524428.png)

 ![1616241606510](SpringMVC.assets/1616241606510.png)

加   **/**   的意思===当前目录下的资源

![1616242430906](SpringMVC.assets/1616242430906.png)

###  资源解析器？？

## 3.SpringMVC的数据响应

![1616242615626](SpringMVC.assets/1616242615626.png)

  ![1616242864503](SpringMVC.assets/1616242864503.png)

![1616242882896](SpringMVC.assets/1616242882896.png)

Model:模型 封装数据

View:视图 展示数据 

RequestMappint(value="/路径")

![1616243165721](SpringMVC.assets/1616243165721.png)

在jsp中${username}

![1616246084898](SpringMVC.assets/1616246084898.png)

![1616246153099](SpringMVC.assets/1616246153099.png)

##  4.文件上传

![1616673511548](SpringMVC.assets/1616673511548.png)

![1616673675724](SpringMVC.assets/1616673675724.png)

![1616673743280](SpringMVC.assets/1616673743280.png)

![1616673795939](SpringMVC.assets/1616673795939.png)

##  5.拦截器

![1616674171201](SpringMVC.assets/1616674171201.png)

![1616674280549](SpringMVC.assets/1616674280549.png)

![1616674488396](SpringMVC.assets/1616674488396.png)

![1616675095970](SpringMVC.assets/1616675095970.png)

##  6.异常

![1616676637767](SpringMVC.assets/1616676637767.png)

![1616676802610](SpringMVC.assets/1616676802610.png)

![1616676862386](SpringMVC.assets/1616676862386.png)

![1616677512285](SpringMVC.assets/1616677512285.png)、

##  spring练习

![1616677972860](SpringMVC.assets/1616677972860.png)

