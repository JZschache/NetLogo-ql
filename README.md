# NetLogo extension: ql

This simulation tool is built on **NetLogo**. More specifically, the following software packages were used:

* [NetLogo 5.2](https://ccl.northwestern.edu/netlogo/)
* [Java 7](http://openjdk.java.net)
* [Scala 2.9.3](http://www.scala-lang.org)
* [Scala STM 0.5](https://nbronson.github.io/scala-stm/)
* [Akka 2.0.5](http://akka.io)
* [typesafe/config 1.2.0](https://github.com/typesafehub/config)
* [Colt 1.2.0](https://dst.lbl.gov/ACSSoftware/colt/)

The source code is found at [https://github.com/JZschache/NetLogo-Extensions](https://github.com/JZschache/NetLogo-Extensions)

Since ql is an extension of NetLogo, the latter must be installed first ([NetLogo 5.2.1](https://ccl.northwestern.edu/netlogo/5.2.1/)). 

After NetLogo has been installed, a directory named `ql` should be created in the `extensions` subdirectory of the `NetLogo` installation ([see also](
http://ccl.northwestern.edu/netlogo/docs/extensions.html)). All files from `https://github.com/JZschache/NetLogo-ql/tree/master/extensions/ql` should be downloaded and 
moved to the newly created directory `extensions/ql`. For example:

    git clone https://github.com/JZschache/NetLogo-ql.git
    mv NetLogo-ql/extensions/ql path-to-netlogo/extensions

After starting NetLogo, a sample model from `NetLogo-ql/models` can be loaded. A very simple one is given in `NetLogo-ql/models/basic.nlogo`.
