嗨，Spring粉丝们，新一期的[Spring周报]新鲜出炉！本周我奔波于芝加哥、纽约和丹佛，和Pivotal公司的客户洽谈沟通。本周有很多干货分享哦~

1、Spring Data大牛Thomas Risberg刚宣布了Spring for Apache Hadoop 2.5.0.RC1的发布。此次发布主要是BUG修复。此外还展望了Spring for Apache Hadoop 3.0，它以Spring Boot为基础，要求Java8以上、集成Spark2.0、关注Spring Batch 4.0。

https://spring.io/blog/2017/06/23/spring-for-apache-hadoop-2-5-0-rc1-released

2、Spring Data大牛Mark Paluch谈了许多Spring Data Kay中的新特性，包括支持MongoOperations接口、Kotlin语言、更智能的MongoDB排序、Java9兼容性等。

https://spring.io/blog/2017/06/20/a-preview-on-spring-data-kay

3、Arnold Galovics的博客中发布了一篇关于如何在Spring Boot中配置数据源代理的文章。

http://blog.arnoldgalovics.com/2017/06/26/configuring-a-datasource-proxy-in-spring-boot/

4、Renato Athaydes有一篇关于Kotlin隐式成本的文章，有兴趣可以前往阅读。

https://sites.google.com/a/athaydes.com/renato-athaydes/posts/kotlinshiddencosts-benchmarks

5、Kotlin语言如何与JVM和编译器交互的基础深挖？对于想深入研究Kotlin的童鞋，值得一读，即使这篇文章和Spring没有多大关系。

https://t.co/wWlIQQX4PH?ssr=true

6、GitHub上有一个有趣的应用，使用Spring Boot编写，以太坊或Quorum网的ERC-20令牌标准的RESTful服务。

https://github.com/blk-io/erc20-rest-service

7、从Redmonk最新关于Java语言和框架的研究来看，Spring和Spring Boot表现非常不错。

https://redmonk.com/fryan/2017/06/22/language-framework-popularity-a-look-at-java-june-2017/

8、Mark Heckler在这篇文章中研究了在REST APIs中使用XML，有需要的可供参考。

http://www.thehecklers.org/2017/06/21/t4sd-tips-4-spring-devs-how-to-get-spring-boot-rest-endpoints-to-speak-xml/

9、下面这篇使用Quartz调度API的文章，它从基本的使用着手，最终延伸到Spring Boot的使用经验。

https://t.co/5iIp2tLCcC?ssr=true

10、Tammy Butow这篇阐述Chaos工程基础的文章很不错。

https://t.co/DgzjCrWM8h?ssr=true

11、如果一个应用可以每天自动更改它的访问凭证，使得每一个被窃取的密码在短时间内失效，从而达到自动抵御攻击的目的，会怎样？这个想法推动了CredHub——Pivotal公司的Cloud Foundry云引入的一项新特性。可以前往VentureBeat阅读这篇文章了解更多详情。

https://venturebeat.com/2017/06/16/pivotal-cloud-foundry-aims-to-thwart-hackers-with-ever-changing-passwords/

12、Dormain Drewitz在最近的Cloud Foundry峰会上推介了一些Cloud Foundry客户的成功诀窍。

https://medium.com/p/secrets-of-successful-cloud-foundry-adopters-232193111b18


原文如下：

Hi Spring fans and welcome to another installment of This Week in Spring! This week I’m in Chicago, New York City and Denver talking to Pivotal customers. We’ve got a lot of good stuff to look at this week so let’s get to it!
Spring Data ninja Thomas Risberg just announced Spring for Apache Hadoop 2.5.0.RC1. The new release is primarily a bugfix. The post looks forward to Spring for Apache Hadoop 3.0, which will be based on Spring Boot, a Java 8 baseline, Spark 2.0 integration, and Spring Batch 4.0 readers and writers.
Spring Data ninja Mark Paluch looks at a lot of the new features in Spring Data Kay including support for fluent MongoOperations, Kotlin,smarter MongoDB collation, Java 9 compatability, and so much more.
I liked Arnold Galovics’s post on how to configure a DataSource proxy in Spring Boot.
Kotlin’s hidden costs - Benchmarks - Renato Athaydes -
Bytecode generation on the JVM and Kotlin - This is a deep-dive into the basics of how the Kotlin-language interacts with the JVM and the compiler. Worth a read if you’re diving into Kotlin (as I have been for the last few years) even if the post doesn’t have a lot to do with Spring perse.
A Spring Boot application that talks to Ethereum or Quorum network - This was an interesting Spring Boot application that talks to an Ethereum or Quorum network.
In Redmonk’s latest look at Java language and framework popularity, Spring and Spring Boot seem to be doing quite well!
Mark Heckler looks at serving XML in REST APIs in this useful post
I liked this post on using the Quartz scheduling API. It starts from the basic usage and eventually gets all the way through to the Spring Boot experience. Nice!
I liked this presentation on the basics of Chaos Engineering by Tammy Butow.
What if an application could automatically repel attackers by rotating its access credentials every day, thereby making every stolen password useless in a short amount of time? That’s the idea behind CredHub, a new feature introduced for Pivotal Cloud Foundry today. Read the rest of this VentureBeat article for more.
Dormain Drewitz chimes in with a look at some Secrets of successful Cloud Foundry users from the recent Cloud Foundry Summit.


