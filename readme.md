# Awesome JVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome JVM languages, concurrency, tools and other low level related stuff.

- [Awesome JVM](#awesome-jvm)
    - [Languages](#languages)
    - [Profilers](#profilers)
    - [Runtimes](#runtimes)
    - [Virtual Machines](#virtual-machines)
- [Resources](#resources)
    - [Communities](#communities)    
    - [Documentation](#documentation)
    - [Media](#media)
    - [People](#people)
- [Contributing](#contributing)

## Languages

*Languages running on the JVM.*

* [Ceylon](http://ceylon-lang.org/) - Object-oriented, strong and static programming language with an emphasis on immutability, created by Red Hat.
* [Clojure](http://clojure.org/) - Dialect of Lisp created by Rich Hickey. Dynamically typed with emphasis on functional programming.
* [Erjang](http://www.erjang.org) - A JVM-based Erlang VM.
* [Frege](https://github.com/Frege/frege) - Pure functional programming language in the spirit of Haskell.
* [Groovy](http://www.groovy-lang.org/) - Optionally typed and dynamic language, with static-typing and static compilation capabilities.
* [Java](http://www.oracle.com/technetwork/java/javase/overview/index.html) - General-purpose, concurrent, strongly typed, class-based object-oriented language.
* [JRuby](http://jruby.org) - Implementation of the Ruby language on the JVM.
* [Jython](http://www.jython.org) - Python for the Java Platform.
* [Kawa](http://www.gnu.org/software/kawa/) - Extension of the Scheme language, which is in the Lisp family of programming languages.
* [Kotlin](http://kotlinlang.org/) - Statically typed programming language for the JVM, Android and the browser.
* [Nashorn](http://openjdk.java.net/projects/nashorn/) - Lightweight high-performance JavaScript runtime in Java with a native JVM.
* [Nodyn](http://nodyn.io/) - Node.js compatible framework, running on the JVM powered by the DynJS Javascript runtime.
* [Renjin](http://www.renjin.org/) - JVM-based interpreter for the R language for the statistical analysis
* [Scala](http://www.scala-lang.org/) - Strong and static programming language that combine object-oriented and functional programming ideas.

## Profilers

*Tools that provide profiling and tracing information to aid program optimization*
* [BTrace](https://github.com/jbachorik/btrace) - a safe, dynamic tracing tool for the Java platform.
* [Chronon](http://chrononsystems.com) - Record your entire java program. Replay on any machine.
* [GCViewer](https://github.com/chewiebug/GCViewer) - GCViewer is a tool that visualizes verbose GC output.
* [Java Mission Control](http://www.oracle.com/technetwork/java/javaseproducts/mission-control/java-mission-control-1998576.html) - Continuously collect low level and detailed runtime information enabling after-the-fact incident analysis.
* [jHiccup](http://www.azulsystems.com/jHiccup) - jHiccup is an open source tool designed to measure the pauses and stalls associated with an application’s underlying Java runtime platform.
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html) - Helps resolve performance bottlenecks, pin down memory leaks and understand threading issues.
* [Riemann JVM Profiler](https://github.com/riemann/riemann-jvm-profiler) - JVM agent which sends function-level profiler telemetry to a Riemann server for analysis, visualization, and storage.
* [Swiss Java Knife](https://github.com/aragozin/jvm-tools) - Small set of tools for JVM troublshooting, monitoring and profiling.
* [Takipi](https://www.takipi.com/) - Tells you when and why code breaks in production.
* [YourKit](https://www.yourkit.com/) - Fully featured, easy to use, low overhead profiler for Java EE and Java SE platforms.
* [Zipkin](https://github.com/openzipkin/zipkin) - A distributed tracing system gather timing data for disparate services developed by Twitter.

## Runtimes

*Tools for managing jvm runtime processes*
* [CRaSH](http://www.crashub.org/) - The shell for the Java Platform.
* [Nailgun](http://martiansoftware.com/nailgun/) - Nailgun is a client, protocol, and server for running Java programs from the command line without incurring the JVM startup overhead.
* [Drip](https://github.com/ninjudd/drip) - Fast JVM launching without the hassle of persistent JVMs.

## Virtual Machines

*Virtual machines that implement the JVM specification or parts of it.*
* [Dalvik](https://source.android.com/devices/tech/dalvik/) - Android runtime (ART) is the managed runtime used by applications and some system services on Android.
* [HotSpot](http://openjdk.java.net/groups/hotspot/) - HotSpot virtual machine maintained and distributed by Oracle Corporation.
* [IBM J9](http://www.ibm.com/developerworks/java/jdk/) - JVM developed by IBM.
* [Zing](http://www.azulsystems.com/products/zing) - The only JVM that eliminates Java garbage collection pauses for large heap sizes.
* [Zulu](http://www.azulsystems.com/products/zulu) - The only certified multi-platform build of OpenJDK: Free, 100% open source Java.

# Resources

## Documentation

*Documentation related to JVM developement*
* [The Java Memory Model](http://www.cs.umd.edu/~pugh/java/memoryModel/) - Starting point for discussions of and information concerning the Java Memory Model.
* [The JSR-133 Cookbook for Compiler Writers](http://gee.cs.oswego.edu/dl/jmm/cookbook.html) - Unofficial guide to implementing the new Java Memory Model (JMM) specified by JSR-133.

## Communities

*Active discussions.*
* [concurrency-interest](http://altair.cs.oswego.edu/mailman/listinfo/concurrency-interest) - Discussion list for JSR-166.
* [mechanical-sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) - Discussing how to code sympathetically to and measure the underlying stack/platform so good performance can be extracted.

## Media

*Videos, podcasts and other media related to JVMs*
* [JVM Language Summit 2015](http://openjdk.java.net/projects/mlvm/jvmlangsummit/) - JVM Language Summit 2015.

## People

*People related to JVM development*
* [Aleksey Shipilëv](http://shipilev.net/) - Developing Oracle/Open JDK/Hotspot and other Java-related technologies.
* [Cliff Click](http://www.cliffc.org/blog/) - Creator of the HotSpot Server Compiler.
* [Doug Lea](http://g.oswego.edu/) - Author of the Java memory model.
* [Gil Tene](https://twitter.com/giltene) - Gil Tene twitter account.
* [Martin Thompson](http://mechanical-sympathy.blogspot.se/) - Pasty faced performance gangster.
* [Nitsan Wakart](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html) - Azul Systems.


# Contributing

Contributions are very welcome!

Please have a look at [contributing.md](https://github.com/deephacks/awesome-jvm/blob/master/contributing.md) for guidelines.
