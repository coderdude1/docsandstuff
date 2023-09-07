# Webflux
https://blog.devgenius.io/uplift-your-java-spring-boot-to-webflux-non-blocking-application-7b207999e669

3 part series thats pretty good overview, and has good info on setting an MDC in a reactive safe fashion
* https://spring.io/blog/2019/03/06/flight-of-the-flux-1-assembly-vs-subscription
* https://spring.io/blog/2019/04/16/flight-of-the-flux-2-debugging-caveats
* https://spring.io/blog/2019/12/13/flight-of-the-flux-3-hopping-threads-and-schedulers'

Quiz and such
https://tech.io/playgrounds/929/reactive-programming-with-reactor-3/Intro

Webflux Threading Model
https://piotrminkowski.com/2020/03/30/a-deep-dive-into-spring-webflux-threading-model/

Reactive Context
https://www.youtube.com/watch?v=5tlZddM5Jo0

Code sample from an udemy video on webfluxes
https://github.com/vinsguru/spring-webflux-course
https://github.com/vinsguru/java-reactive-programming-course/tree/master/src
https://github.com/dilipsundarraj1/reactive-spring-webflux
https://github.com/dilipsundarraj1/reactive-spring-webflux

## Webfluxes and Kotlin Specifics
Reactive and coroutines
https://docs.spring.io/spring-framework/reference/languages/kotlin/coroutines.html#how-reactive-translates-to-coroutines

## Schedulers and Metrics
I noticed that in micrometer there is support for scheduler metrics.  I saw an obsolete/deprecated example in a client library.  TODO research this stuff more
https://github.com/reactor/reactor-core/blob/main/docs/asciidoc/metrics.adoc
https://stackoverflow.com/questions/74461502/migration-guide-for-schedulers-enablemetrics-in-project-reactor

# Kotlin Thread Safety
https://levelup.gitconnected.com/how-to-write-thread-safe-code-with-kotlin-8a56ca6ff7a

# General Async
https://levelup.gitconnected.com/make-your-java-code-fully-async-369efa3b0f23

https://deadlockempire.github.io/

# Java Stuff
ALl functional interfaces in java
https://www.educative.io/answers/a-list-of-all-the-functional-interfaces-in-java

## Thread Metrics
https://stackoverflow.com/questions/71509187/spring-boot-thread-pool-metrics

## Completable Future
https://www.baeldung.com/java-completablefuture

## NIO
This is how netty is able to implement non-blocking IO
https://jenkov.com/tutorials/java-nio/nio-vs-io.html

https://medium.com/ing-blog/how-does-non-blocking-io-work-under-the-hood-6299d2953c74
