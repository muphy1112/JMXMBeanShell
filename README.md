# JMXMBeanShell
MBean使用JMX远程命令执行漏洞利用复现

JMX是管理扩展，通过JMX可以监控管理按照MBean格式编写的java程序，MBean格式要求有接口和实现两个类，接口命名以MBean结尾，实现类命名为接口名去掉MBean，如：接口HelloMBean与实现类Hello。

使用方式查看博客：https://www.cnblogs.com/muphy/p/13971984.html