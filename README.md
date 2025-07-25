<p align="center">
  <img src="assets/images/howtheyloadtest_banner.svg" alt="howtheyloadtest banner" width="300px">
</p>

# How They Load Test

[![how they](https://img.shields.io/badge/how%20they-load%20test-orange?color=dd7c2f&style=flat-square)](#other-how-they-collections)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?color=567e6a&style=flat-square)](CONTRIBUTING.md)

> A curated collection of publicly available resources on how technology and tech-savvy organizations around the world plan/organize/perform/analyze load testing and related acitivities for their products.

## Introduction

Inspired by [howtheytest](https://github.com/abhivaikar/howtheytest), **How They Load Test** is a curated knowledge collection on different aspects of performance engineering, foremost, **performance and load testing** and related topics, by leading technology companies around the world.

## Topics

* Application Performance Management
* Architecture
* Automation
* Benchmarking
* Capacity Planning
* CI/CD
* Incidents
* Monitoring, Observability, Alerting
* Non-Functional Requirements Elicitation and Analysis
* Performance Engineering
* Scalability
* Test Environments
* Testing in Production
* Tools

## Organizations

> In alphabetical order.

<details>
  <summary>Ably</summary>

#### Blogs & Articles

* [Squid game: how we load-tested Ably’s Control API](https://ably.com/blog/how-we-load-tested-control-api) - 2022

#### Tools

* [ably-boomer](https://github.com/ably/ably-boomer) - Ably load generator for Locust, based on the [boomer](https://github.com/myzhan/boomer) library.
* [ably-locust](https://github.com/ably-labs/ably-locust) - A JavaScript load generator for Locust.

</details>

<details>
  <summary>Airbnb</summary>

#### Blogs & Articles

* [Load Testing with Impulse at Airbnb](https://medium.com/airbnb-engineering/load-testing-with-impulse-at-airbnb-f466874d03d2) - 2025
* [Improving Performance with HTTP Streaming](https://medium.com/airbnb-engineering/improving-performance-with-http-streaming-ba9e72c66408) - 2023
* [Measuring Web Performance at Airbnb](https://medium.com/airbnb-engineering/measuring-web-performance-at-airbnb-122da8d3ea3f) - 2021

</details>

<details>
  <summary>Airtasker</summary>

#### Blogs & Articles

* [How Airtasker uses Ruby JMeter and Flood for their load testing](https://nicolevanderhoeven.com/blog/20200224-airtasker/) - 2020

#### Talks

* [How much pressure can your app handle - Performance testing with Ruby](https://www.youtube.com/watch?v=Q09wJm4P8Xw) - Nancy Cai @ RubyConf 2020

</details>

<details>
  <summary>Amazon</summary>

#### Talks

* [UI, Load and Performance testing at Amazon](https://www.youtube.com/watch?v=UVS4CQvO4_M) - Leo Zhadanovsky, Dave Mozealous @ AWS re:Invent 2014
* [Best Practices for Benchmarking and Performance Analysis in the Cloud](https://www.youtube.com/watch?v=__tT5de64cI) - Robert Barnes @ AWS re:Invent 2013
* [Large Scale Load Testing Amazon.com's Traffic on AWS](https://www.youtube.com/watch?v=pgnQQoTMBhI) - Carlos Arguelles @ AWS re:Invent 2013

</details>

<details>
  <summary>Atlassian</summary>

#### Blogs & Articles

* [Performance and scale testing](https://confluence.atlassian.com/adminjiraserver/performance-and-scale-testing-1483246093.html)
* [Jira Performance Testing - Available Tools](https://confluence.atlassian.com/enterprise/jira-performance-testing-available-tools-729743538.html)

#### Tools

* [Jira Performance Tests (JPT)](https://bitbucket.org/atlassian/jira-performance-tests/)
* [Atlassian Performance Testing Framework](https://confluence.atlassian.com/enterprise/atlassian-performance-testing-framework-935575100.html)
* [Atlassian Data Center App Performance Toolkit](https://github.com/atlassian/dc-app-performance-toolkit)

</details>

<details>
  <summary>Capital One</summary>

#### Blogs & Articles

* [Performance Testing of Event-Driven Microservices](https://medium.com/capital-one-tech/performance-testing-of-event-driven-microservices-f5de74305985) - 2017

</details>

<details>
  <summary>Cloud Posse</summary>

#### Tools

* [Load Testing Stack](https://github.com/cloudposse-archives/load-testing) - A collection of best practices, workflows, scripts and scenarios used for load and performance testing.

</details>

<details>
  <summary>Cloudflare</summary>

#### Blogs & Articles

* [How to receive a million packets per second](https://blog.cloudflare.com/how-to-receive-a-million-packets/) - 2015
* [Optimizing Your Linux Stack for Maximum Mobile Web Performance](https://blog.cloudflare.com/optimizing-the-linux-stack-for-mobile-web-per/) - 2012

</details>

<details>
  <summary>CloudStory</summary>

#### Blogs & Articles

* [Running Load Testing at scale on shoestring budget](https://medium.com/cloudstory/running-load-testing-at-scale-on-shoestring-budget-b7ea34e4d5db) - 2020

</details>

<details>
  <summary>Confluent</summary>

#### Talks

* [Ducktape: Keeping System Testing Simple in a Distributed World](https://www.confluent.io/events/current/2022/ducktape-keeping-system-testing-simple-in-a-distributed-world/) - Ian McDonald @ Current 2022

#### Tools

* [ducktape](https://github.com/confluentinc/ducktape) - Distributed system integration and performance testing library.

</details>

<details>
  <summary>Console</summary>

#### Blogs & Articles

* [Automated website performance testing with GitHub Actions, k6 and Cloudflare Workers](https://web.archive.org/web/20230317030530/https://blog.console.dev/automated-website-performance-testing-with-github-actions-k6-and-cloudflare-workers/) - 2021

</details>

<details>
  <summary>Disney+ Hotstar</summary>

#### Blogs & Articles

* [Building Pubsub for 50M concurrent socket connections](https://blog.hotstar.com/building-pubsub-for-50m-concurrent-socket-connections-5506e3c3dabf) - 2019
* ["Millons scale" simulations](https://blog.hotstar.com/millons-scale-simulations-1602befe1ce5) - 2018

#### Talks

* [Real-time messaging service at Hotstar](https://www.youtube.com/watch?v=sF7HN9L54SE) - Piyush Gupta @ RootConf 2020
* [Scaling Hotstar.com for 25 million concurrent viewers](https://www.youtube.com/watch?v=mFpqrVxxwKc) - Gaurav Kamboj @ AWS re:Invent 2019

</details>

<details>
  <summary>Edmunds</summary>

#### Blogs & Articles

* [How we fixed a Node.js memory leak by using ShadowReader to replay production traffic into QA](https://technology.edmunds.com/2018/08/25/Investigating-a-Memory-Leak-and-Introducing-ShadowReader/) - 2018

#### Talks

* [ShadowReader - Serverless load tests for replaying production traffic](https://youtu.be/CszgGXqLbg4?t=14550) - Yuki Sawa @ SCaLE 17x 2019

#### Tools

* [ShadowReader](https://github.com/edmunds/shadowreader) - Serverless load testing tool for replaying website traffic by collecting traffic patterns from access logs, powered by AWS Lambda, S3 and ELB.

</details>

<details>
  <summary>Elastic</summary>

#### Blogs & Articles

* [How we perform continuous performance testing on Enterprise Search](https://www.elastic.co/blog/how-to-use-continuous-performance-testing-for-enterprise-search) - 2022

#### Talks

* [Seven Golden Rules for Benchmarking Elasticsearch](https://www.youtube.com/watch?v=-jgmnpG_P-Y) - Daniel Mitterdorfer @ JDK IO 2018
* [Benchmarking Elasticsearch with Rally](https://www.youtube.com/watch?v=HriBY2zoChw) - Daniel Mitterdorfer @ Search Meetup Munich 2016

#### Tools

* [Rally](https://github.com/elastic/rally) - Macrobenchmarking framework for Elasticsearch.

</details>

<details>
  <summary>Empathy.co</summary>

#### Blogs & Articles

* [Distributed Load Testing with K6 (K6 + K8s + Argo Workflows)](https://engineering.empathy.co/distributed-load-testing-with-k6/) - 2022

</details>

<details>
  <summary>Evil Martians</summary>

#### Blogs & Articles

* [Real-time stress: AnyCable, k6, WebSockets, and Yabeda](https://evilmartians.com/chronicles/real-time-stress-anycable-k6-websockets-and-yabeda) - 2021

#### Tools

* [websocket-bench](https://github.com/anycable/websocket-bench) - CLI interface for benchmarking WebSocket servers.

</details>

<details>
  <summary>Fitbit</summary>

#### Blogs & Articles

* [Load testing microservices and identifying scalability issues — Engineering Fitness](https://medium.com/fitbit-tech-blog/load-testing-microservices-and-identifying-scalability-issues-engineering-fitness-32a2c09b6d4a) - 2019

</details>

<details>
  <summary>Flashphoner</summary>

#### Blogs & Articles

* [Turning RTSP into WebRTC: how many cameras will the server withstand?](https://habr.com/ru/companies/flashphoner/articles/570370/) - 2021
* [Load test of WebRTC recording on AWS](https://habr.com/ru/companies/flashphoner/articles/570360/) - 2021
* [WebRTC face to face video chat. Load test](https://habr.com/ru/companies/flashphoner/articles/570316/) - 2021
* [Load testing for WebRTC mixer](https://habr.com/ru/companies/flashphoner/articles/570342/) - 2021
* [Using a headless browser for WebRTC load tests](https://habr.com/ru/companies/flashphoner/articles/570250/) - 2021
* [Choosing a server for 1000 WebRTC streams](https://habr.com/ru/companies/flashphoner/articles/570284/) - 2021

</details>

<details>
  <summary>Form3</summary>

#### Talks

* [Load testing with F1](https://www.youtube.com/watch?v=yKJ_h0K6liM) - Adelina Simion & Andy Kuszyk @ Conf42 Golang 2022

#### Tools

* [f1](https://github.com/form3tech-oss/f1) - A flexible load testing framework using the Go language for test scenarios.

</details>

<details>
  <summary>GitLab</summary>

#### Blogs & Articles

* [The next step in performance testing? The GitLab Environment Toolkit](https://about.gitlab.com/blog/2021/06/15/why-we-are-building-the-gitlab-environment-toolkit-to-help-deploy-gitlab-at-scale/) - 2021
* [How our QA team leverages GitLab’s performance testing tool (and you can too)](https://about.gitlab.com/blog/2020/02/18/how-were-building-up-performance-testing-of-gitlab/) - 2020

#### Tools

* [GitLab Performance Tool (GPT)](https://gitlab.com/gitlab-org/quality/performance)
* [GitLab Environment Toolkit (GET)](https://gitlab.com/gitlab-org/gitlab-environment-toolkit)

</details>

<details>
  <summary>GovTech Edu</summary>

#### Blogs & Articles

* [Elevating Tech Reliability at Scale: How We Build Dependable Daily Performance Testing Platform](https://medium.com/govtech-edu/elevating-tech-reliability-at-scale-how-we-build-dependable-daily-performance-testing-platform-67616080dae3) - 2023
* [Unleashing Testing at Scale: How GovTech Edu Built a 200K RPS Load Testing Platform](https://medium.com/govtech-edu/unleashing-testing-at-scale-how-govtech-edu-built-a-200k-rps-load-testing-platform-c1a418dfebd6) - 2023

</details>

<details>
  <summary>Grafana</summary>

#### Blogs & Articles

* [How we use the k6 load-testing tool for developing Grafana](https://grafana.com/blog/2021/08/23/how-we-use-the-k6-load-testing-tool-for-developing-grafana/) - 2021

#### Tools

* [The Open Source Load Testing Stack](https://github.com/grafana/k6-timescaledb-stack)

</details>

<details>
  <summary>HelloFresh</summary>

#### Blogs & Articles

* [Kangal, user-friendly load testing tool](https://engineering.hellofresh.com/kangal-952e70e205fd) - 2020

#### Tools

* [Kangal (Kubernetes and Go Automatic Loader)](https://github.com/hellofresh/kangal)

</details>

<details>
  <summary>Helpshift</summary>

#### Blogs & Articles

* [How to benchmark a Kafka consumer that makes async HTTP requests](https://medium.com/helpshift-engineering/how-to-benchmark-a-kafka-consumer-that-makes-async-http-requests-7d7134d62f57) - 2019
* [Load Testing using Tsung](https://medium.com/helpshift-engineering/load-testing-using-tsung-ef26a662929b) - 2014

</details>

<details>
  <summary>iits-consulting</summary>

#### Blogs & Articles

* [How We Load Test Argo CD at Scale: 1000 vClusters with GitOps on Kubernetes](https://itnext.io/how-we-load-test-argo-cd-at-scale-1-000-vclusters-with-gitops-on-kubernetes-d8ea2a8935b6) - 2025
* [Performance testing Kubernetes workloads](https://medium.com/@stearz/performance-testing-kubernetes-workloads-144b2d8e4fb5) - 2024

#### Talks

* [Performance testing Kubernetes workloads](https://www.youtube.com/watch?v=-KQbWUZ_VoM) - Stephan Schwarz @ KubeFM

</details>

<details>
  <summary>LinkedIn</summary>

#### Blogs & Articles

* [Eliminating toil with fully automated load testing](https://www.linkedin.com/blog/engineering/optimization/eliminating-toil-with-fully-automated-load-testing) - 2019
* [TrafficShift: Load Testing at Scale](https://www.linkedin.com/blog/engineering/scalability/trafficshift-load-testing-at-scale) - 2017

#### Talks

* [Testing in production at LinkedIn](https://www.youtube.com/watch?v=lbO6INBICpQ) - Szczepan Faber @ Devoxx Poland 2018

</details>

<details>
  <summary>Loveholidays</summary>

#### Blogs & Articles

* [Load testing in production with Grafana Loki, Kubernetes and Golang](https://tech.loveholidays.com/load-testing-in-production-with-grafana-loki-kubernetes-and-golang-1699554d2aa3) - 2022

#### Tools

* [ripley](https://github.com/loveholidays/ripley) - HTTP traffic replay tool at multiples of the original rate.

</details>

<details>
  <summary>Lyft</summary>

#### Blogs & Articles

* [SimulatedRides: How Lyft uses load testing to ensure reliable service during peak events](https://eng.lyft.com/simulatedrides-how-lyft-uses-load-testing-to-ensure-reliable-service-during-peak-events-644dcb654454) - 2023

</details>

<details>
  <summary>Mattermost</summary>

#### Blogs & Articles

* [Improving performance (and more) through load testing](https://mattermost.com/blog/improving-performance-through-load-testing/) - 2020
* [Mattermost recipe: Using Google Lighthouse and ChatOps for website auditing and performance tracking](https://mattermost.com/blog/mattermost-lighthouse-auditing/) - 2020
* [Performance at Scale with Mattermost](https://mattermost.com/blog/performance-scale-mattermost/) - 2018

</details>

<details>
  <summary>Meesho Tech</summary>

#### Blogs & Articles

* [Scaling for Sale: Automating JMeter Distributed Load Testing](https://medium.com/meesho-tech/scaling-for-sale-automating-jmeter-distributed-load-testing-c128c000cd01) - 2022

</details>

<details>
  <summary>Meetecho</summary>

#### Talks

* [Load Testing of SIP and WebRTC Infrastructures](https://www.youtube.com/watch?v=SnvTAsYtZ5s) - Lorenzo Miniero @ Kamailio World 2017
* [Jattack WebRTC Load Testing tool](https://www.youtube.com/watch?v=UwNq8p0m1js) - Simon Romano @ IIT RTC Conference 2016

</details>

<details>
  <summary>Mercari</summary>

#### Blogs & Articles

* [Benchmarking Automation to Maintain Search Response Performance](https://engineering.mercari.com/en/blog/entry/20220207-8ff8aad53e/) - 2022

</details>

<details>
  <summary>Miro</summary>

#### Blogs & Articles

* [Managing hundreds of servers for load testing: autoscaling, custom monitoring, DevOps culture](https://medium.com/miro-engineering/managing-hundreds-of-servers-for-load-testing-autoscaling-custom-monitoring-devops-culture-390fd1c7e699) - 2020
* [Reliable load testing with regards to unexpected nuances](https://medium.com/miro-engineering/reliable-load-testing-with-regards-to-unexpected-nuances-6f38c82196a5) - 2020

</details>

<details>
  <summary>Monzo</summary>

#### Blogs & Articles

* [How we load tested our bank before our £20 million crowdfunding round](https://monzo.com/blog/2019/01/15/crowdfunding-technology-testing) - 2019

#### Talks

* [Scaling for the Known Unknown](https://www.infoq.com/presentations/monzo-microservices-arch/) - Suhail Patel @ QCon London 2019

</details>

<details>
  <summary>Mozilla</summary>

#### Blogs & Articles

* [Load Testing at Mozilla](https://web.archive.org/web/20221209121345/https://ziade.org/2017/03/23/load-testing-at-mozilla/) - 2017

#### Talks

* [Load testing web services at Mozilla with Molotov](https://www.youtube.com/watch?v=_Ue3rYNs2ro) - Tarek Ziade @ FOSDEM 2018

#### Tools

* [Feuerwerk](https://github.com/mozilla-services/feuerwerk) - A tool designed to run load tests in Docker containers using Google Kubernetes Engine.
* [Raptor](https://firefox-source-docs.mozilla.org/testing/perfdocs/raptor.html) - A performance testing framework for running browser pageload and browser benchmark tests.

</details>

<details>
  <summary>Netflix</summary>

#### Blogs & Articles

* [Fixing Performance Regressions Before they Happen](https://netflixtechblog.com/fixing-performance-regressions-before-they-happen-eab2602b86fe) - 2022
* [Manufactured Chaos: How Netflix Does Performance Testing](https://nicolevanderhoeven.com/blog/20180328-manufactured-chaos/) - 2018
* [Performance Under Load](https://netflixtechblog.medium.com/performance-under-load-3e6fa9a60581) - 2018
* [A Netflix Web Performance Case Study](https://medium.com/dev-channel/a-netflix-web-performance-case-study-c0bcde26a9d9) - 2018
* [Load Testing at Netflix: Virtual Interview with Coburn Watson](https://alexanderpodelko.com/blog/2014/02/11/load-testing-at-netflix-virtual-interview-with-coburn-watson/) - 2014
* [JMeter Plugin for Cassandra](https://netflixtechblog.com/jmeter-plugin-for-cassandra-8ca848c0d480) - 2012

#### Talks

* [How Netflix Tunes Amazon EC2 Instances for Performance](https://www.youtube.com/watch?v=89fYOo1V2pA) - Brendan Gregg @ AWS re:Invent 2017
* [Honest Performance Testing with NDBench](https://www.youtube.com/watch?v=-3I9zyuj1Bo) - Vinay Chella @ Cassandra Summit 2016
* [Performance Tuning Amazon EC2 Instances](https://www.youtube.com/watch?v=7Cyd22kOqWc) - Brendan Gregg @ AWS re:Invent 2014

#### Tools

* [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - A resiliency tool that helps applications tolerate random instance failures.
* [NDBench](https://github.com/Netflix/ndbench) - Netflix Data Benchmark, a pluggable cloud-enabled benchmarking tool that can be used across any data store system.

</details>

<details>
  <summary>Nexthink</summary>

#### Blogs & Articles

* [Comparing gRPC performance across different technologies](https://www.nexthink.com/blog/comparing-grpc-performance/) - 2021

</details>

<details>
  <summary>Outbrain</summary>

#### Talks

* [Hold My Beer - Load Testing. In Production. On Autopilot](https://www.youtube.com/watch?v=WDAKOZTQaLQ) - Slava Antonenko @ USENIX SREcon 2023 APAC

</details>

<details>
  <summary>Pinterest</summary>

#### Blogs & Articles

* [Pinterest Druid Holiday Load Testing](https://medium.com/pinterest-engineering/pinterest-druid-holiday-load-testing-4bd9b9ee1308) - 2021
* [Distributed tracing at Pinterest with new open source tools](https://medium.com/pinterest-engineering/distributed-tracing-at-pinterest-with-new-open-source-tools-a4f8a5562f6b) - 2017

#### Talks

* [Evolution of Observability Tools at Pinterest](https://www.youtube.com/watch?v=v7xmkA6B1yo) - Naoman Abbas @ USENIX SREcon 2019

#### Tools

* [Bender](https://github.com/pinterest/bender) - An easy-to-use library for creating load testing applications.
* [JBender](https://github.com/pinterest/jbender) - A port of Bender to the JVM platform with Quasar lightweight threads (fibers) and channels.

</details>

<details>
  <summary>Redis</summary>

#### Blogs & Articles

* [Redis Labs Performance Testing with Live Traffic](https://redis.io/blog/redis-labs-performance-testing-with-live-traffic/) - 2014
* [memtier_benchmark: A High-Throughput Benchmarking Tool for Redis & Memcached](https://redis.io/blog/memtier_benchmark-a-high-throughput-benchmarking-tool-for-redis-memcached/) - 2013

#### Talks

* [End-To-End Performance Testing, Profiling, and Analysis at Redis](https://www.youtube.com/watch?v=QemEy97fiY0) - Filipe Oliveira @ P99 CONF 2022
* [How to benchmark Redis](https://www.youtube.com/watch?v=d6KPJ6aKRJI) - Or Shwartz, Filipe Oliveira @ RedisConf 2021

#### Tools

* [memtier_benchmark](https://github.com/RedisLabs/memtier_benchmark) - NoSQL Redis and Memcache traffic generation and benchmarking tool.
* [redis-benchmark-go](https://github.com/redis-performance/redis-benchmark-go) - Redis benchmark utility in Go.

</details>

<details>
  <summary>Riot Games</summary>

#### Blogs & Articles

* [Scalability and Load Testing for Valorant](https://technology.riotgames.com/news/scalability-and-load-testing-valorant) - 2020

</details>

<details>
  <summary>Robinhood</summary>

#### Blogs & Articles

* [Scaling Confidently with the Load and Fault Team](https://newsroom.aboutrobinhood.com/scaling-confidently-with-the-load-and-fault-team/) - 2021

</details>

<details>
  <summary>Salesforce</summary>

#### Blogs & Articles

* [How to Scale Test on Salesforce](https://medium.com/salesforce-architects/how-to-scale-test-on-salesforce-bf933d5948b9) - 2021
* [The Importance of Data Quality & Quantity for Performance and Scale Testing](https://medium.com/salesforce-architects/the-importance-of-data-quality-quantity-for-performance-and-scale-testing-8fabd8c6a9cf) - 2021
* [How to Continuously Profile Tens of Thousands of Production Servers](https://engineering.salesforce.com/how-to-continuously-profile-tens-of-thousands-of-production-servers-a5714bab4dc0) - 2020
* [Performance Testing on the Lightning Platform](https://developer.salesforce.com/blogs/2020/09/performance-testing-on-the-lightning-platform) - 2020
* [Introduction to Performance Testing](https://developer.salesforce.com/blogs/2020/09/introduction-to-performance-testing) - 2020

</details>

<details>
  <summary>Shopify</summary>

#### Blogs & Articles

* [Resiliency Planning for High-Traffic Events](https://shopify.engineering/resiliency-planning-for-high-traffic-events) - 2020
* [Capacity Planning at Scale](https://shopify.engineering/capacity-planning-shopify) - 2020
* [Pummelling the Platform–Performance Testing Shopify](https://shopify.engineering/performance-testing-shopify) - 2020

#### Tools

* [Genghis](https://github.com/Shopify/go-lua/blob/main/doc/presentations/golangmtl-march-2016/presentation.md) - An in-house load generation tool using Lua VM in Go as core execution engine.

</details>

<details>
  <summary>Slack</summary>

#### Blogs & Articles

* [Continuous Load Testing: Building a culture of performance with Koi Pond](https://slack.engineering/continuous-load-testing/) - 2022
* [Load Testing with Koi Pond: How Slack models and tests with incredibly large groups of users](https://slack.engineering/load-testing-with-koi-pond/) - 2021
* [Preparing for Huge Waves of Traffic via Load Testing](https://slack.engineering/%ef%b8%8f-surfs-up-preparing-for-huge-waves-of-traffic-via-load-testing/) - 2019

#### Talks

* [Better Integration Tests for Performance Monitoring](https://www.youtube.com/watch?v=j0PJhD5XNJ8) - Maude Lemaire @ Strange Loop Conference 2019
* [Mobile performance testing at Slack. How to Build a Performance Test Pipeline from Scratch](https://www.youtube.com/watch?v=xKMIGN1WHgo) - Valera Zakharov @ DevFest Ukraine 2018

</details>

<details>
  <summary>Spotify</summary>

#### Blogs & Articles

* [Load Testing for 2022 Wrapped](https://engineering.atspotify.com/2023/03/load-testing-for-2022-wrapped/) - 2023

#### Tools

* [Lighthouse Audit Service](https://github.com/spotify/lighthouse-audit-service) - A service meant to help you run, schedule, store, and monitor Lighthouse reports over time.

</details>

<details>
  <summary>Supabase</summary>

#### Blogs & Articles

* [Supavisor: Scaling Postgres to 1 Million Connections](https://supabase.com/blog/supavisor-1-million) - 2023

#### Talks

* [How Supabase does performance benchmarking using k6](https://www.youtube.com/watch?v=VcrQidYBjEg) - Egor Romanov @ k6 Office Hours 2023

#### Tools

* [supabench](https://github.com/supabase/benchmarks) - Platform to run and keep the history of benchmark runs.

</details>

<details>
  <summary>Tag1 Consulting</summary>

#### Blogs & Articles

* [A Goose in the Clouds: Load Testing at Scale](https://www.tag1consulting.com/blog/goose-clouds-load-testing-scale) - 2021
* [Goose Attack: A Locust-inspired Load Testing Tool in Rust](https://www.tag1consulting.com/blog/goose-locust-inspired-load-testing-tool-rust) - 2020

#### Tools

* [gander](https://github.com/tag1consulting/ddev-gander) - Pre-configured OpenTelemetry stack with Grafana Tempo / Prometheus for performance testing.
* [goose](https://github.com/tag1consulting/goose) - A Rust load testing tool inspired by Locust.

</details>

<details>
  <summary>TeamSnap</summary>

#### Blogs & Articles

* [Load Testing a Service with ~20,000 Requests per Second with Locust, Helm, and Kustomize](https://medium.com/teamsnap-engineering/load-testing-a-service-with-20-000-requests-per-second-with-locust-helm-and-kustomize-ea9bea02ae28) - 2022

</details>

<details>
  <summary>Twitter</summary>

#### Talks

* [Testing Systems at Scale @Twitter](https://www.youtube.com/watch?v=99RABfKNfcY) - James Waldrop @ GTAC 2013

#### Tools

* [iago](https://github.com/twitter-archive/iago)/[iago2](https://github.com/twitter/iago2) - A load generator, built for engineers.
* [rpc-perf](https://github.com/twitter/rpc-perf) - A tool for benchmarking RPC services.

</details>

<details>
  <summary>Uber</summary>

#### Blogs & Articles

* [Introducing Shadower: A Minimalistic Load Testing Tool](https://www.uber.com/en-US/blog/introducing-shadower-a-minimalistic-load-testing-tool/) - 2022
* [Introducing Ballast: An Adaptive Load Test Framework](https://www.uber.com/en-US/blog/introducing-ballast-an-adaptive-load-test-framework/) - 2022
* [Introducing QALM, Uber’s QoS Load Management Framework](https://www.uber.com/en-US/blog/qalm-qos-load-management-framework/) - 2018
* [Reliability at Scale: Engineering an Uneventful New Year's Eve](https://www.uber.com/en-US/blog/nye/) - 2017

#### Talks

* [Testing in Production at Scale](https://www.youtube.com/watch?v=nIlFmja65_g) - Amit Gud @ USENIX SREcon 2019

</details>

<details>
  <summary>VictoriaMetrics</summary>

#### Blogs & Articles

* [Monitoring benchmark: how to generate 100 million samples/s of production-like data](https://victoriametrics.com/blog/benchmark-100m/) - 2023
* [Grafana Mimir and VictoriaMetrics: performance tests](https://victoriametrics.com/blog/mimir-benchmark/) - 2022
* [Benchmarking Prometheus-compatible time series databases](https://victoriametrics.com/blog/remote-write-benchmark/) - 2022

#### Talks

* [VictoriaMetrics: scaling to 100 million metrics per second](https://www.youtube.com/watch?v=xfed9_Q0_qU) - Aliaksandr Valialkin @ OSMC 2022

#### Tools

* [prometheus-benchmark](https://github.com/VictoriaMetrics/prometheus-benchmark) - Benchmark for Prometheus-compatible systems.

</details>

<details>
  <summary>Wingify</summary>

#### Blogs & Articles

* [Performance Testing a data pipeline at scale](https://engineering.wingify.com/posts/performance-testing-a-data-pipeline-at-scale/) - 2020
* [Overcoming the Challenges of Performance Testing Single-page Apps](https://engineering.wingify.com/posts/performance-testing/) - 2015

</details>

<details>
  <summary>WinZO</summary>

#### Blogs & Articles

* [Simulating random spikes in traffic with low cost testing infrastructure](https://tech.winzogames.com/performance-testing-simulating-random-spikes-in-traffic-with-low-cost-testing-infrastructure-462b727817b8) - 2022

</details>

<details>
  <summary>Wix</summary>

#### Blogs & Articles

* [How We Improved Website Performance by Evolving Our Infrastructure](https://www.wix.engineering/post/how-we-improved-website-performance-by-evolving-our-infrastructure) - 2021

#### Talks

* [Testing for Performance](https://www.youtube.com/watch?v=T1Zuad-Mkg0) - Dan Shappir @ Wix Engineering Tech Talks 2019
* [Improving Load Time for 100 Million Websites](https://www.youtube.com/watch?v=5dtDUkvLLCE) - Dan Shappir @ Wix Engineering Tech Talks 2019

</details>

<details>
  <summary>Zalando</summary>

#### Blogs & Articles

* [Building an end-to-end load test automation system on top of Kubernetes](https://engineering.zalando.com/posts/2021/03/building-an-end-to-end-load-test-automation-system-on-top-of-kubernetes.html) - 2021
* [How Zalando prepares for Cyber Week](https://engineering.zalando.com/posts/2020/10/how-zalando-prepares-for-cyber-week.html) - 2020
* [End-to-end load testing Zalando's production website](https://engineering.zalando.com/posts/2019/04/end-to-end-load-testing-zalandos-production-website.html) - 2019
* [End-to-end latency challenges for microservices](https://engineering.zalando.com/posts/2016/08/end-to-end-latency-challenges-for-microservices.html) - 2016

#### Talks

* [Load Testing in the Microservices World](https://www.youtube.com/watch?v=aUGSPQKP8J0) - Arjun Naik @ LeaseWeb Tech Summit Berlin 2016

#### Tools

* [docker-locust](https://github.com/zalando-incubator/docker-locust) - A ready and easy-to-use version of locust which also contains additional/useful features that are required.
* [transformer](https://github.com/zalando-incubator/transformer) - A command-line tool and Python library to transform/convert web browser sessions (HAR files) into locust load testing scenarios (locustfile).
* [typhoon](https://github.com/fogfish/typhoon) - A stress and load testing tool for distributed systems that simulates traffic from a test cluster toward a system-under-test and visualizes infrastructure-, protocol- and application-related latencies.
* [zelt](https://github.com/zalando-incubator/zelt) - Zalando End-to-end Load Tester, a command-line tool for orchestrating the deployment of locust in Kubernetes.

</details>

<details>
  <summary>Zoopla</summary>

#### Blogs & Articles

* [Measuring Web Page Performance at Zoopla](https://www.houseful.blog/posts/2021/measuring-page-performance/) - 2021

</details>

<details>
  <summary>ZOOZ</summary>

#### Blogs & Articles

* [Distributed load testing with Kubernetes and Predator](https://medium.com/payu-engineering/distributed-load-testing-using-kubernetes-and-predator-cf447e33e5cc) - 2020
* [Optimizing Node.js Performance in Microservice Architecture](https://medium.com/zooz-engineering/nodejs-performance-302ff764509a) - 2019
* [The Rise of Predator](https://medium.com/zooz-engineering/by-niv-lipetz-software-engineer-zooz-b5928da0b7a8) - 2019

#### Tools

* [Predator](https://github.com/Zooz/predator) - A distributed open-source platform for load testing APIs using artillery as load testing engine.

</details>

## Credits

* Inspired by [How They Test](https://github.com/abhivaikar/howtheytest) from [Abhijeet Vaikar](https://github.com/abhivaikar).
* Banner cartoon vector by [vectorjuice](https://www.freepik.com/author/vectorjuice) from [freepik.com](https://www.freepik.com/vectors/cartoon).

## Other How They... collections

* [How They Test](https://github.com/abhivaikar/howtheytest)
* [How They DevOps](https://github.com/bregman-arie/howtheydevops)
* [How They SRE](https://github.com/upgundecha/howtheysre)
* [How They AWS](https://github.com/upgundecha/howtheyaws)
* [How They Automate on Mobile](https://github.com/testableapple/how-they-automate-on-mobile)

## Contributors

<a href="https://github.com/aliesbelik/how-they-load/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=aliesbelik/how-they-load" alt="contributors">
</a>

## Contribute

Contributions are welcome!<br>
Read the [CONTRIBUTING](CONTRIBUTING.md) guidelines first.
