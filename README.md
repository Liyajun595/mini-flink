# mini-flink
学习一项技术最好的方式莫过于 "造轮子"。
本项目基于 Flink-1.14 的官方示例 org.apache.flink.streaming.examples.wordcount.WordCount 删减代码，得到一个最小的可运行的 Flink

开始之前根据 IDEA Statistic 插件统计 Flink-1.14 有 Java 代码 1380163(不含注释、空行)，Scala 代码 185875(不含注释、空行)

2021.01.01

每次删除记录都将统计在此文件中
2021.01.02 删除 flink-yarn、flink-yarn-test。 Java 1367046, Scala 185875

2021.01.02 删除 flink-quickstart。 Java 1367030, Scala 185859

2021.01.02 删除 flink-doc。 Java 1365036, Scala 185859

2021.01.02 删除 flink-end-to-end-tests。 Java 1350078, Scala 185815

2021.01.02 删除 flink-k8s。 Java 1335966, Scala 185815

2021.01.02 删除 flink-dist。 Java 1335806, Scala 185807

2021.01.02 删除 flink-walkthroughs。 Java 1335479, Scala 185762

2021.01.02 删除 flink-external-resources。 Java 1335150, Scala 185762

2021.01.02 删除 flink-python。 Java 1311708, Scala 185287

2021.01.02 删除 flink-contrib。 Java 1311252, Scala 185287

2021.01.02 删除 flink-container。 Java 1310803, Scala 185287

2021.01.02 删除 flink-fs-tests。 Java 1309032, Scala 185287

2021.01.02 删除 other examples and tests。 Java 1301993, Scala 183805

2021.01.02 删除 flink-scala-shell。 Java 1301683, Scala 183135

2021.01.03 删除 flink-tests。 Java 1249361, Scala 170217

2021.01.03 删除 flink-table。 Java 1001526, Scala 15937

2021.01.03 删除 flink-scala、flink-streaming-scala。 Java 1000387, Scala 3205

2021.01.03 删除 flink-dist、flink-dist-scala。 Java 996865, Scala 3205

2021.01.03 删除 flink-test-utils-parent & other tests。 Java 501054, Scala 1695

2021.01.04 删除一些 connector。 Java 424444, Scala 1257

2021.01.04 删除 flink-formats。 Java 404784, Scala 1257

2021.01.04 删除 flink-filesystems。 Java 396603, Scala 1257。org.apache.flink.runtime.security 中有依赖文件系统

2021.01.04 删除所有 flink-connectors。 Java 388536, Scala 1257。org.apache.flink.streaming.api.functions.sink.filesystem.Bucket 中有依赖 flink-file-sink-common
