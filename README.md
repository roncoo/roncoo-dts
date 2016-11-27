# 微服务架构的分布式事务解决方案
龙果学院《微服务架构的分布式事务解决方案》（RonCoo distributed transaction solution）

http://www.roncoo.com/course/view/7ae3d7eddc4742f78b0548aa8bd9ccdb

整体方案流程图：
http://img.roncoo.com/education/course/2016/07_26/img/601f1cf9d0884a6dab2043c335f341ff.jpg

1、基于可靠消息的最终一致性方案；
http://img.roncoo.com/education/course/2016/07_17/img/8da5a88cc9df427795173839010c2ce4.jpg

2、TCC（Try/Confirm/Cancel）两阶段型方案；
http://img.roncoo.com/education/course/2016/08_03/img/51fbbcdd54e74bef9a46a0d70c5157fb.jpg

3、最大努力通知型方案；
http://img.roncoo.com/education/course/2016/07_17/img/b10e10aa0f9347f9b8e84de592b4c709.jpg

教程中的样例项目基于龙果学院开源的微支付系统进行实现，使用Dubbo作为服务化框架，教程中所实现的分布式事务解决方案在Java体系中的微服务架构系统都能通用，与具体的开发框架无关。

教程样例项目中用到的技术及相应的环境：
Dubbo、Spring、SpringMVC、MyBatis、Druid、JDK7（或JDK8）、MySQL5.6、Tomcat
