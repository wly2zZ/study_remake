#  spring5框架

结构

![1615981205057](spring5框架.assets/1615981205057.png)



##  1.ioc

配置文件

![1614839791566](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614839791566.png)



###  1.1 概念和原理

![1614668118017](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614668118017.png)

![1614668146853](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614668146853.png)

### 1.2 接口

![1614668716231](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614668716231.png)

![1614668728253](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614668728253.png)

###  1.3 ioc操作Bean管理(xml管理)

1.什么是Bean管理

​    Bean管理指的是两个操作：（1）Spring创建对象 （2）SPring注入属性

2.Bean管理操作有两种方式

  （1）基于xml配置文件方式实现

  （2）基于注解方式实现

![1614669796440](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614669796440.png)

![1614670111534](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670111534.png)

![1614670152530](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670152530.png)

![1614670280567](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670280567.png)

<b>            先创建对象再注入属性</b>

![1614670547181](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670547181.png)

![1614670560179](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670560179.png)

![1614670874766](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614670874766.png)

![1614671313917](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614671313917.png)

![1614671387186](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614671387186.png)

![1614671642432](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614671642432.png)

![1614671851894](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614671851894.png)



2.注入属性-外部bean

![1614695082015](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614695082015.png)

![1614695375229](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614695375229.png)

   <b>xml文件</b>

![1614695341724](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614695341724.png)

![1614695932600](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614695932600.png)

3.注入属性-内部bean和级联赋值

![1614696294190](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614696294190.png)

（3）配置spring文件

![1614696518136](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614696518136.png)

级联赋值

![1614697004563](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614697004563.png)



4.xml注入属性集合

![1614697382213](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614697382213.png)

1.数组

![1614697542894](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614697542894.png)

2.list类型

![1614697561486](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614697561486.png)

3.map类型

![1614697619254](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614697619254.png)



对象注入list集合

![1614698356880](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614698356880.png)



使用util标签完成list集合注入提取

![1614698828173](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614698828173.png)



Bean的作用域

默认单实例，scope=“singleton"默认单实例  prototype=多实例 

![1614784200740](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614784200740.png)

![1614785059198](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614785059198.png)

![1614785465731](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614785465731.png)



自动装配

![1614786066216](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614786066216.png)



配置连接池

![1614837420626](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614837420626.png)



引用外部配置信息

![1614837517955](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614837517955.png)

![1614837680819](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614837680819.png)

![1614837694748](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614837694748.png)

![1614837919217](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614837919217.png)



###  1.4 ioc操作Bean管理(注解管理)

![1615626511826](spring5框架.assets/1615626511826.png)



![1614838453497](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614838453497.png)

![1614838583246](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614838583246.png)

![1614839101584](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614839101584.png)

![1614839281089](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614839281089.png)

![1614839261363](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614839261363.png)



组件扫描的细节配置

![1614840159699](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614840159699.png)

![1614840222286](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614840222286.png)

![1614840716277](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614840716277.png)

![1614840985396](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614840985396.png)

![1614840992889](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1614840992889.png)

一个接口有多个实现类，如果根据类型注入，会导致多态无法有效使用，所以用到Qualifier根据名称注入，这个方法要和Autowired一起使用

![1615082523178](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615082523178.png)

 

![1615082716064](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615082716064.png)

 ###  1.5 完全注解开发

![1615083403651](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615083403651.png)

![1615083505781](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615083505781.png)

相当于spring boot

## 2. AOP

### 2.1 概念

![  ](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615086066351.png)

![1615086117980](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615086117980.png)

![1615086081172](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615086081172.png)

### 2.2 底层原理



![1615087398015](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615087398015.png)

![1615088093539](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615088093539.png)

 

 使用jdk动态代理 Proxy类

![1615292479675](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615292479675.png)

编写JDK动态代理代码

![1615292704745](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615292704745.png)

![1615292717254](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615292717254.png)

  P27 代码编写

### 2.3 术语

 1.连接点

​	类里面那些方法可以被增强，这些方法称为连接点

2.切入点

​	实际被真正增强的方法，称为切入点

3.通知（增强）

​	（1）实际增强的逻辑部分称为通知（增强）

​	（2）通知有多种类型

![1615294677186](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615294677186.png)

4.切面

![1615295104278](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615295104278.png)

### 2.4 操作（准备）

![1615295490330](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615295490330.png)

 ![1615295632752](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615295632752.png)

![1615295942380](C:\Users\a\AppData\Roaming\Typora\typora-user-images\1615295942380.png)

![1615296274708](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615296274708.png)

*中间有个空格==所有权限符

..代表所有参数

![1615296617415](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615296617415.png)



![1615296664162](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615296664162.png)

###  2.5Aspect（注解）

![1615296964884](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615296964884.png)

![1615297047211](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297047211.png)

![1615297129778](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297129778.png)



（1）

![1615297299009](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297299009.png)

（2）

<img src="F:\桌面文件\wlyPPT\markdown\1615297341803.png" alt="1615297341803" style="zoom:53%;" />

（3）

![1615297385348](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297385348.png)

（4）

![1615297444642](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297444642.png)意思就是扫描有没有@Aspect类的对象，有就开启

![1615297682839](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615297682839.png)

**PS**：

![1615298931438](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615298931438.png)

![1615299050163](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615299050163.png)

### 2.6 AspectJ配置文件（了解）

![1615299238286](F:\桌面文件\wlyPPT\markdown\spring5框架.assets\1615299238286.png)



##  3.数据源

### 3.1 配置数据源

1.导入包

2.导入坐标

![1615687707189](spring5框架.assets/1615687707189.png)

### 3.2 抽取数据源

jdbc.properties

![1615687862307](spring5框架.assets/1615687862307.png)

C3P0数据源

![1615688070157](spring5框架.assets/1615688070157.png)

方便解耦

###  3.3 spring配置数据源（c3p0）

xml文件 

![1615688313439](spring5框架.assets/1615688313439.png)

property的name 就是set方法的头字母小写

**测试**

![1615688425764](spring5框架.assets/1615688425764.png)



如果要配置druid的话 property要注意name的名字



![1615688585811](spring5框架.assets/1615688585811.png)

### 3.4 jdbcTemplate

![1615689750885](spring5框架.assets/1615689750885.png)

![1615690595583](spring5框架.assets/1615690595583.png)



###  3.5 spring产生jdbcTemplate对象

![1615690843017](spring5框架.assets/1615690843017.png)

spring代码：

![1615691326970](spring5框架.assets/1615691326970.png)



模板：

![1615691563596](spring5框架.assets/1615691563596.png)



省略![1615691707707](spring5框架.assets/1615691707707.png)

![1615692082453](spring5框架.assets/1615692082453.png)

![1615692261775](spring5框架.assets/1615692261775.png)

jdbcTemplate.query（sql，new BeanPropertRowMapper<T>(类的字节码))

T代表封装的实体类

**单个查询**，queryForObjcet(sql=?，new BeanPropertRowMapper<T>(类的字节码),属性)



**聚合查询，**

![1615692525403](spring5框架.assets/1615692525403.png)

###  3.6 知识要点

![1615692655012](spring5框架.assets/1615692655012.png)

jdbcTemplate new完之后要注入数据源才能用



##  4.事务控制-编程式

###  4.1 PlatformTransactionManger

![1615980017923](spring5框架.assets/1615980017923.png)

###  4.2 TransactionDefinition

![1615980100343](spring5框架.assets/1615980100343.png)

### 4.3 TransactionStatus

## 5. 基于XML的声明式事务控制

![1615981026923](spring5框架.assets/1615981026923.png)

###  5.1 声明式事务控制的实现

![1615981640961](spring5框架.assets/1615981640961.png)

切点---目标对象就是切点 例如转账

通知--事务的增强 

![1615982214825](spring5框架.assets/1615982214825.png)

![1615982262963](spring5框架.assets/1615982262963.png)

![1615984206010](spring5框架.assets/1615984206010.png)

## 6. 基于注解的声明式事务控制

![1615984578074](spring5框架.assets/1615984578074.png)

##  Spring集成web环境

![1616235944194](spring5框架.assets/1616235944194.png)

监听器：

![1616236025318](spring5框架.assets/1616236025318.png)

1 配置监听器 web/xml 

![1616236534666](spring5框架.assets/1616236534666.png)

获取：在doget或post

![1616236581381](spring5框架.assets/1616236581381.png)

![1616236593132](spring5框架.assets/1616236593132.png)





在web xml里面取代 获取应用上下文 方便更改名字

![1616236877270](spring5框架.assets/1616236877270.png)

![1616237035363](spring5框架.assets/1616237035363.png)

这是spring提供的监听器

**使用方法**：

 ![1616237183928](spring5框架.assets/1616237183928.png)

![1616237257275](spring5框架.assets/1616237257275.png)



![1616237311218](spring5框架.assets/1616237311218.png)







