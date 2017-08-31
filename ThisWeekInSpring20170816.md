嗨，Spring粉丝们。欢迎浏览这一期的[Spring周报]。过去一周实在太忙了。我先是在北卡和一个开发者群体聊，然后回旧金山和Matt Raible一起做了一个关于VJUG的演讲。紧接着又到圣路易斯和开发者们聊，再赶到纽约录制一个关于持续交付的视频，在燥热的录像棚中录了三天（哥的整个周末！）。好在我现在已飞回旧金山，在前往亚洲（杭州，上海，北京，深圳，香港和新加坡）的四周之旅前，我可以休息幸福的14个小时。当然，也不是只有我才忙咯。以下就是本周的分享内容~


1、我的朋友Spring Framework的领导Juergen Hoeller在 Devoxx PL 2017大会上做了一个关于Spring响应式编程的演讲。希望大家看看~

https://www.youtube.com/watch?v=TZUZgU6rsNY


2、我哥们Matt Raible和我上周做了一个使用Angular和Spring Boot构建渐进式的Web应用程序和强大稳定的后端服务的演讲。关于这个主题，Matt和我说过很多次，每次都很有意思。我们通过直播的方式，我使用Apache Groovy、Kotlin和java来写后端服务，他使用TypeScript写客户端。我觉着Matt才是真英雄，因为即使我只写完三个服务，他却需要写出大量的TypeScript来使客户端运行起来。这个视频是在太搞笑了，走过路过不要错过，哈哈~~

https://virtualjug.com/building-robust-apis-and-apps-with-spring-boot-and-angular/


3、《Java云原生》终于写作完成并发售了！我朋友Kenny Bastani和我为O’Reilly出版社完成了一部拙作《Java云原生,如何基于Spring Boot，Spring Cloud 和Cloud Foundry构建云原生Java应用程序》。这本书耗费了我们两年时间，在Spring团队内部被审阅过无数次，也受到Spring创始人Rod Johnson和Cloud Foundry传奇James Watters的支持和推动。这本书不会是你买的最烂的一本书的，所以希望大家可以考虑买一本回去看看。衷心感谢Spring粉丝们的耐心。

亚马逊购书传送门：https://www.amazon.com/Cloud-Native-Java-Designing-Resilient/dp/1449374646/ref=sr_1_1?ie=UTF8&qid=1502769139&sr=8-1&keywords=cloud+native+java


4、距离在加州旧金山Moscone中心举办的SpringOne Platform 2017大会（12.4-12.7）不到四个月了。我当然会去，希望你们也去。如果你还犹豫不决，打开下面的链接看看我这波安利。如果你已经决定了，哈哈，也可以打开这个链接，看看文章最后我们市场团队合成的那张不忍直视的动图。

https://spring.io/blog/2017/08/08/there-s-no-place-like-production-springone-platform-will-illuminate-the-path


5、大爱Spring Framework 5 的参考文档！

https://docs.spring.io/spring-framework/docs/5.0.0.BUILD-SNAPSHOT/spring-framework-reference/


6、我喜欢这个Pull Request。不是对是否支持表达明确的观点，只是觉得评论才是亮点。它本身讨论的是Spring Boot 2是否应该默认支持HTTP2。可能它是仅适用Java9的特性？也许是趋于探索使之能运行于Java8仅有的几个方案。如果你有什么想法或想知道更多，可以签出看看。

https://github.com/spring-projects/spring-boot/pull/9981


7、大家有看这篇文章基于Spring使用Google Cloud Pub/Sub进行消息通信的入门指南么？

https://spring.io/guides/gs/spring-cloud-gcp/


8、Codecentric上这篇文章研究了Spring Boot项目中如何使用指定日期格式解析Java8 LocalDate的查询参数。

https://blog.codecentric.de/en/2017/08/parsing-of-localdate-query-parameters-in-spring-boot/


9、Matthew Casperson研究了给一个Spring Boot项目集成Spring Security。短小精悍，顺理成章。干得非常漂亮。

https://dzone.com/articles/logging-into-a-spring-bootelide-json-api-server?fromrel=true


10、Dzone上这份文档是使用Google云的一份很好的参考教材。我越来越喜欢Google云了，它提供很多业务差异化的功能，是个运行Cloud Foundry平台的好地方。

https://dzone.com/refcardz/getting-to-know-google-compute-engine-and-how-to-u


11、我朋友John Willis研究了PDCA和OODA组织定位模型，如何借鉴已发生的情况来确定下一步的执行策略。虽然文章本身跟Spring没有什么关系，但殊途同归。

https://slightlyeastofnew.com/2013/11/20/pdca-vs-ooda-why-not-take-both/amp/


12、本周我和我的朋友Marcin Grzejszczak（Pivotal持续交付方面的疯狂砖家）花了好几天在录像棚里，希望录更多的内容分享给大家，这次主要研究基于Spring和Pivotal生态系统的持续交付。视频中我们花了大量时间剖析JsonPath，也是想提醒大家关注JsonPath项目本身以及这篇来自Baeldung的介绍JsonPath的博客。

项目链接：https://github.com/json-path/JsonPath
博客链接：http://www.baeldung.com/guide-to-jayway-jsonpath


13、自从Stormpath团队融合后Okta博客就很火，似乎每天都有大量的优质内容。这篇博客中使用Apache Shiro为Spring Boot应用作为安全框架，想做类似事情的同学可以参考~

https://developer.okta.com/blog/2017/07/13/apache-shiro-spring-boot


14、Okta上周还有一篇博客，Matt Raible的神作，研究使用Spring Security，JWTs, Juiser 和 Okta作为Spring Boot和Spring Cloud微服务架构的安全框架。

https://developer.okta.com/blog/2017/08/08/secure-spring-microservices


15、恭喜Reactive Streams团队上周刚发布了Reactive Streams1.0.1。

http://www.reactive-streams.org/announce-1.0.1


16、Auth0对于Spring Boot安全方面的工作也很赞。本周他们发布了Spring Boot集成JWTs安全框架的研究。

https://auth0.com/blog/implementing-jwt-authentication-on-spring-boot/


17、Atomist联合创始人Russ Miles研究了他们的协同工具平滑支持PullRequest工作流的能力。他们是基于一个应用（正好是Spring Boot写的）环境完成此事，但在一篇文章如此不起眼的段落里引用Spring Boot，对于彰显结论价值是远远不够的。Atomist总是这么酷，就破例一次吧。

https://github.com/ErnestOrt/Trampoline/releases


18、恭喜JetBrains的Kotlin团队，新发布的Kotlin 1.2.M2看起来超赞。包括了支持Kotlin能统一运行于JVM，JavaScript运行时环境上的数学运算新API。是时候“喜新厌旧”了，可以尝试一下新的特性，不妨用Spring Boot项目初始化器。

https://blog.jetbrains.com/kotlin/2017/08/kotlin-1-2-m2-is-out/
Spring Boot项目初始化传送门：http://start.spring.io/


19、Redmonk上有一篇文章关于Spring Boot的用户New Relic和特斯拉使用的一些情况。

http://redmonk.com/jgovernor/2017/08/10/notes-from-the-field-spring-boot-at-tesla-and-new-relic/


20、YouTube上关于韩国首尔的Spring训练营视频列表及其所有的Pivotal和Spring内容（韩语版）都可以看了。这是非常好的韩语资源。

https://www.youtube.com/playlist?list=PLdHtZnJh1KdZ6NDO9zc9hF4tONDLTSEUV


21、葡萄牙语版的Spring Boot书籍《Spring Boot: Acelere o desenvolvimento de microsserviços》看起来不错。

https://www.casadocodigo.com.br/products/livro-spring-boot


22、Camunda BPM团队的Bernd Rücker发布了一个在分布式应用中集成Spring Boot和Camunda BPM的示例。README和代码同样有趣，我很喜欢测试部分的讨论，这在像工作流引擎这类高端工具中通常是很欠缺的。

https://github.com/berndruecker/camunda-spring-boot-amqp-microservice-cloud-example/



原文如下：

Hi Spring fans and welcome to another installment of This Week in Spring! It’s been a busy week! I started last week talking to a group of developers in North Carolina, then gave a VJUG presentation with Matt Raible in San Francisco, then spoke to developers in Saint Louis, then flew to New York City to shoot a video on continuous delivery for three days in a hot studio (over the weekend no less!) and now as I wing back to San Francisco I look forward to spending a blissful 14 hours on the ground before I’m off to Asia (Hangzhou, Shanghai, Beijing, Shenzhen, Hong Kong, and Singapore) for about four weeks! I’m not the only who’s been busy, though! As usual, we’ve got a lot to cover this week so let’s get to it!
My friend and Spring Framework lead Juergen Hoeller gave a talk introducing reactive programming with Spring at Devoxx PL 2017. I hope you’ll watch this one, if you watch anything.
My buddy Matt Raible and I did a presentation last week that looked at building progressive web applications and robust backend services with Angular and Spring Boot. Matt and I have given this talk a few times and it’s always fun. We do the talk live. I write the backend services and he writes the frontend client. I write the backend service using Apache Groovy, Kotlin and Java. He uses TypeScript in the frontend. I think Matt’s the real hero here, of course, because even though I wrote 3 services, Matt ended up writing reams more TypeScript to get a client working! :D This video was crazy fun. I hope you’ll check it out.
Cloud Native Java is finally done and shipping! My friend Kenny Bastani and I wrote a little book for O’Reilly - Cloud Native Java - on how to build cloud native Java applications in terms of Spring Boot, Spring Cloud and Cloud Foundry. The book took us two years, has been reviewed a zillion different ways by folks on the Spring team, has forwards by Spring creator Rod Johnson and Cloud Foundry legend James Watters. It’s not the worst book that you could buy, and I hope you’ll consider it. Thanks so much for your patience, Spring fans! :-)
SpringOne Platform 2017, held in the Moscone center in beautiful San Francisco, CA, is in four short months! I’m going and I hope you will too. If you need more convincing, read this. If you’re already convinced then click that link for the ridiculous animated .gif that the marketing team put together!
I am absolutely loving the Spring Framework 5 reference documentation
I liked this pull-request. It’s by no means a definitive look at what will be supported or not supported, but the comments are interesting. It looks at what Spring Boot 2 might support HTTP/2 by default. Perhaps it’s a Java 9-only feature? Maybe there’s an appetite to explore some of the truly wretched options required to make it work on Java 8? If you have ideas or want to learn more, check out this issue!
Have you seen the new Spring Getting Started guide on messaging with Google Cloud Pub/Sub?
This Codecentric post looks at how to parse Java 8 LocalDate query parameters with a given date format.
Matthew Casperson looks at adding Spring Security to a Spring Boot-based project. Short and sweet - just the way it should be! Nice job Matthew!
This Dzone RefCard is a pretty good introduction to using Google Cloud. I have really grown to like Google Cloud - it provides a lot of business-differentiating functionality all while being an amazing place to run Cloud Foundry.
My friend John Willis looks at different models - PDCA and OODA - for organizational orientation; how to figure out what to do next based on what’s happened. This has nothing to do with Spring, per se, and everything with building the right thing (with Spring).
This week I spent a few days in studio shooting more content - this time looking at continuous delivery in terms of the Spring and Pivotal ecosystems - with my friend (and Pivotal’s resident continuous delivery mad-scientist) Marcin Grzejszczak. All this to say we spend a non-negative number of minutes dissecting JSON Path in the video and it seemed a propos to remind folks of the JSON Path project itself and this post introducing JSON Path from the Baeldung blog.
The Okta blog is on fire since the Stormpath team-meld! So much great content, seemingly every day! Here’s a nice post on securing Spring Boot applications with Apache Shiro, for those that do that sort of thing..
Also from the Okta blog this last week, Matt Raible’s epic post that looks at how to secure Spring Boot and Spring Cloud microservices using JWTs, Juiser and Okta. Nice job Matt!
Congratulations to the Reactive Streams teams who just last week announced that Reactive Streams 1.0.1 is here!
Auth0’s security with Spring Boot game is pretty on point, too! This week they released a useful look at securing Spring Boot applications with JSON Web Tokens (JWTs). Nice job!
Atomist co-founder Russ Miles looks at their collaboration tool’s ability to smoothly support a pull-request workflow. They do so in the context of a application (which happens to be written in Spring Boot) and while referencing Spring Boot in a post isn’t in of itself normally enough to be worthy of inclusion in these humble paragraphs, Atomist is generally so cool I’ll make an exception!
Congratulations to the Kotlin team at JetBrains on the new Kotlin 1.2.M2 release looks terrific. It includes new APIs supporting mathematics that work in a uniform way across the JVM and JavaScript runtimes for Kotlin. Now’s a good time to kick the tires and try the new features, perhaps using the Spring Boot Initializr?
Redmonk have a great post on Spring Boot users New Relic and the Tesla - in the field who’ve recently published their use.
The YouTube playlist for the Seoul, Korea-based Spring Camp event and all of its wondedrful Pivotal and Spring-centric content (in Koean!) is now available. This is a wonderful resource for Korean speakers!
This Portuguese-language book on Spring Boot - Spring Boot: Acelere o desenvolvimento de microsserviços looks like it could be a good read.
Bernd Rücker from the Camunda BPM team have put out a very cool exammple of integrating Camunda BPM with Spring Boot in a distributed application. The README is almost as interesting as the code itself, too. I love the discussion of testing which is something that’s typically missing from higher-level tools like workflow engines.
