a)	maven
i.	2d
ii.	产出 自建工程
项目管理，依赖、插件管理工具，着重了解中心库、本地库、私有库等概念

b)	spring
i.	2-3d
ii.	产出 demo
IOC：inverse of control 控制反转
自动装配autowire：1，byName，2，byType
注解装配：引入<context:annotation-config/> 
Qualifier:用于筛选出合适bean
自动检测：引入<context:component-scan/>
@component标签 -> 通用的构造型注解，标示该类为Spring组件
@Controller -> 标示讲该类定义为Spring MVC con
@Repository -> 标示讲该类定义为数据仓库
@Service -> 标示讲该类定义为服务
AOP：aspect of programming 切面编程
把分散在各处通用的代码放入可重用的模块，减少代码的冗余
 

c)	jdbc
i.	2d
ii.	产出 demo

d)	mybatis
i.	2d
ii.	产出demo
 
User作为model，用于与数据库中的字段做映射
UserDAO是提供一组操作的接口
需定义一个mapping文件用于对象关系映射：
 
配置userDAO bean用于具体的操作
 

e)	xjc: xsd-->java bean
i.	1d
ii.	产出 编写xsd并生成java bean

f)	jaxb: xml <--> java bean
i.	2-3d
ii.	产出 demo
Jaxb : java architecture for xml binding

g)	jackson: json <--> java bean
i.	1-2d
ii.	产出 demo
    关键类: ObjectMapper

h)	dozer: java bean --> java bean
i.	2-3d
ii.	产出 demo
Dozer做对象转换有什么特点 :
1.	默认属性Mapping，即如果属性名称一样， 就不需要显示配置，Dozer会自动处理。
2.	自动做类型转换，即如果两个属性名称一样，即使类型不一样，在Dozer可理解范围内，帮你处理得妥妥的。Dozer可理解的类型范围非常广，这会极大的提升程序员的生产力
3.	不必担心中间的null property，遇到null property，Dozer会把对应的所有属性全部设置为null，而不会抛NullPointerExeception。
实例：http://blog.sina.com.cn/s/blog_71b8dd040100ron3.html

i)	http
i.	apache-httpclient
1.	1d
2.	产出 demo
模拟发出HTTP请求，可得到resonse对象
ii.	jetty
1.	1-2d
2.	产出 demo
以Server为中心，围绕着三大重要模块：Connector，Handler，ThreadPool，其架构可概括为：Jetty Server由一组接受http连接的Connectors和一组处理来自连接的请求并响应的Handlers，通过取自线程池中的线程来完成相关工作。
iii.	客户端和服务端联调

j)	webservice
i.	server
1.	2d
2.	产出 demo
ii.	client
1.	2d
2.	产出 demo
iii.	联调
@SOAPBinding注解的用法：决定SOAP数据的编码样式，由style，use两个属性
决定
@suppresswarning：用于屏蔽某些警告的提示
 
k)	spring-integration
i.	2-3d
ii.	产出 demo

l)	activemq
i.	生产者
1.	2d
2.	产出 demo
 producer发送数据有一个属性，设为PERSISTENT表示数据长久保持，当ActiveMQ关闭后不会丢失，反之如果设为NON_PERSISTENT，则会丢失
 
ii.	消费者
1.	2d
2.	产出 demo
 
iii.	联调
与Spring整合

m) mybatis
i. 熟悉配置文件所有标签含义
ii. 了解缓存机制
iii. 学习分页相关，拦截插件

n）elasticsearch
i. 增删查改索引
ii. 分词插件
iii. 模糊匹配

o) kafka
i. 了解客户端基本使用
ii. 了解实现机制

p) redis
i. 基本使用
ii. 发布订阅

r) docker
i. 原理
ii. 结合kubernetes搭建应用发布平台
 
s) 分布式系统架构
i. 高并发
ii. 高可用
iii. 反向代理
iiii. 负载均衡



