嗨，Spring粉丝们，新一期[Spring周报]来了！本周我会在田纳西州纳什维尔做一个关于Reactive Spring的演讲分享，然后赶去堪萨斯城再重讲一遍。两次都会和Mark Heckler一起。如果你们在这两个城市，可别错过咯。
对这两个活动感兴趣的同学，可以进来看看详情。
纳什维尔：https://www.meetup.com/nashvillejug/events/237237449/
堪萨斯城：https://www.meetup.com/kc-spring/events/237043686/

我正在研究下一期的Spring Tips，你们想看到哪些内容呢？去推特@SpringTipsLive上给我留言吧~ 
本周确实有大量干货可以分享，赶紧来看看。

1、Spring消息和集成大师Artem Bilan刚发布Spring for Apache Kafka 2.0 M3。新版本主要包括新的Kafka事务管理器KafkaTransactionManager，并支持KafkaTemplate。

https://spring.io/blog/2017/07/24/spring-for-apache-kafka-2-0-milestone-3-available

2、Spring Security Session大牛Joe Grandja刚发布了Spring Session 2.0 M3。新版本主要增加了对Spring WebFlux、WebSession以及响应式编程的支持。

https://spring.io/blog/2017/07/25/spring-session-2-0-m3-released

3、永不止步! Christoph Strobl也发布了Spring Data Kay RC1和RC2新版。新版包括Spring Data for Apache Geode、响应式优化、Cassandra v3.0的驱动升级等，且修复120+个问题。

https://spring.io/blog/2017/07/25/spring-data-release-train-kay-rc1-rc2-released

4、Christoph Strobl 发布了Spring Data Ingalls SR5的大升级，修复了40多个问题。

https://spring.io/blog/2017/07/25/spring-data-ingalls-sr5-released

5、Spring Integration 大牛 Artem Bilan刚发布了Spring Integration 5.0 M6版。升级包括了对响应式HTTP信道适配器的支持，能方便与Spring Cloud Function进行集成，并包含了新的JDBC元数据存储。

https://spring.io/blog/2017/07/25/spring-integration-5-0-milestone-6-available

6、Spring Boot 大牛 Andy Wilkinson 刚发布了Spring Boot 1.5.5 维护版。

https://spring.io/blog/2017/07/26/spring-boot-1-5-5-available-now

7、Spring Data 大牛Thomas Risberg 发布了Spring Cloud Data Flow 1.2.3 维护版，主要包括了一个开源的SQL Server的JDBC驱动，和改进后的参考文档。

https://spring.io/blog/2017/07/26/spring-cloud-data-flow-1-2-3-released

8、Spring Boot 和 Cloud Foundry云平台大牛Madhura Bhave发布了Spring Boot 2.0.0.M3, 拉取了Spring Framework 5RC3的更新，关闭了100多个问题。

https://spring.io/blog/2017/07/26/spring-boot-2-0-0-m3-available-now

9、Spring Batch负责人Michael Minella发布了Spring Batch 4.0.0.M3。新版本进一步改进了各种ItemReader和ItemWriter的Java配置构建器。此外，终结了Spring Batch Admin的使命，可以使用Spring Cloud Data Flow来代替它。

https://spring.io/blog/2017/07/26/spring-batch-4-0-0-m3-is-now-available

10、哇哦！Spring Session Data Geode 2.0.0.M1发布了。这是Spring Data Geode(同样支持Pivotal的Gemfire产品)集成Spring Session的产物。Spring Data Geode的@ClientCacheApplication注解和Spring Session Data Geode 的@EnableGemFireHttpSession注解让Spring Boot应用变为一个Geode缓存客户端，它可通过将数据分布到一个Geode服务器集群来管理HTTP session状态，以达到快速可靠（重放）访问。Spring Data传奇John Blum及其团队做得非常漂亮，这次的发布太酷了。

https://spring.io/blog/2017/07/27/spring-session-data-geode-gemfire-2-0-0-m1-now-available

11、Spring Vault负责人Mark Paluch发布了Spring Vault 1.1.0.M1 和 2.0.0.M2。两个版本都包括了AWS IAM Vault 登录，基于租约期限的通用密钥的翻转，以及一份使用VaultEndpointProvider动态配置端点的说明。此外，2.0.0.M2版本包括一个认证的DSL，集成了Spring Framework5,并增强了对可空的支持。

https://spring.io/blog/2017/07/27/spring-vault-1-1-0-m1-and-2-0-0-m2-available

12、Spring Boot 1.5.6发布了。Spring Boot1.5.5版有一个小问题，所以大家直接使用1.5.6吧。

https://spring.io/blog/2017/07/27/spring-boot-1-5-6-available-now

13、Spring传奇Greg Turnquist发布了Spring Sessions MongoDB 2.0.0.M2。这个版本带来了新的依赖，并且集成了Spring Framework5的响应式支持。

https://spring.io/blog/2017/07/27/spring-session-mongodb-2-0-0-m2-released


14、Spring Security OAuth大牛Joe Grandja发布了Spring Security OAuth 2.2.0.RELEASE。这次打包发布，恭喜Spring Security团队，干得不错。

https://spring.io/blog/2017/07/28/spring-security-oauth-2-2-released

15、Spring Framework 5 Kotlin的APIs，函数的方式——Sébastien Deleuze研究了Spring Framework 5 对Kotlin语言本地支持的很多优化点。这里面有太多令人兴奋的点，其中的一些效果——比如关注可空验证——给Java开发者使用Spring提供了一些新血液和灵感。

https://spring.io/blog/2017/08/01/spring-framework-5-kotlin-apis-the-functional-way

16、虽然我们推荐Spring Cloud Data Flow用来统筹Spring Batch任务，但你依然可以使用SPring Batch Admin，甚至可以在Spring Boot环境下运行它，可以参考Joris Kuipers在GitHub上提供的这个样例。

https://github.com/jkuipers/boot-batchadmin

17、ADTMag上有一篇很好的分析最近的Spring Framework 5.0RC3的文章。

https://adtmag.com/articles/2017/07/26/spring-release-candidate.aspx

18、Kotlin在Hootsuite的黎明时代——Hootsuite平台上有一篇文章谈论了他们使用Kotlin语言的一些经验。文章中，他们审视了使用Kotlin完成Android开发的动机以及遇到的种种问题，可前往一阅。

http://code.hootsuite.com/dawn-of-the-age-of-kotlin-at-hootsuite/

19、Verizon的Josh Stone谈到了企业大规模运行Cloud Foundry平台的经验。

https://content.pivotal.io/cloud-foundry-summit-2017-2/what-does-it-take-to-run-cloud-foundry-at-enterprise-scale

20、我的朋友Harry Zhang指出Container Storage Interface将会是一个非常有前途的项目，它涉及到来自Cloud Foundry，Kubernetes，Mesos和Docker的众多参与者。

https://twitter.com/resouer/status/891909789747367936

21、Coding Dojo很显然已经放弃了他们的ROR训练营（由于兴趣减弱），转向开展一个Spring研讨会。我个人最近几年看到了这种影响。我认为这意味着两件事：a）ROR对行业来说已经算是一个惊喜了，b)如果人们选择使用Spring来代替ROR的话，Spring肯定是正在做一些非常正确的事。何不自己尝试呢？你可以通过点击下面第二个链接直接体验高效创建Spring项目的感觉。

https://flipboard.com/@flipboard/-ruby-on-rails-is-out-major-coding-bootc/f-e61f983902%2Fthenextweb.com
http://start.spring.io/

22、Codecentric’s的Johannes Edmeier分享了一个好消息，Codecentric Spring Boot Admin Server的下载量已经超过了六百万次。这是很令人振奋的消息。

https://twitter.com/joshiste/status/891660694826995712

戳下文了解更多关于基于Spring Boot的应用的dashboard选项。

https://spring.io/blog/2016/12/07/spring-tips-bootiful-dashboards

23、为什么PCF是Spring Boot最好的平台？Pivotal的Toshiaki Maki极好地阐述了为什么Cloud Foundry平台（尤其是Pivotal的Cloud Foundry平台）是开发者使用Spring的最佳实践。

https://www.slideshare.net/makingx/why-pcf-is-the-best-platform-for-spring-boot
https://www.slideshare.net/makingx/why-pcf-is-the-best-platform-for-spring-boot

24、Michael Kops有一篇非常好的文章，阐述了使用Karate（一个web测试框架）来测试基于Spring Boot项目的Rest Apis服务。

https://semaphoreci.com/community/tutorials/testing-a-java-spring-boot-rest-api-with-karate


25、Charity Majors 有一篇很棒的文章 "Ops: It’s Everyone’s Job Now!", 文章呼吁软件开发者拥抱运维思想。作为一个整体，这对更高阶的系统和成果交付是至关重要的。

https://opensource.com/article/17/7/state-systems-administration

26、Dan Vega有一篇关于为SpringMVC端点配置多HTTP请求映射的绝妙文章。

http://therealdanvega.com/blog/2017/07/03/multiple-request-mappings-spring-boot

27、Grails项目负责人Graeme Rocher 发布了Grails 3.3.GA。大家快更新吧~~

http://grailsblog.objectcomputing.com/posts/2017/07/26/grails-3.3-ga-released.html

28、想要一个全功能的Spring Cloud应用的案例？可以参考Benjamin Wilms在GitHub上的这个DEMO。

https://github.com/MrBW/resilient-transport-service

29、Spring的创始人Rod Johnson介绍了他的公司Atomist关于自动化及彻底简化项目初始化方面的技术。Atomist不止研究了代码生成，还聚焦于基础设施，例如 云平台集成，生命周期管理，资源仓库，松整合等。

https://the-composition.com/no-more-copy-paste-bf6c7f96e445


原文如下：

Hi Spring fans! Welcome to another installment of This Week in Spring! This week I’m in Nashville, TN, for a meetup presentation on Reactive Spring and then it’s off to Kansas City, KS for a replay of the same talk. Both times I’ll be joined by pal Mark Heckler. If you’re in either of those cities, don’t miss this!
I’m working on the next installments of Spring Tips: what would you like to see covered? Let me know on Twitter on @SpringTipsLive.
This week we have a truly massive good many things to look at so let’s get started!
Spring messaging and integration maestro Artem Bilan just announced Spring for Apache Kafka 2.0 M3. The new release includes, among other things, a new KafkaTransactionManager and according supportin the KakfaTemplate.
Spring Session 2.0 M3 Released - Spring Security and Session ninja Joe Grandja just announced Spring Session 2.0.M3. This new release adds support for Spring WebFlux, and its WebSession and reactive programming in general.
Not one to rest on his laurels, Christoph Strobl also announced the new release of Spring Data Kay RC1 and RC2. These releases include Spring Data for Apache Geode, reactive tuning, a Cassandra v3.0 driver upgrade and so much more, including 120+ tickets fixed!
Christoph Strobl just announced just announced a massive Spring Data Ingalls SR5 release with over 40 issues fixed.
Spring Integration 5.0 Milestone 6 Available - Spring Integration ninja Artem Bilan just announced Spring Integration 5.0M6. This release includes support for the reactive HTTP channel adapter, convenient integration with Spring Cloud Function, a new JDBC metadata store, and so much more.
Spring Boot ninja Andy Wilkinson has just announced the Spring Boot 1.5.5 maintenance release.
Spring Data ninja Thomas Risberg announced the Spring Cloud Data Flow 1.2.3 maintenance release which include, among other things, an OSS-licensed SQL Server JDBC driver and improved reference documentation.
Spring Boot and Cloud Foundry ninja Madhura Bhave just announced Spring Boot 2.0.0.M3 which pulls in Spring Framework 5RC3 and closes over 100 tickets! Get the bits now!
Spring Batch lead Michael Minella has just announced Spring Batch 4.0.0.M3. This new release further improves the Java Configuration builders for various ItemReader and ItemWriters. It also end-of-lifes the Spring Batch Admin. You should use Spring Cloud Data Flow, instead.
Hurray! Spring Session Data Geode 2.0.0.M1 is now available. This is a Spring Session integration that builds upon Spring Data Geode (which also supports Pivotal’s Gemfire product). Spring Data Geode’s @ClientCacheApplication and Spring Session Data Geode’s @EnableGemFireHttpSession annotations turn your Spring Boot application into a Geode cache client capable of managing the HTTP Session state by distributing data to a cluster of Geode servers for fast and reliable (replicated) access. Nice work to Spring Data legend John Blum and team! This is such a cool release.
Spring Vault lead Mark Paluch’s announced Spring Vault 1.1.0.M1 and 2.0.0.M2. Both new releases include AWS IAM Vault login, rotation of generic secrets based on their lease duration, and an introduction of VaultEndpointProvider to configure endpoints dynamically. Additionally, 2.0.0.M2 includes an authentication DSL, reactive Spring Framework 5 integration, and enhanced nullability support.
Spring Boot 1.5.6 available now - There was a small issue int he Spring Boot 1.5.5 release, so get 1.5.6, instead.
Spring Session MongoDB 2.0.0.M2 released - Spring legend Greg Turnquist just announced Spring Sessions MongoDB 2.0.0.M2. This new release brings in new dependencies and integrates with Spring Framework 5’s reactive support.
Spring Security OAuth ninja Joe Grandja just announced Spring Security OAuth 2.2.0.RELEASE. This is a packed release, so congratulations to the Spring Security team on a job well done!
Spring Framework 5 Kotlin APIs, the functional way - Sébastien Deleuze looks at a number of the nice improvements in Spring Framework 5’s native support for the Kotlin-language. There’s so much to love here! Some of the efforts - like a focus on nullability checks - also bleed through and improve the lives of Java developers using Spring, as well.
While we recommend Spring Cloud Data Flow for anybody who wants to manage and interrogate Spring Batch jobs, you can still use Spring Batch Admin and you can even run it in a Spring Boot environment, as this sample from Joris Kuipers demonstrates.
ADTMag has a nice look at the recent Spring Framework 5.0RC3 release.
Dawn of the Age of Kotlin at Hootsuite – Code @ Hootsuite - Hootsuite talks about their use of the Kotlin language. In this post they look at their motivations and the issues they’ve encountered when using it for Android development.
Verizon’s Josh Stone talks about the experience of running Cloud Foundry at scale。
my friend Harry Zhang points out that the Container Storage Interface will be a very promising project in that it involves participants from Cloud Foundry, Kubernetes, Mesos, and Docker.
Coding Dojo has apparently dropped their Ruby on Rails bootcamp, due to waning interest, and are now running a Spring workshop, instead. I’ve, personally, seen this effect a lot in recent years. I think that this says two things: a) Ruby on Rails has been an amazing boon for the industry b) Spring must be doing something right if people are opting to use it instead of Ruby on Rails! Why don’t you try it for yourself?
Codecentric’s Johannes Edmeier shares the good news that there have been more than six million downloads of the Codecentric Spring Boot Admin Server! This is very promising news! Learn more here about various dashboard options for your Spring Boot-based applications
Why PCF is the best platform for Spring Boot - Pivotal’s own Toshiaki Maki has put together an awesome look at why Cloud Foundry, and specifically Pivotal’s Cloud Foundry, is the best experience for developers using Spring.
Michael Kops has a nice post on testing Spring Boot-based REST APIs with Karate, a web testing framework.
Charity Majors has a great post, “Ops: It’s Everyone’s Job Now!” which urges software developers to embrace operations-minded thinking. This is critical if we’re to, as a community, move to higher order systems and deliverables.
Dan Vega has a nice post on configuring multiple HTTP request mappings for Spring MVC endpoints.
The Grails project lead, Graeme Rocher, just announced Grails 3.3.GA. Check it out!
Want a full-featured example Spring Cloud application? You might like this resilient demo by Benjamin Wilms.
Rod Johnson, creator of Spring, look at his company Atomist’s technology for automating and drastically simplifying project initialization. Atomist looks at more than just code-generation and focuses on infrastructure like cloud-platform integration, lifecycle, repositories, Slack integration, etc.


