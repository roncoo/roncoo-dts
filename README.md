# roncoo-dts
龙果学院《微服务架构的分布式事务解决方案》（RonCoo distributed transaction solution）

http://www.roncoo.com/course/view/7ae3d7eddc4742f78b0548aa8bd9ccdb

1、基于可靠消息的最终一致性方案；

2、TCC（Try/Confirm/Cancel）两阶段型方案；

3、最大努力通知型方案；

教程中的样例项目基于龙果学院开源的微支付系统进行实现，使用Dubbo作为服务化框架，教程中所实现的分布式事务解决方案在Java体系中的微服务架构系统都能通用，与具体的开发框架无关。

教程样例项目中用到的技术及相应的环境：
Dubbo、Spring、SpringMVC、MyBatis、Druid、JDK7（或JDK8）、MySQL5.6、Tomcat
