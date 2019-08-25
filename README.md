# *Almost* every single day I read or watch something interesting

Inspired by [the list of Stéphane Derosiaux](https://github.com/sderosiaux/every-single-day-i-tldr), here I list all the articles, blog posts, pages I've read, or videos I've watched, that I found interesting.

I'm reading mostly about Kotlin, Kafka, Scala, Java, Big Data Engineering, DDD, and guitar/music/audio stuff. :nerd_face:

> Note: this is stuff I'm reading mostly off work of course. :see_no_evil: My current tech stack @ work is Kotlin, Java, Kafka, Spring, Reactor

# 25-08-2019
- Software Architecture Guide.   
  https://martinfowler.com/architecture/  & https://news.ycombinator.com/item?id=20786448
- The End of Agile.   
  https://www.forbes.com/sites/cognitiveworld/2019/08/23/the-end-of-agile/#d5488f220713
- Why Clojure?    
  https://blog.cleancoder.com/uncle-bob/2019/08/22/WhyClojure.html
- YAML: probably not so great after all.   
  https://arp242.net/yaml-config.html
  
# 24-08-2019
- Correctness Anomalies Under Serializable Isolation.   
  https://dbmsmusings.blogspot.com/2019/06/correctness-anomalies-under.html
- Overview of Consistency Levels in Database Systems
  https://dbmsmusings.blogspot.com/2019/07/overview-of-consistency-levels-in.html
- 10 Key Learnings in Rust after 30,000 Lines of Code.   
  https://medium.com/@jondot/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19

# 19-08-2019
- The traits of serverless architecture.   
  https://www.thoughtworks.com/insights/blog/traits-serverless-architecture
- How we built a tool for validating big data workflows.   
  https://engineering.klarna.com/how-we-built-a-tool-for-validating-big-data-workflows-170c196a4493

# 18-08-2019
- Yes silver bullet    
  Revisiting & arguing against "No Silver Bullet – Essence and Accident in Software Engineering", a widely discussed paper on software engineering written by Turing Award winner Fred Brooks in 1986.    
  "If the essential complexity is inherent, then you can't reduce the size of it. The only way to decrease the overall complexity is to reduce the accidental complexity.    
  There's no magical solution that will solve all problems with software development, but that doesn't mean that improvements can't be had."    
  Mark Seemann suggests to try to use better tools, from statically typed functional programming, to reduce the massive amounts of accidental complexity we still have.   
  https://blog.ploeh.dk/2019/07/01/yes-silver-bullet/

# 16-08-2019
- Kafka Connect Improvements in Apache Kafka 2.3.   
  https://www.confluent.io/blog/kafka-connect-improvements-in-apache-kafka-2-3
- Gathering WebRTC stats with gRPC.   
  https://medium.com/@aconchillo/gathering-webrtc-stats-with-grpc-a76d89dc618a

# 12-08-2019
- Monads as a Programming Pattern.   
  https://samgrayson.me/2019-08-06-monads-as-a-programming-pattern/

# 9-08-2019
- Working Backwards.   
  https://www.allthingsdistributed.com/2006/11/working_backwards.html

# 6-08-2019
- Stack Overflow: How We Do App Caching.   
  https://nickcraver.com/blog/2019/08/06/stack-overflow-how-we-do-app-caching/
- Why I love Trunk Based Development (or pushing straight to master)    
  https://medium.com/@mattia.battiston/why-i-love-trunk-based-development-641fcf0b94a0

# 4-08-2019
- KIP-500: Replace ZooKeeper with a Self-Managed Metadata Quorum.   
  https://cwiki.apache.org/confluence/display/KAFKA/KIP-500%3A+Replace+ZooKeeper+with+a+Self-Managed+Metadata+Quorum & https://news.ycombinator.com/item?id=20595194

# 3-08-2019
- Mitigating serverless lock-in fears: Use hexagonal architecture/ports & adaptors to mitigate risk around cloud-based lock-in at the application level.    
  https://www.thoughtworks.com/insights/blog/mitigating-serverless-lock-fears
- How to Build an Insurance Company: How to build payments for an insurance startup    
  https://www.moderntreasury.com/journal/how-to-build-an-insurance-company
- Some items from Rachel Kroll's "reliability list":
 
	- Rollbacks need to be possible.   
	- New states need to be forward compatible
	- More than one person should be able to ship
	- Using weak or ambiguous formats for storage will get us in trouble
	- There is far, far too much JSON
	- Use some kind of actual RPC mechanism
	   
  https://rachelbythebay.com/w/2019/07/21/reliability/ & https://news.ycombinator.com/item?id=20522868

# 2-08-2019
- Building Shared State Microservices for Distributed Systems Using Kafka Streams.   
  https://www.confluent.io/blog/building-shared-state-microservices-for-distributed-systems-using-kafka-streams

# 1-08-2019
- Exceptions and proxies and coroutines, oh my!    
  https://jakewharton.com/exceptions-and-proxies-and-coroutines-oh-my/
- How to run Flutter in the background?    
  https://medium.com/vrt-digital-studio/flutter-workmanager-81e0cfbd6f6e

# 30-07-2019
- Fast and flexible observability with canonical log lines.   
  https://stripe.com/gb/blog/canonical-log-lines

# 28-07-2019
- Fault Tolerance in Distributed Systems: Tracing with Apache Kafka and Jaeger.   
  https://www.confluent.io/blog/fault-tolerance-distributed-systems-tracing-with-apache-kafka-jaeger
- Building Kafka Streams applications with Quarkus and Eclipse MicroProfile.   
  https://quarkus.io/blog/kafka-streams-applications-with-quarkus-and-microprofile/

# 27-07-2019
- Cache me if you can: HTTP caching overview.   
  https://blog.octo.com/en/cache-me-if-you-can-2/

# 26-07-2019
How To Serve Machine Learning Models With Dynamically Controlled Streams in Cloud-Native Applications.    
https://www.lightbend.com/blog/serve-machine-learning-models-dynamically-controlled-streams    
All of the modern stream processing frameworks and engines, including [Akka Streams](https://doc.akka.io/docs/akka/2.5/stream/?_ga=2.87837720.1080481679.1564347590-1164336498.1511962281), [Kafka Streams](https://kafka.apache.org/documentation/streams/), [Flink](https://flink.apache.org/), and [Spark](https://spark.apache.org/) (frameworks discussed further) can be used for implementing dynamically controlled streams. 
The Lightbend Platform supports the integration with these various streaming engines.     
Four examples implemented:    

- How To Use Akka Streams For Dynamically Controlled Streams.   
  https://www.lightbend.com/blog/use-akka-streams-dynamically-controlled-streams
- How To Use Kafka Streams For Dynamically Controlled Streams.   
  https://www.lightbend.com/blog/use-kafka-streams-dynamically-controlled-streams
- How To Use Apache Flink For Dynamically Controlled Streams.   
  https://www.lightbend.com/blog/use-apache-flink-dynamically-controlled-streams
- How To Use Spark Streaming For Dynamically Controlled Streams.   
  https://www.lightbend.com/blog/use-spark-streaming-dynamically-controlled-streams

# 23-07-2019
- Kafka productivity hacks.   
  https://gist.github.com/MichaelDrogalis/08463ed82a4a04015eef03cb483cad26

# 22-07-2019
- Callbacks and Kotlin Flows.   
  https://medium.com/@elizarov/callbacks-and-kotlin-flows-2b53aa2525cf
- The future of AI is entertainment: How GANs may be combined to create the YouTube of tomorrow.   
  https://blog.plan99.net/the-future-of-ai-is-entertainment-1841fbb400df

# 17-07-2019
- Autoscaling Kafka Streams applications with Kubernetes.   
  https://blog.softwaremill.com/autoscaling-kafka-streams-applications-with-kubernetes-9aed2e37d3a0

# 16-07-2019
- Java frameworks performances on Cloud Run.   
  https://medium.com/google-cloud/java-frameworks-performances-on-cloud-run-eb243fd84a5c

# 15-07-2019
- Exceptions in Kotlin Flows.   
  https://medium.com/@elizarov/exceptions-in-kotlin-flows-b59643c940fb

# 14-07-2019
- "CRDTs Illustrated" by Arnout Engelen.   
  https://www.youtube.com/watch?v=9xFfOhasiOE 
- Why Kafka Connect? ft. Robin Moffatt.   
  https://www.buzzsprout.com/186154/1265780-why-kafka-connect-ft-robin-moffatt
- Deploying Confluent Platform, from Zero to Hero ft. Mitch Henderson.   
  https://www.buzzsprout.com/186154/1292998-deploying-confluent-platform-from-zero-to-hero-ft-mitch-henderson
- Kafka in Action with Dylan Scott.   
  https://www.buzzsprout.com/186154/1384408-kafka-in-action-with-dylan-scott
- Change Data Capture with Debezium ft. Gunnar Morling    
  https://www.buzzsprout.com/186154/1365043-change-data-capture-with-debezium-ft-gunnar-morling

# 03-07-2019
- 7 Reasons We Choose Apache Pulsar Over Apache Kafka: comparison Kafka - Pulsar.   
  https://kafkaesque.io/7-reasons-we-choose-apache-pulsar-over-apache-kafka/

# 30-06-2019
- The big interview with Martin Kleppmann: “Figuring out the future of distributed data systems”.   
  https://medium.com/@hydraconference/the-big-interview-with-martin-kleppmann-figuring-out-the-future-of-distributed-data-systems-28a680d99ae6

# 27-06-2019
- Comparing Ethereum and the Libra blockchain.   
  https://blog.softwaremill.com/comparing-ethereum-and-the-libra-blockchain-64bec7dd70c0

# 26-06-2019
- Microservices, Apache Kafka, and Domain-Driven Design.   
  https://www.confluent.io/blog/microservices-apache-kafka-domain-driven-design
- Application programming language.   
  https://medium.com/@elizarov/application-programming-language-ff7f0063c16

# 24-06-2019
- Fast key-value stores: An idea whose time has come and gone.   
  Reading this validates my interest in Akka even more: Akka provides an advanced system for stateful processes (communicating via message passing), that can seamlessly interoperate while running in a cluster, all with a strong focus on resiliency and fault tolerance.    
  https://ai.google/research/pubs/pub48030
- Startup idea checklist.   
  https://www.defmacro.org/2019/03/26/startup-checklist.html
- GraphQL Conf 2019 in a nutshell - Some Takeaways.   
  https://time2hack.com/2019/06/graphql-conf-2019-in-a-nutshell-some-takeaways/

# 23-06-2019
- API Gateways are going through an identity crisis.   
  https://medium.com/solo-io/api-gateways-are-going-through-an-identity-crisis-d1d833a313d7

# 20-06-2019
- Google Cloud networking in depth: Cloud CDN.   
  https://cloud.google.com/blog/products/networking/google-cloud-networking-in-depth-cloud-cdn
- Cloudflare's Ethereum Gateway.   
  https://blog.cloudflare.com/cloudflare-ethereum-gateway/
- The fourth Industrial revolution emerges from AI and the Internet of Things.   
  https://arstechnica.com/information-technology/2019/06/the-revolution-will-be-roboticized-how-ai-is-driving-industry-4-0/

# 18-06-2019
- Announcing Envoy Mobile.   
  https://eng.lyft.com/announcing-envoy-mobile-5c2067d9ade0
- CSV vs Parquet vs Avro: Choosing the Right Tool for the Right Job.   
  https://medium.com/ssense-tech/csv-vs-parquet-vs-avro-choosing-the-right-tool-for-the-right-job-79c9f56914a8

# 17-06-2019
- Let a 1,000 flowers bloom. Then rip 999 of them out by the roots.   
  *Tech debt is the mind killer. Tech debt is the lack of quality. It slows us down. It makes us miserable. It breaks our flow and saps our will to live.*    
  http://www.gigamonkeys.com/flowers/

# 15-06-2019
- Design Techniques for Building Streaming Data, Cloud-Native Applications: Managing Streaming And Queryable State In Spark, Akka Streams, Kafka Streams, And Flink.   
  https://www.lightbend.com/blog/managing-streaming-and-queryable-state-in-spark-akka-streams-kafka-streams-flink
- Making Direct Messages Reliable and Fast.   
  Somewhat similar architecture to the solution [@mikeseghers]( https://twitter.com/mikeseghers ) and I were exploring at a previous job (https://speakerdeck.com/filipmaelbrancke/common-mobile-architecture?slide=39). Nowadays I think I would rather look into eventually-consistent databases, or GraphQL, with a client that optimistically updates a client-side cache. The article very much feels like describing the client component of an eventually-consistent data store, but without touching the nitty-gritty details of causal consistency, vector clocks, etc...     
  https://instagram-engineering.com/making-direct-messages-reliable-and-fast-a152bdfd697f

# 13-06-2019
- Distributed Locks are Dead; Long Live Distributed Locks!    
  https://hazelcast.com/blog/long-live-distributed-locks/
- Redlock: Distributed locks with Redis.   
  https://redis.io/topics/distlock
- Martin Kleppmann criticizes Redlock, and mentions fencing: How to do distributed locking.   
  https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html
- Antirez (Salvatore Sanfilippo - Redis Creator) disagrees with the analysis: Is Redlock safe? + insightful discussion @ HN.   
  http://antirez.com/news/101 & https://news.ycombinator.com/item?id=11065933
- Redlock: unsafe at any time.   
  tl;dr redlock is ok for advisory locks but not for guaranteeing mutual exclusion.   
  https://medium.com/@talentdeficit/redlock-unsafe-at-any-time-40ceac109dbb

# 12-06-2019
- Backoff and Retry Error-Handling for Akka Streams.   
  https://blog.colinbreck.com/backoff-and-retry-error-handling-for-akka-streams/

# 11-06-2019
- Modern garbage collection.   
  A look at what the newest generation of Java GCs can do.   
  https://blog.plan99.net/modern-garbage-collection-part-2-1c88847abcfd

# 10-06-2019
- Abstracting Kotlin Sealed Classes.   
  https://arturdryomov.online/posts/abstracting-kotlin-sealed-classes/
  
# 09-06-2019
- Reactive Streams and Kotlin Flows.   
  https://medium.com/@elizarov/reactive-streams-and-kotlin-flows-bfd12772cda4
- Reactive Streams 1.0.0 interview (°2015).   
  https://medium.com/@viktorklang/reactive-streams-1-0-0-interview-faaca2c00bec

# 08-06-2019
- Schema Registry Made Simple by Confluent Cloud ft. Magesh Nandakumar.   
  https://www.buzzsprout.com/186154/1220195-schema-registry-made-simple-by-confluent-cloud-ft-magesh-nandakumar

# 07-06-2019
- Testing Kafka Streams Applications with Viktor Gamov.   
  Various approaches to testing Kafka Streams applications: KafkaEmbedded, TopologyTestDriver, Mocked Streams, Mockafka & using TestContainers.   
  https://www.buzzsprout.com/186154/1158407-testing-kafka-streams-applications-with-viktor-gamov

# 06-06-2019
- A DIY Guide to Kafka Connectors.   
  https://medium.com/enfuse-io/a-diy-guide-to-kafka-connectors-38ad7cd82e02

# 05-06-2019
- Log Compacted Topics in Apache Kafka.   
  How does Kafka internally keep the state of compacted topics in the file system?    
  https://towardsdatascience.com/log-compacted-topics-in-apache-kafka-b1aa1e4665a7

# 04-06-2019
- Observations on Observability.   
  https://blog.colinbreck.com/observations-on-observability/
- Domain-Oriented Observability.   
  https://martinfowler.com/articles/domain-oriented-observability.html
- Kafka Usecase: Deploying Kafka Streams and KSQL with Gradle
	- Part 1: Overview and Motivation.   
  	https://www.confluent.io/blog/deploying-kafka-streams-and-ksql-with-gradle-part-1-overview-and-motivation
	- Part 2: Managing KSQL Implementations.   
  	https://www.confluent.io/blog/deploying-kafka-streams-and-ksql-with-gradle-part-2-managing-ksql-implementations
- How KEEP-87 & Typeclasses will change the way we write Kotlin.   
  https://quickbirdstudios.com/blog/keep-87-typeclasses-kotlin/
- Immutable Conversations - Inside Arrow Fx & Arrow Optics.   
  https://www.youtube.com/watch?v=4eZFUpLiX00

# 03-06-2019
- Execution context of Kotlin Flows.   
  https://medium.com/@elizarov/execution-context-of-kotlin-flows-b8c151c9309b
- How to set up a serious Kubernetes terminal.   
  https://medium.com/free-code-camp/how-to-set-up-a-serious-kubernetes-terminal-dd07cab51cd4
- Deduplication at Scale: Dedupe Ingested Events Data at Scale using [Bloom Filters](https://blog.medium.com/what-are-bloom-filters-1ec2a50c68ff).   
  https://amplitude.engineering/dedupe-events-at-scale-f9e416e46ca9

# 02-06-2019
- Spring for Apache Kafka Deep Dive:    
	- Spring for Apache Kafka Deep Dive – Part 1: Error Handling, Message Conversion and Transaction Support.   
  	https://www.confluent.io/blog/spring-for-apache-kafka-deep-dive-part-1-error-handling-message-conversion-transaction-support
	- Spring for Apache Kafka Deep Dive – Part 2: Apache Kafka and Spring Cloud Stream.   
  	https://www.confluent.io/blog/spring-for-apache-kafka-deep-dive-part-2-apache-kafka-spring-cloud-stream
	- Spring for Apache Kafka Deep Dive – Part 3: Apache Kafka and Spring Cloud Data Flow.   
  	https://www.confluent.io/blog/spring-for-apache-kafka-deep-dive-part-3-apache-kafka-and-spring-cloud-data-flow
- Spring Boot + Kafka: The New Enterprise Platform by James Watters, Pivotal (Kafka Summit 2019 Keynote).   
  https://www.youtube.com/watch?v=9I3CDfHKfNY

# 01-06-2019
- The Coming Software Apocalypse.   
  *“The software did exactly what it was told to do. The reason it failed is that it was told to do the wrong thing.“*.   
  *“Software engineers don’t understand the problem they’re trying to solve, and don’t care to.”*
  https://www.theatlantic.com/technology/archive/2017/09/saving-the-world-from-code/540393/
- [Eve](http://witheve.com/): Checking what could have been if Eve would have had enough funding to complete the vision.   
- How Eve unifies your entire programming stack.   
  https://hackernoon.com/how-eve-unifies-your-entire-programming-stack-900ca80c58a7
- When logic programming meets CQRS.   
  https://hackernoon.com/when-logic-programming-meets-cqrs-1137ab2a5f86
- Throwing off our scope chains.   
  https://hackernoon.com/throwing-off-our-scope-chains-7567beb2d0b6
- Smalltalk and protein programming.   
  https://hackernoon.com/smalltalk-and-protein-programming-4da245ac93e2
- The rock-solid foundation for Eve’s big vision.   
  https://hackernoon.com/the-rock-solid-foundation-for-eves-big-vision-225b80b91e11
- Why Eve will be perfect for realtime apps     
  https://hackernoon.com/why-eve-will-be-perfect-for-realtime-apps-92b965b80ad

# 30-05-2019
- Online Event Processing: Achieving consistency where distributed transactions have failed.  
  (Martin Kleppmann, Alastair R. Beresford, and Boerge Svingen).   
  Different way of building systems... besides Online Transaction Processing (OLTP) and Online Analytical Processing (OLAP), we should think about OLEP, which is taking transaction processing ideas and implementing them on top of event processing systems.    
  Use event logs, rather than transactions, as the primary application programming model for data management. Traditional databases are still used, but their writes come from a log rather than directly from the application.    
  https://queue.acm.org/detail.cfm?id=3321612
- Publishing with Apache Kafka at The New York Times.   
  https://www.confluent.io/blog/publishing-apache-kafka-new-york-times/

# 29-05-2019
- 17 Ways to Mess Up Self-Managed Schema Registry.   
  https://www.confluent.io/blog/17-ways-to-mess-up-self-managed-schema-registry

# 28-05-2019
- What’s the proper Kubernetes health check for a Kafka Streams application?    
  https://blog.softwaremill.com/whats-the-proper-kubernetes-health-check-for-a-kafka-streams-application-c9c00a112581

# 27-05-2019
- Eliminating Coroutine leaks in tests.   
  https://proandroiddev.com/eliminating-coroutine-leaks-in-tests-3af825e7cde2

# 26-05-2019
- Martin Kleppmann: Is Kafka a Database? (Kafka Summit London 2019 Keynote)    
  https://www.youtube.com/watch?v=BuE6JvQE_CY

# 24-05-2019
- H.264 is Magic.   
  https://sidbala.com/h-264-is-magic/

# 21-05-2019
- Schemas, Contracts, and Compatibility.   
  https://www.confluent.io/blog/schemas-contracts-compatibility

# 20-05-2019
- Performant Functional Programming to the max with ZIO.   
  https://cloudmark.github.io/A-Journey-To-Zio/

# 17-05-2019
- Serverless Architectures.   
  https://martinfowler.com/articles/serverless.html
- Serverless Computing: One Step Forward, Two Steps Back.   
  http://cidrdb.org/cidr2019/papers/p119-hellerstein-cidr19.pdf

# 16-05-2019
- Kafka Replication: The case for MirrorMaker 2.0.   
  https://blog.cloudera.com/blog/2019/05/kafka-replication-the-case-for-mirrormaker-2/
- Reactive Transactions with Spring.   
  https://spring.io/blog/2019/05/16/reactive-transactions-with-spring

# 14-05-2019
- Introducing a Cloud-Native Experience for Apache Kafka in Confluent Cloud.   
  https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud

# 13-05-2019
- Control as Liability.   
  Decentralization gets a surprising boost from the regulatory environment.
  https://vitalik.ca/general/2019/05/09/control_as_liability.html

# 12-05-2019
- Designing events first microservices for a cloud native world by Jonas Bonér - Lightbend.   
  https://www.youtube.com/watch?v=qFnSWDoK69I

# 9-05-2019
- Stateful Serverless Event Sourcing.   
  https://www.youtube.com/watch?v=AOY8yRC6dVY

# 8-05-2019
- Kafka transactions - the tricky bits.   
  Clear description of Kafka zombie fencing. 
  https://tgrez.github.io/posts/2019-04-13-kafka-transactions.html
- HTTP headers for the responsible developer.   
  https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer

# 7-05-2019
- It’s Time for Streaming to Have a Maturity Model.   
  https://www.buzzsprout.com/186154/996549-it-s-time-for-streaming-to-have-a-maturity-model-ft-nick-dearden

# 6-05-2019
- Functional Programming is on the rise.   
  https://medium.com/@elizarov/functional-programing-is-on-the-rise-ebd5c705eaef

# 4-05-2019
- In a Serverless World, We Still Need State.   
  https://www.infoq.com/news/2019/04/serverless-needs-state
- Serverless Needs a Bolder, Stateful Vision.   
  https://thenewstack.io/serverless-needs-a-bolder-stateful-vision/
- The Problem is Data: Gwen Shapira, Confluent, Serverless NYC 2018.   
  https://www.youtube.com/watch?time_continue=66&v=J-9afazR2o0

# 3-05-2019
- Is there anybody out there? - Manuel Bernhardt.   
  https://www.youtube.com/watch?v=VoF6211e3y8

# 2-05-2019
- Focus on Integration Tests Instead of Mock-Based Tests.  
  [Test the behaviour, not the implementation](https://testing.googleblog.com/2013/08/testing-on-toilet-test-behavior-not.html).    
  A mocked dependency is an implementation.    
  Test the final output, not the intermediate one.     
  https://phauer.com/2019/focus-integration-tests-mock-based-tests/

# 1-05-2019
- Kafka-Streams: a road to autoscaling via Kubernetes.   
  https://medium.com/xebia-france/kafka-streams-a-road-to-autoscaling-via-kubernetes-417f2597439

# 30-04-2019
- Diving into Exactly Once Semantics with Guozhang Wang.   
  A walk through the implementation of transactional messaging in Kafka.     
  https://www.buzzsprout.com/episodes/1046878-diving-into-exactly-once-semantics-with-guozhang-wang
- Enabling Exactly Once in Kafka Streams.   
  https://www.confluent.io/blog/enabling-exactly-once-kafka-streams/
- Exactly once Semantics are Possible: Here’s How Kafka Does it.   
  https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/
- Transactions in Apache Kafka.   
  https://www.confluent.io/blog/transactions-apache-kafka/

# 29-04-2019
- Ben Stopford on Microservices and Event Streaming.   
  Microservices are pretty ubiquitous these days. Really “SOA done right,” they reimagine the services pattern in the context of the world we live in today, nearly two decades since the first big service-oriented systems hit production. But what have we learned in this time?    
  Ben Stopford explore the event-driven paradigm and how it relates to the microservice architectures we build today. Ben dives deep into coupling, evolution and challenges of our increasingly data-oriented culture. He also talks about the future, where data are events and events are data, and touches on real-time architectures that retain the decoupling properties needed to be pluggable, and to evolve.    
  https://www.buzzsprout.com/186154/1029683-ben-stopford-on-microservices-and-event-streaming

# 28-04-2019
- Subtractive synths explained.   
  Oscillators, Filters, Amplifiers, LFOs & Envelopes.   
  https://www.residentadvisor.net/features/1351
- Concurrency on the JVM is complicated.   
  https://medium.com/@wiemzin/concurrency-is-complicated-e44ddb5aa9ef
- Simple design of Kotlin Flow.   
  https://medium.com/@elizarov/simple-design-of-kotlin-flow-4725e7398c4c
- Watermarks, Tables, Event Time, and the Dataflow Model.   
  https://www.confluent.io/blog/watermarks-tables-event-time-dataflow-model/
- Kafka Streams’ Take on Watermarks and Triggers.   
  https://www.confluent.io/blog/kafka-streams-take-on-watermarks-and-triggers
- 7 Commandments for Event-Driven Architecture.   
  https://rjzaworski.com/2019/03/7-commandments-for-event-driven-architecture

# 26-04-2019

- Real Production Use: Reactive Design For The Manufacturing Industry by Roland Kuhn.   
  https://www.youtube.com/watch?v=0jtnfh0lKCU&t=2s
- Event Sourcing by Avi Levi.   
  https://www.youtube.com/watch?v=9AGfpjhmuOw&t=2s


# 24-04-2019

- [Kafka Streams In Action](https://www.manning.com/books/kafka-streams-in-action): Chapter 5 - The KTable API.   
  The duality of streams and tables. Where a KStream is a stream of events, a KTable is a stream of related events or an update stream.

# 23-04-2019

- Kafka Exactly Once Semantics Revisited.   
  https://www.confluent.io/kafka-summit-ny19/exactly-once-semantics-revisted 


# 22-04-2019

- [Designing Data-Intensive Applications - Martin Kleppmann](https://dataintensive.net) - Chapter 1.   
  Chapter 1 introduces the terminology and approach that's going to be used throughout this book. It examines what is actually meant by words like reliability, scalability, and maintainability, and how we can try to achieve these goals.


# 21-04-2019

- A guide for the perplexed - GOTO 2018 by Joe Armstrong.   
  https://www.youtube.com/watch?v=rmueBVrLKcY 
- Why OO sucks by Joe Armstrong.   
  http://www.cs.otago.ac.nz/staffpriv/ok/Joe-Hates-OO.htm & https://news.ycombinator.com/item?id=19715191

# 20-04-2019

- The mess we’re in by Joe Armstrong.   
  https://www.youtube.com/watch?v=lKXe3HUG2l4 

# 19-04-2019

- [Kafka Streams In Action](https://www.manning.com/books/kafka-streams-in-action): Chapter 4 - Streams And State.   
  Chapter 4 discusses state and explains how it’s required for streaming applications. Handles state store implementations and performing joins in Kafka Streams.

# 18-04-2019

- 122 announcements from Google Cloud Next ‘19.   
  https://cloud.google.com/blog/topics/inside-google-cloud/100-plus-announcements-from-google-cloud-next19 


# 17-04-2019

- [Kafka Streams In Action](https://www.manning.com/books/kafka-streams-in-action): Chapter 3 - Developing Kafka Streams.   
  The Kafka Streams DSL & Processor API.
  
# 16-04-2019
- WebSockets for App Engine (Flexible Environment).   
  https://cloud.google.com/blog/products/application-development/introducing-websockets-support-for-app-engine-flexible-environment
  
# 15-04-2019
- Achieving High Availability With Stateful Kafka Streams Applications.   
  https://tech.transferwise.com/achieving-high-availability-with-kafka-streams/

# 14-04-2019
A software renaissance of some sort is taking place with regard to the authoring of concurrent programs: tying task lifetime to lexical scopes and the stack in a deliberate way while providing sane error propagation and cancellation semantics. Reading into Kotlin coroutines & structured concurrency.    

Structured concurrency:    

- “Concurrency made easy”: coming soon to a programming language near you.   
  https://medium.com/@belm0/concurrency-made-easy-d3fdb0382c58
- Update on Structured Concurrency.   
  http://250bpm.com/blog:137
- Exceptions vs Structured Concurrency.   
  https://matklad.github.io/2018/07/24/exceptions-in-structured-concurrency.html
- Notes on structured concurrency, or: Go statement considered harmful.   
  https://vorpus.org/blog/notes-on-structured-concurrency-or-go-statement-considered-harmful/    
  
Kotlin coroutines:    

- Structured concurrency.   
  https://medium.com/@elizarov/structured-concurrency-722d765aa952
- Blocking threads, suspending coroutines.   
  https://medium.com/@elizarov/blocking-threads-suspending-coroutines-d33e11bf4761
- Explicit concurrency.   
  https://medium.com/@elizarov/explicit-concurrency-67a8e8fd9b25
- What is “concurrent” access to mutable state?    
  https://proandroiddev.com/what-is-concurrent-access-to-mutable-state-f386e5cb8292
- The reason to avoid GlobalScope.   
  https://medium.com/@elizarov/the-reason-to-avoid-globalscope-835337445abc
- Coroutine Context and Scope.   
  https://medium.com/@elizarov/coroutine-context-and-scope-c8b255d59055
- Cold flows, hot channels.   
  https://medium.com/@elizarov/cold-flows-hot-channels-d74769805f9

# 12-04-2019
- Everything you should know about certificates and PKI (public key infrastructure) but are too afraid to ask.   
  https://smallstep.com/blog/everything-pki.html

# 11-04-2019
- Les Cast Codeurs Podcast: [Interview sur Quarkus avec Emmanuel Bernard](https://lescastcodeurs.com/2019/03/26/lcc-207-interview-sur-quarkus-avec-emmanuel-bernard/).   
  Quarkus is Red Hat's new Java application framework, "A Kubernetes Native Java stack tailored for GraalVM & OpenJDK HotSpot, crafted from the best of breed Java libraries and standards".   
  https://quarkus.io/
- From zero to Quarkus and Knative: The easy way.   
  https://developers.redhat.com/blog/2019/04/09/from-zero-to-quarkus-and-knative-the-easy-way/
  
# 10-04-2019
- Introduction to Clock Sync in Finance and Beyond.   
  https://www.fsmlabs.com/news/2017/11/01/introduction-to-clock-sync-in-finance-and-beyond.html

# 9-04-2019
Counter-narrative to the often quoted notion that Bitcoin would be an unfolding environmental disaster. The following articles provide a fact-based examination of the claim that Bitcoin consumes more energy than a number of countries.   

- The reports of bitcoin environmental damage are garbage.   
  https://medium.com/coinmonks/the-reports-of-bitcoin-environmental-damage-are-garbage-5a93d32c2d7
- Will Bitcoin burn the planet to ashes? Not so fast.    
  https://vellum.capital/2018/11/08/will-bitcoin-burn-the-planet-to-ashes-not-so-fast/

# 8-04-2019
- Technical Debt Is Like Tetris.   
  https://medium.com/s/story/technical-debt-is-like-tetris-168f64d8b700 & https://news.ycombinator.com/item?id=19353352