### System Design Bytes for Enthusiasts

![System Design Discussions](https://raw.githubusercontent.com/codersguild/System-Design/master/system-design.PNG)

I complied and collected some of the articles as a part of doing **CS654A** course at **IIT Kanpur** for a fantastic course on **Advanced Software Architecture** taught by [*Prof.Dr.T.V.Prabbhakar*](https://www.iitk.ac.in/new/index.php/dr-tadinada-venkata-prabhakar).

Modified from [Zach](https://github.com/checkcheckzz) system design repository. Added more links and topics to cover on both PS/DS & System Design Interviews. We will keep updating this posting from time to time. Some more [awesome resource](https://github.com/binhnguyennus/awesome-scalability)

[![How to "think" (and design) like a Software Architect at Silicon Valley Code Camp 2019](https://img.youtube.com/vi/mCM6QVHD08c/0.jpg)](https://www.youtube.com/watch?v=mCM6QVHD08c)

[![Visualising software architecture with the C4 model - Simon Brown, Agile on the Beach 2019](https://img.youtube.com/vi/x2-rSnhpw0g/0.jpg)](https://www.youtube.com/watch?v=x2-rSnhpw0g)

## `SYSTEM DESIGN IS NOT JUST FOR INTERVIEWS, IT CAN BE HOW YOU MANAGE YOUR LIFE. GIVE IT A THOUGHT`

## Disclaimer/Acknowledgements

I didn't write the `articles` myself. I love expanding my understanding of `system design` complexities and thus read many books, research papers, and articles that enhance my knowledge. I take the opportunity to thank everyone who found this repository useful. I would like to thank all the authors and developers who wrote the articles aggregated in this repository.

## More Content Comming !

We are working to create good content to fulfil the needs of system-design noobs. Please feel free to share any resource or material at ```lahiri.devs@gmail.com```.

- [How Slack Works](https://www.youtube.com/watch?v=WE9c9AZe-DY)

## SWEBOOK & PDFs

- http://swebokwiki.org
- https://cs.fit.edu/~kgallagher/Schtick/Serious/SWEBOKv3.pdf
- [System Design Basics by Aditya Malshikhare](https://www.linkedin.com/feed/update/urn:li:activity:6881853381657321472/?commentUrn=urn%3Ali%3Acomment%3A(ugcPost%3A6881853381124636672%2C6881999479675908096))

## All-Time Favourites

* [http://highscalability.com/all-time-favorites/](http://highscalability.com/all-time-favorites/)
* [Software Engineering Daily](https://softwareengineeringdaily.com/)

## How to prepare system design questions?

System design is a very broad topic. Even a software engineer with many years of working experience at a top IT company may not be an expert on system design. If you want to become an expert, you need to read many books, articles, and solve real large scale system design problems.

In order to practice designing a few systems, for the love or learning or preparing for interviews, you can use this [practice platform](https://workat.tech/system-design/practice).

This repository only teaches you how to handle the system design interview with a systematic approach in a concise way. You can dive into each topic if you have time. Of course, welcome to add your thoughts!.

## <a name='toc'>Table of Contents</a>
- [ ] [System Design Interview Tips & PS/DS](#tips)
- [ ] [Basic Knowledge about System Design](#intro)
- [ ] [Company Engineering Blogs](#blog)
- [ ] [Products and Systems](#system)
- [ ] [Hot Questions and Reference](#qs)
- [ ] [Good Books](#bk)
- [ ] [Object Oriented Design](#ood)
- [ ] [Distributed System Design](#dsd)
- [ ] [Projects to Try](#prjt)

### [[⬆]](#toc) <a name='tips'>System Design Interview Tips & PS/DS</a>

**Clarify the constraints and identify the user cases**

Spend a few minutes questioning the interviewer and agreeing on the scope of the system.
Remember to make sure you know all the requirements the interviewer didn't tell you about in the beginning.

User cases indicate the main functions of the system, and constraints list the scale of the system such as requests 
per second, requests types, data written per second, data read per second.

In a real world scenario, beyond a white-board interview setting one must understand the `functional` & `non-functional` requirements of an 
engineering project. 

- [Requirements Engineering](https://medium.com/omarelgabrys-blog/requirements-engineering-introduction-part-1-6d49001526d3)
- [How to manage Modern Software Projects ?](https://medium.com/@lizparody/waterfall-vs-agile-methodology-in-software-development-1e19ef168cf6)
- [A Design Doc : Online Judge (https://www.youtube.com/watch?v=_eRTl_YxgUw)](https://docs.google.com/document/d/1MgoMz8McpZAmAq_hJfn1topocHqfmAhcbqq42zJEMsY/edit)
- [*Important* Data Engineering](https://www.dremio.com/data-lake/data-engineering/)

**High-level architecture design**

Sketch the important components and the connections between them, but don't go into some details. 
Usually, a scalable system includes webserver (load balancer), service (service partition), database (primary/secondary database cluster plug cache).
 
**Component design**

For each component, you need to write the specific APIs for each component. You may need to finish
the detailed OOD design for a particular function. You may also need to design the database schema for the database.

**Revist Basic PS/DS & Machine Coding Questions**

Basics of OOPs, SOLID Concepts, algorithms and data structures will help a lot in clearing most tof the onsite interviews at large tech companies. Having a habit of solving problems on LeetCode or CodeFoces will definitely help in thinking faster and better in terms of approach to problem solving. 

* [What is PS/DS?](https://workat.tech/problem-solving/article/what-is-ps-ds-coding-round-efuatnl7zxju)
* [What is Machine Coding?](https://workat.tech/machine-coding/article/what-is-a-machine-coding-round-omfn1w54ojlg)
* [How to practice for Machine Coding?](https://workat.tech/machine-coding/article/how-to-practice-for-machine-coding-kp0oj3sw2jca)
* [Sample Machine Coding Problems](https://workat.tech/practice)
* [LeetCode Problems](https://leetcode.com/problemset/all/)
* [Try the CodeChef Medium Problems](https://www.codechef.com/problems/medium)
* [Try this as well](https://www.algoexpert.io/product)

### [[⬆]](#toc) <a name='intro'>Basic Knowledge about System Design:</a>

Here are some articles about system design related topics.  

* [Chaos Engineering](https://principlesofchaos.org/)
* [The New Stack Blogs](https://thenewstack.io/)
* [An Illustrated Proof of the CAP Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
* [Educative.io & Other Lists](https://www.8bitmen.com/best-resources-to-learn-software-architecture-system-design/)
* [Node Clean Architecture](https://medium.com/better-programming/node-clean-architecture-deep-dive-ab68e523554b)
* [Services Engineering Resources](https://github.com/mmcgrana/services-engineering)
* [How to Rock a Systems Design Interview](http://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
* [System Interview](http://www.hiredintech.com/app#system-design)
* [SE Daily : Fiverr Engineering with Gil Sheinfeld](https://softwareengineeringdaily.com/2017/11/15/fiverr-engineering-with-gil-scheinfeld/)
* [Scalability for Dummies](http://www.lecloud.net/tagged/scalability)
* [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html)
* [Numbers Everyone Should Know](http://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
* [Fallacies of distributed systems](https://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf)
* [Designing Tinder](http://highscalability.com/blog/2022/1/17/designing-tinder.html)
* [Scalable System Design Patterns](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
* [Introduction to Architecting Systems for Scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
* [Transactions Across Datacenters](http://snarfed.org/transactions_across_datacenters_io.html)
* [A Plain English Introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem/)
* [The CAP FAQ](https://github.com/henryr/cap-faq)
* [Paxos Made Simple](http://research.microsoft.com/en-us/um/people/lamport/pubs/paxos-simple.pdf)
* [Simple : Consistent Hashing](https://medium.com/omarelgabrys-blog/consistent-hashing-beyond-the-basics-525304a12ba)
* [More On : Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
* [NOSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
* [Emerging Architectures](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/)
* [Scalability, Availability & Stability Patterns](http://www.slideshare.net/jboner/scalability-availability-stability-patterns)
* [Simple Publisher-Subscriber design for Koinex : PushMan](https://medium.com/koinex-crunch/pushman-the-koinex-standard-for-realtime-experience-4122d2715c92)
* [Web Architecture 101](https://engineering.videoblocks.com/web-architecture-101-a3224e126947)
* [Testing in Production: the hard parts](https://medium.com/@copyconstruct/testing-in-production-the-hard-parts-3f06cefaf592)
* [Distributed Tracing — we’ve been doing it wrong](https://medium.com/@copyconstruct/distributed-tracing-weve-been-doing-it-wrong-39fc92a857df)
* [Distributed Consistent Hashing](https://medium.com/ably-realtime/how-to-implement-consistent-hashing-efficiently-fe038d59fff2)
* [System Design White Board](https://www.youtube.com/channel/UCRPMAqdtSgd0Ipeef7iFsKw)
* [Bloom Filter : A Probabilistic Data Structure](https://medium.com/system-design-blog/bloom-filter-a-probabilistic-data-structure-12e4e5cf0638)
* [Basics :  ML Architecture](https://www.bmc.com/blogs/machine-learning-architecture)
* [Security By Design](https://blog.threatpress.com/security-design-principles-owasp/)
* [How Netlify’s deploying and routing infrastructure works](https://medium.com/netlify/how-netlifys-deploying-and-routing-infrastructure-works-c90adbde3b8d)
* [Basic Overview of Blockchain](https://www.edureka.co/blog/blockchain-architecture/)
* [Architecting a Machine Learning Pipeline](https://towardsdatascience.com/architecting-a-machine-learning-pipeline-a847f094d1c7)
* [ML Reference Architecture](https://freeandopenmachinelearning.readthedocs.io/en/latest/architecture.html)
* [Reducing Databse Costs](https://scalegrid.io/blog/reducing-your-database-hosting-costs-digitalocean-vs-aws-vs-azure/)
* [Patterns : Thinking About Microservices](https://www.infoq.com/articles/microservices-design-ideals/?itm_source=infoq&itm_medium=popular_widget&itm_campaign=popular_content_list&itm_content=)
* [The Reactive Monolith - How to Move from CRUD to Event Sourcing](https://www.wix.engineering/post/the-reactive-monolith-how-to-move-from-crud-to-event-sourcing)
* [Terraform Software](https://www.terraform.io/)
* [FreeCodeCamp : DevOps Course](https://www.youtube.com/watch?v=j5Zsa_eOXeY)
* [Some Linux Know How is necessary](https://training.linuxfoundation.org/training/linux-kernel-internals-and-development/)
* [Architecture of Open Source Systems](http://aosabook.org/en/index.html)
* [Some Quickstart ML know-how for system design : What to use? Where to use it?](https://youtu.be/VyWAvY2CF9c)
* [Quick : Observability and Microservices](https://www.infoq.com/news/2018/06/observability-microservices/)
* [System Design Interviews](https://www.youtube.com/channel/UC9vLsnF6QPYuH51njmIooCQ)
* [Designing Microservices](https://www.youtube.com/watch?v=j6ow-UemzBc)
* [Crack the System Design Interview - FreeCodeCamp](https://www.freecodecamp.org/news/how-to-system-design-dda63ed27e26/)
* [Intro to Distributed Logging](https://blog.treasuredata.com/blog/2016/08/03/distributed-logging-architecture-in-the-container-era/)
* [Usenix -- Gmail Overview](https://www.usenix.org/legacy/event/webapps10/tech/slides/deboor.pdf)
* [Jeff Dean On Large-Scale Deep Learning At Google](http://highscalability.com/blog/2016/3/16/jeff-dean-on-large-scale-deep-learning-at-google.html)
* [Infinite Memory Transformer: Attending to Arbitrarily Long Contexts Without Increasing Computation Burden
Researchers from Instituto de Telecomunicações.](https://syncedreview.com/2021/09/09/deepmind-podracer-tpu-based-rl-frameworks-deliver-exceptional-performance-at-low-cost-100/)

Of course, if you want to dive into system related topics, here is a good collection of reading list about [services-engineering](https://github.com/mmcgrana/services-engineering), and
a good collection of material about [distributed systems](http://dancres.github.io/Pages/).

### [[⬆]](#toc) <a name='blog'>Off-topic Blogs:</a>

* [Architecture of Machine Learning Systems](https://medium.com/louis-dorard/architecture-of-a-real-world-machine-learning-system-795254bec646)
* [Engineering Dependability And Fault Tolerance In A Distributed System - @@Ably](http://highscalability.com/blog/2021/2/19/engineering-dependability-and-fault-tolerance-in-a-distribut.html)
* [Postman API Testing](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
* [Microservices and the Economics of Small Things](https://www.infoq.com/articles/microservices-economics-small-things/?topicPageSponsorship=62547418-6220-4c74-9be8-b11f14b85016&itm_source=articles_about_scalability&itm_medium=link&itm_campaign=scalability)
* [Service Mesh Ultimate Guide - Second Edition: Next Generation Microservices Development](https://www.infoq.com/articles/service-mesh-ultimate-guide-2e/?itm_campaign=rightbar_v2&itm_source=infoq&itm_medium=articles_link&itm_content=link_text)
* [Adoption of Cloud Native Architecture, Part 3: Service Orchestration and Service Mesh](https://www.infoq.com/articles/cloud-native-architecture-adoption-part3/?itm_campaign=rightbar_v2&itm_source=infoq&itm_medium=articles_link&itm_content=link_text)

### [[⬆]](#toc) <a name='blog'>Company Engineering Blogs:</a>

If you are going to have an onsite with a company, you should read their engineering blog. 

* [InfoQ](https://www.infoq.com/)
* [High Scalability](http://highscalability.com/)
* [Complex Systems: Microservices and Humans](https://www.youtube.com/watch?v=E8A3Yn2Vjx8)
* [The GitHub Blog](https://github.com/blog/category/engineering)
* [Engineering at Quora](http://engineering.quora.com/)
* [Yelp Engineering Blog](http://engineeringblog.yelp.com/)
* [Twitter Engineering](https://engineering.twitter.com/)
* [Facebook Engineering](https://www.facebook.com/Engineering)
* [Yammer Engineering](http://eng.yammer.com/blog/)
* [Etsy Code as Craft](http://codeascraft.com/)
* [Foursquare Engineering Blog](http://engineering.foursquare.com/)
* [Airbnb Engineering](http://nerds.airbnb.com/)
* [WebEngage Engineering Blog](http://engineering.webengage.com/)
* [LinkedIn Engineering](http://engineering.linkedin.com/blog)
* [The Netflix Tech Blog](http://techblog.netflix.com/)
* [BankSimple Simple Blog](https://www.simple.com/engineering/)
* [Square The Corner](http://corner.squareup.com/)
* [SoundCloud Backstage Blog](https://developers.soundcloud.com/blog/)
* [Flickr Code](http://code.flickr.net/)
* [Instagram Engineering](http://instagram-engineering.tumblr.com/)
* [Dropbox Tech Blog](https://tech.dropbox.com/)
* [Cloudera Developer Blog](http://blog.cloudera.com/)
* [Bandcamp Tech](http://bandcamptech.wordpress.com/)
* [Oyster Tech Blog](http://tech.oyster.com/)
* [THE REDDIT BLOG](http://www.redditblog.com/)
* [Groupon Engineering Blog](https://engineering.groupon.com/)
* [Songkick Technology Blog](http://devblog.songkick.com/)
* [Google Research Blog](http://googleresearch.blogspot.com/)
* [Pinterest Engineering Blog](http://engineering.pinterest.com/)
* [Twilio Engineering Blog](http://www.twilio.com/engineering)
* [Bitly Engineering Blog](http://word.bitly.com/)
* [Uber Engineering Blog ](https://eng.uber.com/)
* [Godaddy Engineering](http://engineering.godaddy.com/)
* [Splunk Blog](http://blogs.splunk.com/)
* [Coursera Engineering Blog](https://building.coursera.org/)
* [PayPal Engineering Blog](https://www.paypal-engineering.com/)
* [Nextdoor Engineering Blog](https://engblog.nextdoor.com/)
* [Booking.com Development Blog](https://blog.booking.com/)
* [Scalyr Engineering Blog ](https://blog.scalyr.com/)
* [Architect.io Blog](https://www.architect.io/blog)
* [Ably Engineering Blog](https://ably.com/blog)
* [DoorDash Engineering Blog](https://doordash.engineering/blog/)

### [[⬆]](#toc) <a name='system'>Products and Systems:</a>

The following papers/articles/slides can help you to understand the general design idea of different real products and systems. 

* [MapReduce: Simplied Data Processing on Large Clusters](http://static.googleusercontent.com/media/research.google.com/zh-CN/us/archive/mapreduce-osdi04.pdf)
* [Bigtable: A Distributed Storage System for Structured Data](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/chang06bigtable.pdf)
* [The Google File System](http://static.googleusercontent.com/media/research.google.com/zh-CN/us/archive/gfs-sosp2003.pdf)
* [The Chubby lock service for loosely-coupled distributed systems](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en/us/archive/chubby-osdi06.pdf)
* [Dynamo: Amazon's Highly Available Key-value Store](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf)
* [Frontend in React](https://reactjs.org/tutorial/tutorial.html)
* [State Management using Redux](https://redux.js.org/introduction/getting-started)
* [Angular Get Started](https://angular.io/start)
* [First DJango App](https://docs.djangoproject.com/en/3.0/intro/tutorial01/)
* [Build a CRUD Todo app with Django and React/Redux](https://medium.com/technest/build-a-crud-todo-app-with-django-and-react-redux-8ddb0b6ac2f0)
* [The MERN Stack Tutorial – Building A React CRUD Application From Start To Finish](https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/)
* [Introduction to Memcached](http://www.slideshare.net/oemebamo/introduction-to-memcached)
* [Cassandra Introduction Features](http://www.slideshare.net/planetcassandra/cassandra-introduction-features-30103666)
* [Introduction to HBase](http://www.slideshare.net/alexbaranau/intro-to-hbase)
* [Introduction to MongoDB](http://www.slideshare.net/mdirolf/introduction-to-mongodb)
* [Introduction to Redis](http://www.slideshare.net/dvirsky/introduction-to-redis)
* [Storm](http://www.slideshare.net/previa/storm-16094009)
* [Introduction to Zookeeper](http://www.slideshare.net/sauravhaloi/introduction-to-apache-zookeeper)
* [Kafka](http://www.slideshare.net/mumrah/kafka-talk-tri-hug)
* [YouTube Architecture](http://highscalability.com/youtube-architecture)
* [Scaling Pinterest](http://highscalability.com/blog/2013/4/15/scaling-pinterest-from-0-to-10s-of-billions-of-page-views-a.html)
* [Google Architecture](http://highscalability.com/google-architecture)
* [Scaling Twitter](http://highscalability.com/scaling-twitter-making-twitter-10000-percent-faster)
* [The WhatsApp Architecture](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)
* [Flickr Architecture](http://highscalability.com/flickr-architecture)
* [Amazon Architecture](http://highscalability.com/amazon-architecture)
* [Stack Overflow Architecture](http://highscalability.com/blog/2009/8/5/stack-overflow-architecture.html)
* [Pinterest Architecture](http://highscalability.com/blog/2012/5/21/pinterest-architecture-update-18-million-visitors-10x-growth.html)
* [Tumblr Architecture](http://highscalability.com/blog/2012/2/13/tumblr-architecture-15-billion-page-views-a-month-and-harder.html)
* [Instagram Architecture](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
* [TripAdvisor Architecture](http://highscalability.com/blog/2011/6/27/tripadvisor-architecture-40m-visitors-200m-dynamic-page-view.html)
* [Scaling Mailbox](http://highscalability.com/blog/2013/6/18/scaling-mailbox-from-0-to-one-million-users-in-6-weeks-and-1.html)
* [Salesforce Architecture ](http://highscalability.com/blog/2013/9/23/salesforce-architecture-how-they-handle-13-billion-transacti.html)
* [ESPN Architecture](http://highscalability.com/blog/2013/11/4/espns-architecture-at-scale-operating-at-100000-duh-nuh-nuhs.html)
* [Uber Architecture](http://highscalability.com/blog/2015/9/14/how-uber-scales-their-real-time-market-platform.html)
* [DropBox Design](https://www.youtube.com/watch?v=PE4gwstWhmc)
* [Splunk Architecture](http://www.splunk.com/view/SP-CAAABF9)
* [Good Parts of AWS](https://www.educative.io/courses/good-parts-of-aws?aid=5082902844932096)
* [Azure DataCenter Architecture](https://youtu.be/69PrhWQorEM)
* [Evolution Of Search Engines Architecture - Highscalability](http://highscalability.com/blog/2021/8/2/evolution-of-search-engines-architecture-algolia-new-search.html)

## Trends

- [Emerging Trends in Software Architecture](https://www.oreilly.com/library/view/software-architecture-a/9788131707494/ch07.html)
- [Software Architecture and Design InfoQ Trends Report—April 2020](https://www.infoq.com/articles/architecture-trends-2020/)

### [[⬆]](#toc) <a name='qs'>Hot Questions and Reference:</a>

There are some good references for each question. The references here are slides and articles. 

**Design a CDN network**  
Reference:  
* [Globally Distributed Content Delivery](http://repository.cmu.edu/cgi/viewcontent.cgi?article=2112&context=compsci)

**Design a Google document system**  
Reference:  
* [google-mobwrite](https://code.google.com/p/google-mobwrite/)
* [Differential Synchronization](https://neil.fraser.name/writing/sync/)

**Design a random ID generation system**  
Reference: 
* [Announcing Snowflake](https://blog.twitter.com/2010/announcing-snowflake) 
* [snowflake](https://github.com/twitter/snowflake/)

**Design a key-value database**  
Reference:   
* [Introduction to Redis](http://www.slideshare.net/dvirsky/introduction-to-redis)
* [Introduction to Memcached](https://medium.com/swlh/what-is-memcached-d1498623db3b)

**Design the Facebook news feed function**   
Reference:   
* [Deisgn a News Feed System](https://medium.com/@bansal_ankur/design-a-news-feed-system-6bf42e9f03fb)
* [What are best practices for building something like a News Feed?](http://www.quora.com/What-are-best-practices-for-building-something-like-a-News-Feed) 
* [What are the scaling issues to keep in mind while developing a social network feed?](http://www.quora.com/Activity-Streams/What-are-the-scaling-issues-to-keep-in-mind-while-developing-a-social-network-feed) 
* [Activity Feeds Architecture](http://www.slideshare.net/danmckinley/etsy-activity-feeds-architecture)

**Design the Facebook timeline function**   
Reference: 
* [Building Timeline](https://www.facebook.com/note.php?note_id=10150468255628920) 
* [Facebook Timeline](http://highscalability.com/blog/2012/1/23/facebook-timeline-brought-to-you-by-the-power-of-denormaliza.html)
* [Facebook System Design](https://www.codekarle.com/system-design/facebook-system-design.html)

**Design a function to return the top k requests during past time interval**   
Reference:  
* [Efficient Computation of Frequent and Top-k Elements in Data Streams](http://www.cse.ust.hk/~raywong/comp5331/References/EfficientComputationOfFrequentAndTop-kElementsInDataStreams.pdf)
* [An Optimal Strategy for Monitoring Top-k Queries in Streaming Windows](http://davis.wpi.edu/xmdv/docs/EDBT11-diyang.pdf)

**Design an online multiplayer card game**   
Reference:  
* [How to Create an Asynchronous Multiplayer Game](http://www.indieflashblog.com/how-to-create-an-asynchronous-multiplayer-game.html)   
* [How to Create an Asynchronous Multiplayer Game Part 2: Saving the Game State to Online Database](http://www.indieflashblog.com/how-to-create-async-part2.html)  
* [How to Create an Asynchronous Multiplayer Game Part 3: Loading Games from the Database](http://www.indieflashblog.com/how-to-create-async-part3.html)  
* [How to Create an Asynchronous Multiplayer Game Part 4: Matchmaking](http://www.indieflashblog.com/how-to-create-async-part4-html.html#comment-4447)  
* [Real Time Multiplayer in HTML5](http://buildnewgames.com/real-time-multiplayer/)  

**Design a graph search function**   
Reference:   
* [Building out the infrastructure for Graph Search](https://www.facebook.com/notes/facebook-engineering/under-the-hood-building-out-the-infrastructure-for-graph-search/10151347573598920)
* [Indexing and ranking in Graph Search](https://www.facebook.com/notes/facebook-engineering/under-the-hood-indexing-and-ranking-in-graph-search/10151361720763920) 
* [The natural language interface of Graph Search](https://www.facebook.com/notes/facebook-engineering/under-the-hood-the-natural-language-interface-of-graph-search/10151432733048920) and [Erlang at Facebook](http://www.erlang-factory.com/upload/presentations/31/EugeneLetuchy-ErlangatFacebook.pdf)

**Design a picture sharing system**   
Reference:   
* [Flickr Architecture](http://highscalability.com/flickr-architecture) 
* [Instagram Architecture](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)

**Design a search engine**   
Reference:  
* [How would you implement Google Search?](http://programmers.stackexchange.com/questions/38324/interview-question-how-would-you-implement-google-search)  
* [Implementing Search Engines](http://www.ardendertat.com/2012/01/11/implementing-search-engines/)

**Design a recommendation system**  
Reference:  
* [Hulu’s Recommendation System](http://tech.hulu.com/blog/2011/09/19/recommendation-system.html)  
* [Recommender Systems](http://ijcai13.org/files/tutorial_slides/td3.pdf)

**Design a tinyurl system**    
Reference: 
* [System Design for Big Data-tinyurl](http://n00tc0d3r.blogspot.com/) 
* [URL Shortener API](https://developers.google.com/url-shortener/?csw=1)
* [Tiny URL System Design](https://www.youtube.com/watch?v=AVztRY77xxA)

**Design a garbage collection system**    
Reference:   
* [Baby's First Garbage Collector](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/)
 
**Design a scalable web crawling system**    
Reference:  
* [How can I build a web crawler from scratch?](https://www.quora.com/How-can-I-build-a-web-crawler-from-scratch)

**Design the Facebook chat function**    
Reference:   
* [Erlang at Facebook](http://www.erlang-factory.com/upload/presentations/31/EugeneLetuchy-ErlangatFacebook.pdf)  
* [Facebook Chat](https://www.facebook.com/note.php?note_id=14218138919&id=9445547199&index=0)
* [Facebook Messenger/Whatsapp System Design](https://www.youtube.com/watch?v=RjQjbJ2UJDg)

**Design a micro blogging site**    
Reference:   
* [Twitter System Design](https://www.youtube.com/watch?v=EkudBdvbDhs)


**Design hotel booking platform**    
Reference:   
* [AirBNB/Booking.com System Design](https://www.youtube.com/watch?v=YyOXt2MEkv4)

**Design a trending topic system**    
Reference:  
* [Implementing Real-Time Trending Topics With a Distributed Rolling Count Algorithm in Storm](http://www.michael-noll.com/blog/2013/01/18/implementing-real-time-trending-topics-in-storm/)   
* [Early detection of Twitter trends explained](http://snikolov.wordpress.com/2012/11/14/early-detection-of-twitter-trends/)
 
**Design a cache system**    
Reference:   
* [Introduction to Memcached](http://www.slideshare.net/oemebamo/introduction-to-memcached)

**Design LeetCode**
- [Youtube Link-1 : Gaurav Sen](https://www.youtube.com/watch?v=eg0nlYcbLpo)
- [Youtube Link-2](https://www.youtube.com/watch?v=cMH2aa0xNYQ)

**Design a Payment System**
* [Digital Wallet Design](https://techwithkp.com/digital-wallet-design-machine-coding-round-solution/)



**Basic SRE**
Reference:
* [How Google Runs Production Systems?](https://landing.google.com/sre/)

**Design a React Native Application**
Reference : 
* [Facebook F8 App](https://makeitopen.com/)

**Numbers from concerte implementations**
References : 
* [DB Comparisions](http://highscalability.com/blog/2021/2/17/benchmark-ycsb-numbers-for-redis-mongodb-couchbase2-yugabyte.html)

### [[⬆]](#toc) <a name='bk'>Good Books:</a>

* [Big Data: Principles and best practices of scalable realtime data systems](http://www.amazon.com/Big-Data-Principles-practices-scalable/dp/1617290343)
* [Real-Time Analytics: Techniques to Analyze and Visualize Streaming Data](http://www.amazon.com/Real-Time-Analytics-Techniques-Visualize-Streaming/dp/1118837916)
* [Building Microservices: Designing Fine-Grained Systems](http://www.amazon.com/Building-Microservices-Sam-Newman/dp/1491950358)
* [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
* [Site Reliability Engineering - How Google Runs Production Systems  (English, Paperback, Beyer Betsy)](https://www.amazon.in/Site-Reliability-Engineering-Betsy-Beyer/dp/149192912X)

### [[⬆]](#toc) <a name='ood'>Object Oriented Design:</a>

#### Tips for OOD Interview

**Clarify the scenario, write out user cases**

Use case is a description of sequences of events that, taken together, lead to a system doing something useful. Who is going to use it and how they are going to use it. The system may be very simple or very complicated.

Special system requirements such as multi-threading, read or write oriented.

**Define objects**

Map identity to class: one scenario for one class, each core object in this scenario for one class.

Consider the relationships among classes: certain class must have unique instance, one object has many other objects (composition), one object is another object (inheritance).

Identify attributes for each class: change noun to variable and action to methods.

Use design patterns such that it can be reused in multiple applications.

#### Useful Websites

* [101 Design Patterns & Tips for Developers](http://sourcemaking.com/design-patterns-and-tips)
* [A Solid Guide to SOLID Principles](https://www.baeldung.com/solid-principles)
* [SOLID Design Principles Explained](https://stackify.com/solid-design-principles/)
* [SOLID Principles made easy](https://hackernoon.com/solid-principles-made-easy-67b1246bcdf)
* [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw)
* [Common System Design Interview Questions](https://www.codekarle.com/)

### [[⬆]](#toc) <a name='dsd'>Distributed System Design :</a>

#### Distributed System Design

* [Basics of Lamport Clocks](https://medium.com/@balrajasubbiah/lamport-clocks-and-vector-clocks-b713db1890d7)
* [Distributed Consensus : RAFT](http://thesecretlivesofdata.com/raft/)
* [Distributed Consensus : PAXOS](https://medium.com/@logeshrajendran/paxos-a9d76ebf04f3)
* [Two Generals Problem](https://www.youtube.com/watch?v=IP-rGJKSZ3s)

### [[⬆]](#toc) <a name='prjt'>Projects to try :</a>

* [Projects to try](https://web.eecs.utk.edu/~azh/blog/morechallengingprojects.html)

#### Misc 

* [Scale like a Pro](https://medium.com/swlh/how-i-scaled-a-software-systems-performance-by-35-000-6dacd63732df)
* [GoLang to Node.Js](https://medium.com/thecobbles/why-we-moved-from-golang-to-nodejs-cecf66a47740)
* [Documenting Software Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
* [Choosing the correct storage solutions](https://www.codekarle.com/system-design/Database-system-design.html)

#### More Info

Feel free to contact [Sumit Lahiri](mailto:lahiri.devs@gmail.com) 
