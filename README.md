如果您觉得这个项目对您有帮助，就请点右上角的**Star**按钮为它加星星✨✨ 其他TIOBE Top 20编程语言的中文翻译请看[awesome-code-resources](https://github.com/awesome-code-resources/awesome-code-resources)。
# 很棒的Java[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
精选的Java框架，库和软件列表。

## 内容
- [项目](#项目)
  - [Bean映射](#Bean映射)
  - [构建](#构建)
  - [字节码操作](#字节码操作)
  - [缓存](#缓存)
  - [CLI](#CLI)
  - [集群管理](#集群管理)
  - [代码分析](#代码分析)
  - [代码覆盖率](#代码覆盖率)
  - [代码生成器](#代码生成器)
  - [编译器-编译器](#编译器-编译器)
  - [计算机视觉](#计算机视觉)
  - [配置](#配置)
  - [约束满足问题求解器](#约束满足问题求解器)
  - [CSV](#CSV)
  - [数据结构](#数据结构)
  - [数据库](#数据库)
  - [日期和时间](#日期和时间)
  - [依赖注入](#依赖注入)
  - [发展](#发展)
  - [分布式应用程序](#分布式应用程序)
  - [分布式事务](#分布式事务)
  - [分布](#分布)
  - [文档处理](#文档处理)
  - [财务](#财务)
  - [形式验证](#形式验证)
  - [函数式编程](#函数式编程)
  - [游戏开发](#游戏开发)
  - [地理空间](#地理空间)
  - [图形用户界面](#图形用户界面)
  - [高性能](#高性能)
  - [HTTP客户端](#HTTP客户端)
  - [超媒体类型](#超媒体类型)
  - [IDE](#IDE)
  - [图像](#图像)
  - [内省](#内省)
  - [作业调度](#作业调度)
  - [JSON](#JSON)
  - [JVM和JDK](#JVM和JDK)
  - [日志记录](#日志记录)
  - [机器学习](#机器学习)
  - [消息传递](#消息传递)
  - [微服务](#微服务)
  - [杂项](#杂项)
  - [移动开发](#移动开发)
  - [监测](#监测)
  - [原生](#原生)
  - [自然语言处理](#自然语言处理)
  - [联网](#联网)
  - [ORM](#ORM)
  - [PaaS](#PaaS)
  - [PDF](#PDF)
  - [性能分析](#性能分析)
  - [站台](#站台)
  - [流程](#流程)
  - [反应式库](#反应式库)
  - [REST框架](#REST框架)
  - [科学](#科学)
  - [搜索](#搜索)
  - [安全](#安全)
  - [序列化](#序列化)
  - [服务器](#服务器)
  - [模板引擎](#模板引擎)
  - [测试](#测试)
  - [效用](#效用)
  - [版本管理器](#版本管理器)
  - [Web爬行](#Web爬行)
  - [Web框架](#Web框架)
  - [工作流编排引擎](#工作流编排引擎)
- [资源](#资源)
  - [相关的Awesome 列表](#相关的Awesome 列表)
  - [社区](#社区)
  - [前端](#前端)
  - [有影响力的书籍](#有影响力的书籍)
  - [播客和截屏](#播客和截屏)
  - [人](#人)
  - [网站](#网站)

## 项目
### Bean映射
_ 简化bean映射的框架。_ 

- [dOOv](https://github.com/doov-io/doov)-为类型安全域模型验证和映射提供fluent API。它使用注释，代码生成和类型安全的DSL，使bean验证和映射快速和容易。
- [JMapper](https://github.com/jmapper-framework/jmapper-core)-使用字节码操作闪电快速映射。支持注释和API或XML配置。
- [MapStruct](https://github.com/mapstruct/mapstruct)-代码生成器，它基于约定配置方法简化了不同bean类型之间的映射。
- [ModelMapper](https://github.com/modelmapper/modelmapper)-智能对象映射库，自动将对象映射到彼此。
- [Orika](https://github.com/orika-mapper/orika)-JavaBean映射框架，递归地将数据从一个对象 (以及其他功能) 复制到另一个对象。
- [reMap](https://github.com/remondis-it/remap)-Lambda和基于方法句柄的映射，如果对象具有不同的名称，则需要代码而不是注释。
- [Selma](https://github.com/xebia-france/selma)-基于注释处理器的bean映射器。

### 构建
_ 处理应用程序的生成周期和依赖项的工具。_ 

- [Apache Maven](https://maven.apache.org)-声明式构建和依赖管理，有利于约定而不是配置。它可能比Apache Ant更可取，后者使用相当程序化的方法，并且可能难以维护。
- [Bazel](https://bazel.build)-来自Google的工具，可快速可靠地构建代码。
- [Buck](https://github.com/facebook/buck)-鼓励创建由代码和资源组成的小型可重用模块。
- [Gradle](https://gradle.org)-通过Groovy而不是声明XML编程的增量构建。适用于Maven的依赖管理。

### 字节码操作
_ 库以编程方式操作字节码。_ 

- [ASM](https://asm.ow2.io)-通用，低级别的字节码操作和分析。
- [Byte Buddy](https://bytebuddy.net)-使用fluent API进一步简化字节码生成。
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer)-Java 8 Jar & 安卓APK逆向工程套件。(GPL-3.0-only)
- [Byteman](https://byteman.jboss.org)-通过DSL (规则) 在运行时操纵字节码; 主要用于测试/故障排除。(LGPL-2.1-or-later)
- [cglib](https://github.com/cglib/cglib)-字节码生成库。
- [Javassist](https://github.com/jboss-javassist/javassist)-尝试简化字节码编辑。
- [Maker](https://github.com/cojen/maker)-提供低级别的字节码生成。
- [Mixin](https://github.com/SpongePowered/Mixin)-使用真正的Java代码在运行时操作字节码。
- [Perses](https://github.com/nicolasmanic/perses)-根据混沌工程的原理在字节码级别动态注入故障/延迟。
- [Recaf](https://www.coley.software/Recaf/)-JVM逆向工程工具包，本质上是Java字节码的IDE。

### 缓存
_ 提供缓存设施的库。_ 

- [cache2k](https://cache2k.org)-内存中的高性能缓存库。
- [Caffeine](https://github.com/ben-manes/caffeine)-高性能，接近最佳的缓存库。
- [Ehcache](http://www.ehcache.org)-分布式通用缓存。
- [Infinispan](https://infinispan.org)-用于缓存的高度并发的键/值数据存储。

### CLI
_ 与CLI相关的所有内容的库。_ 

- [ASCII Table](https://github.com/vdmeer/asciitable)-库以ASCII格式绘制表。
- [Airline](https://github.com/airlift/airline)-基于注释的框架，用于解析类似Git的命令行参数。
- [args4j](http://args4j.kohsuke.org)-用于解析命令行参数的小型库。
- [Jansi](https://github.com/fusesource/jansi)-ANSI转义代码格式化控制台输出。
- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render)-用于控制台的图形原语。
- [JCommander](http://jcommander.org)-命令行参数解析框架与自定义类型和验证通过实现接口。
- [jbock](https://github.com/jbock-java/jbock)-Reflectionless命令行解析器。
- [Jexer](https://gitlab.com/klamonte/jexer)-高级控制台 (和Swing) 文本用户界面 (TUI) 库，具有鼠标可拖动窗口，内置终端窗口管理器和sixel图像支持。看起来像[Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision)。
- [JLine](https://github.com/jline/jline3)-包括从现代炮弹，如完成或历史的功能。
- [JOpt Simple](https://jopt-simple.github.io/jopt-simple/)-使用POSIX # getopt和GNU # getopt_long语法的Fluent解析器。
- [picocli](https://picocli.info)-使用ANSI颜色和样式有助于基于注释的POSIX/GNU/any语法，子命令，选项和位置参数的强类型。
- [Text-IO](https://github.com/beryx/text-io)-帮助创建完整的基于控制台的应用程序。
- [Lanterna](https://github.com/mabe02/lanterna)-简单的控制台文本GUI库，类似于诅咒。(LGPL-3.0-only)

### 集群管理
_ 可以动态管理集群内的应用程序的框架。_ 

- [Apache Aurora](https://aurora.apache.org)-用于长时间运行的服务和cron作业的Mesos框架。
- [Singularity](http://getsingularity.com)-Mesos框架，使部署和操作变得容易。它支持web服务、后台工作人员、计划作业和一次性任务。

### 代码分析
_ 提供度量和质量度量的工具。_ 

- [Checkstyle](https://github.com/checkstyle/checkstyle)-编码约定和标准的静态分析。(LGPL-2.1-or-later)
- [Error Prone](https://github.com/google/error-prone)-捕获常见的编程错误作为编译时错误。
- [Error Prone Support](https://github.com/PicnicSupermarket/error-prone-support)-容易出错的扩展: 额外的错误检查器和大量的更快的模板。
- [Infer](https://github.com/facebook/infer)-现代静态分析工具，用于验证代码的正确性。
- [jQAssistant](https://jqassistant.org)-使用Neo4J-based查询语言进行静态代码分析。(GPL-3.0-only)
- [NullAway](https://github.com/uber/NullAway)-以低构建时开销消除NullPointerExceptions。
- [PMD](https://github.com/pmd/pmd)-用于查找不良编码实践的源代码分析。
- [p3c](https://github.com/alibaba/p3c)-提供阿里巴巴的PMD、IDEA和Eclipse的编码指南。
- [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)-识别并优先考虑上帝类和高度耦合类。
- [SonarJava](https://github.com/SonarSource/sonar-java)-SonarQube & SonarLint的静态分析仪。(LGPL-3.0-only)
- [Spoon](https://github.com/INRIA/spoon)-用于分析和转换Java源代码的库。
- [Spotbugs](https://github.com/spotbugs/spotbugs)-字节码的静态分析，以发现潜在的错误。(LGPL-2.1-only)

### 代码覆盖率
_ 为测试套件启用代码覆盖率指标收集的框架和工具。_ 

- [Clover](https://www.atlassian.com/software/clover)-依赖于源代码工具而不是字节码工具。
- [Cobertura](https://cobertura.github.io/cobertura/)-依靠离线 (或静态) 字节码检测和类加载来收集代码覆盖率指标。(GPL-2.0-only)
- [JaCoCo](https://www.eclemma.org/jacoco/)-允许使用离线和运行时字节码工具收集代码覆盖率指标的框架。

### 代码生成器
_ 为重复代码生成模式以减少冗长和错误倾向的工具。_ 

- [ADT4J](https://github.com/sviperll/adt4j)-代数数据类型的JSR-269代码生成器。
- [Auto](https://github.com/google/auto)-生成工厂、服务和值类。
- [Avaje Http Server](https://avaje.io/http/)-使用Javalin或Helidon (Nima) SE生成轻量级jax-rs样式的http服务器。
- [Bootify ![c]](https://bootify.io)-基于浏览器的Spring Boot应用程序生成，带有JPA模型和REST API。
- [FreeBuilder](https://github.com/inferred/FreeBuilder)-自动生成构建器模式。
- [Geci](https://github.com/verhas/javageci)-发现需要生成代码的文件，自动更新并使用方便的API写入源代码。
- [Immutables](https://immutables.github.io)-注释处理器生成简单，安全和一致的值对象。
- [JavaPoet](https://github.com/square/javapoet)-生成源文件的API。
- [JHipster](https://github.com/jhipster/generator-jhipster)-用于Spring Boot和AngularJS的Yeoman源代码生成器。
- [Joda-Beans](https://www.joda.org/joda-beans/)-为Java添加可查询属性的小框架，增强了JavaBeans。
- [JPA Buddy ![c]](https://www.jpa-buddy.com)-插件的IntelliJ的想法。提供用于生成JPA实体、Spring Data JPA存储库、Liquibase changelogs和SQL脚本的可视化工具。通过将模型与DB进行比较，并从DB表反向工程JPA实体，提供自动的Liquibase/Flyway脚本生成。
- [Lombok](https://projectlombok.org)-旨在减少冗长的代码生成器。
- [Record-Builder](https://github.com/Randgalt/record-builder)-同伴构建器类，Java记录的枯萎和模板。
- [Telosys](https://www.telosys.org/)-简单而轻便的代码生成器可作为Eclipse插件和CLI使用。

### 编译器-编译器
_ 帮助创建解析器、解释器或编译器的框架。_ 

- [ANTLR](https://www.antlr.org)-复杂的自上而下的解析功能齐全的框架。
- [JavaCC](https://javacc.github.io/javacc/)-生成自顶向下解析器的解析器生成器。允许词法状态切换，并允许扩展的BNF规范。
- [JFlex](https://jflex.de)-词法分析器生成器。

### 计算机视觉
_ 寻求从图像和视频中获取高级信息的库。_ 

- [BoofCV](https://boofcv.org)-用于图像处理，相机校准，跟踪，SFM，MVS，3D视觉，QR码等的库。
- [ImageJ](https://imagej.net/ImageJ)-具有API的医学图像处理应用程序。
- [JavaCV](https://github.com/bytedeco/javacv)-Java接口OpenCV，FFmpeg，以及更多。

### 配置
_ 提供外部配置的库。_ 

- [avaje config](https://avaje.io/config/)-加载yaml和属性文件，支持动态配置，插件，文件监视和配置事件侦听器。
- [centraldogma](https://github.com/line/centraldogma)-基于Git、ZooKeeper和HTTP/2的高可用版本控制服务配置库。
- [cfg4j](https://github.com/cfg4j/cfg4j)-用Java编写的分布式应用程序的现代配置库。
- [config](https://github.com/lightbend/config)-配置库支持Java属性，JSON或其人类优化的超集HOCON。
- [Configurate](https://github.com/SpongePowered/Configurate)-支持各种配置格式和转换的配置库。
- [Curator Framework](https://curator.apache.org/)-Apache ZooKeeper的高级API。
- [dotenv](https://github.com/shyiko/dotenv)-使用特定于环境的文件的十二因素配置库。
- [Externalized Properties](https://github.com/joel-jeremy/externalized-properties)-轻量级但功能强大的配置库，支持从外部源和可扩展的后处理/转换机制的属性的分辨率。
- [ini4j](http://ini4j.sourceforge.net)-提供用于处理windows的ini文件的API。
- [KAConf](https://github.com/mariomac/kaconf)-基于注释的Java和Kotlin配置系统。
- [microconfig](https://microconfig.io)-为微服务设计的配置系统，有助于将配置与代码分开。不同服务的配置可以具有公共和特定部分，并且可以动态分布。
- [owner](https://github.com/lviggiano/owner)-减少属性的样板。

### 约束满足问题求解器
_ 帮助实现优化和可满足性问题的库。_ 

- [Choco](https://choco-solver.org)-使用约束编程技术的现成的约束满足问题求解器。
- [JaCoP](https://github.com/radsz/jacop)-包括FlatZinc语言的接口，使其能够执行MiniZinc模型。(AGPL-3.0)
- [OptaPlanner](https://www.optaplanner.org)-业务计划和资源调度优化求解器。
- [Timefold](https://github.com/TimefoldAI/timefold-solver)-具有Spring/Quarkus支持和快速入门的灵活求解器，用于解决车辆路线问题，维护计划，员工轮班计划等。

### CSV
_ 简化读取/写入CSV数据的框架和库。_ 

- [FastCSV](https://github.com/osiegmar/FastCSV)-性能优化，无依赖和RFC 4180兼容。
- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv)-用于读取和写入CSV的Jackson扩展。
- [opencsv](http://opencsv.sourceforge.net)-简单的CSV解析器。
- [Super CSV](https://super-csv.github.io/super-csv/)-强大的CSV解析器，支持Dozer，joda-time和Java 8。
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)-最快和最完整的功能解析器之一。还带有用于TSV和固定宽度记录的解析器。

### 数据结构
_ 高效和具体的数据结构。_ 

- [Apache Avro](https://avro.apache.org)-具有动态类型，未标记数据以及缺少手动分配的id的数据交换格式。
- [Apache Orc](https://orc.apache.org)-快速高效的列式存储格式，适用于基于Hadoop的工作负载。
- [Apache Parquet](https://parquet.apache.org)-基于Google关于Dremel的论文中的汇编算法的列式存储格式。
- [Apache Thrift](https://thrift.apache.org)-起源于Facebook的数据交换格式。
- [Big Queue](https://github.com/bulldog2011/bigqueue)-基于内存映射文件的快速和持久队列。
- [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java)-用于在日志空间中计算并集，交集和集合基数的概率数据结构。
- [Persistent Collection](https://github.com/hrldcpr/pcollections)-Java集合框架的持久和不可变模拟。
- [Protobuf](https://github.com/protocolbuffers/protobuf)-Google的数据交换格式。
- [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap)-快速和高效的压缩位图。
- [SBE](https://github.com/real-logic/simple-binary-encoding)-简单的二进制编码，最快的消息格式之一。
- [Tape](https://github.com/square/tape)-闪电般快速，事务性，基于文件的FIFO。
- [Wire](https://github.com/square/wire)-干净，轻量级的协议缓冲区。

### 数据库
_ 简化与数据库交互的一切。_ 

- [Apache Calcite](https://calcite.apache.org)-动态数据管理框架。它包含许多组成典型数据库管理系统的部分。
- [Apache Drill](https://drill.apache.org)-用于大数据探索的分布式模式即时ANSI SQL查询引擎。
- [Apache Phoenix](https://phoenix.apache.org)-HBase上的高性能关系数据库层，用于低延迟应用程序。
- [ArangoDB](https://github.com/arangodb/arangodb-java-driver)-ArangoDB Java驱动程序。
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map)-高效、内存中 (opt.持久化到磁盘) 、堆外键值存储。
- [Debezium](https://debezium.io/)-用于更改数据捕获的低延迟数据流平台。
- [druid](https://druid.apache.org)-高性能，面向列的分布式数据存储。
- [eXist](https://github.com/eXist-db/exist)-NoSQL文档数据库和应用平台。(LGPL-2.1-only)
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool)-为最常见的连接池解决方案带来指标和故障转移策略。
- [Flyway](https://flywaydb.org)-简单的数据库迁移工具。
- [H2](https://h2database.com)-小型sql数据库以其内存功能而著称。
- [HikariCP](https://github.com/brettwooldridge/HikariCP)-高性能JDBC连接池。
- [HSQLDB](https://hsqldb.org/)-HyperSQL 100% Java数据库。
- [JDBI](http://jdbi.org)-JDBC的方便抽象。
- [Jedis](https://github.com/xetorthio/jedis)-用于与Redis交互的小客户端，具有用于命令的方法。
- [Jest](https://github.com/searchbox-io/Jest)-Elasticsearch REST API的客户端。
- [jetcd](https://github.com/justinsb/jetcd)-用于etcd的客户端库。
- [Jinq](https://github.com/my2iu/Jinq)-通过符号执行Java 8 Lambdas (在JPA或jOOQ之上) 进行类型安全数据库查询。
- [jOOQ](https://www.jooq.org)-基于SQL架构生成类型安全代码。
- [Leaf](https://github.com/Meituan-Dianping/Leaf)-分布式ID生成服务。
- [Lettuce](https://lettuce.io/)-生菜是一个可扩展的Redis客户端，用于构建非阻塞反应式应用程序。
- [Liquibase](http://www.liquibase.org)-独立于数据库的库，用于跟踪，管理和应用数据库模式更改。
- [MapDB](http://www.mapdb.org)-嵌入式数据库引擎，提供备份在磁盘或堆外内存中的并发集合。
- [MariaDB4j](https://github.com/vorburger/MariaDB4j)-MariaDB的启动器，不需要安装或外部依赖。
- [Modality](https://github.com/arkanovicz/modality)-具有数据库逆向工程功能的轻量级ORM。
- [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)-为Java平台开发的符合LDAPv3的目录服务，为身份提供高性能、高可用性和安全的存储。
- [Querydsl](http://www.querydsl.com)-Typesafe统一查询。
- [QueryStream](https://github.com/querystream/querystream)-使用类似流的API构建JPA标准查询。
- [QuestDB](https://github.com/questdb/questdb)-用于时间序列的高性能sql数据库。支持InfluxDB line协议、PostgreSQL wire协议和REST。
- [Realm](https://github.com/realm/realm-java)-移动数据库直接在手机，平板电脑或可穿戴设备中运行。
- [Redisson](https://github.com/redisson/redisson)-允许在Redis服务器上使用分布式和可扩展的数据结构。
- [requery](https://github.com/requery/requery)-现代，轻量级但功能强大的对象映射和SQL生成器。轻松映射或创建数据库，或从任何使用Java的平台执行查询和更新。
- [Speedment](https://github.com/speedment/speedment)-利用Java 8的Stream API进行查询的数据库访问库。
- [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions)-允许您使用MongoDB查询语言来查询您的关系数据库。
- [Trino](https://trino.io)-用于大数据的分布式SQL查询引擎。
- [Vibur DBCP](https://www.vibur.org)-具有高级性能监控功能的JDBC连接池库。
- [Xodus](https://github.com/JetBrains/xodus)-高度并发的无事务模式和符合ACID的嵌入式数据库。
- [CosId](https://github.com/Ahoo-Wang/CosId)-通用，灵活，高性能的分布式ID生成器。

### 日期和时间
_ 与处理日期和时间相关的库。_ 

- [iCal4j](https://github.com/ical4j/ical4j)-解析和构建iCalendar[RFC 5545](https://tools.ietf.org/html/rfc5545)数据模型。
- [Jollyday](https://github.com/svendiedrichsen/jollyday)-确定给定年份，国家/地区和最终州/地区的假期。
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra)-补充JDK 8中的日期时间类。
- [Time4J](https://github.com/MenoData/Time4J)-先进的日期和时间库。(LGPL-2.1-only)

### 依赖注入
_ 有助于实现[Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm._ 

- [Apache DeltaSpike](https://deltaspike.apache.org)-CDI扩展框架。
- [Avaje Inject](https://avaje.io/inject/)-专注于微服务的编译时注入框架，无需反射。
- [Dagger](https://dagger.dev/)-没有反射的编译时注入框架。
- [Feather](https://github.com/zsoltherpai/feather)-超轻量级，JSR-330-compliant依赖注入库。
- [Governator](https://github.com/Netflix/governator)-增强Google Guice的扩展和实用程序。
- [Guice](https://github.com/google/guice)-轻量级和固执己见的框架，完成匕首。
- [HK2](https://javaee.github.io/hk2/)-轻量级和动态依赖注入框架。
- [JayWire](https://github.com/vanillasource/jaywire)-轻量级的依赖注入框架。(LGPL-3.0-only)

### 发展
_ 在基本层面上增强开发过程。_ 

- [AspectJ](https://www.eclipse.org/aspectj/)-无缝的面向方面的编程扩展。
- [DCEVM](https://dcevm.github.io)-JVM修改，允许在运行时无限制地重新定义加载的类。(GPL-2.0-only)
- [Faux Pas](https://github.com/zalando/faux-pas)-库，通过规避默认情况下不允许Java运行时中的任何函数式接口抛出检查异常的问题，简化了错误处理。
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)-无限的运行时类和资源重新定义。(GPL-2.0-only)
- [JavaParser](https://github.com/javaparser/javaparser)-解析，修改和生成Java代码。
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver)-符号求解器。
- [Manifold](https://github.com/manifold-systems/manifold)-重新激发Java强大的功能，如类型安全元编程，结构类型和扩展方法。
- [NoException](https://noexception.machinezoo.com)-允许在函数式接口中检查异常，并将异常转换为可选返回。
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)-忽略没有字节码操作的检查异常。也可以在Java 8流操作中使用。
- [Tail](https://nrktkt.github.io/tail/)-使用尾调用优化启用无限递归。

### 分布式应用程序
_ 用于编写分布式和容错应用程序的库和框架。_ 

- [Apache Geode](https://geode.apache.org)-内存数据管理系统，提供可靠的异步事件通知和保证消息传递。
- [Apache Storm](https://storm.apache.org)-实时计算系统。
- [Apache ZooKeeper](https://zookeeper.apache.org)-具有用于大型分布式系统的分布式配置，同步和命名注册表的协调服务。
- [Atomix](https://atomix.io)容错分布式协调框架。
- [Axon](https://axoniq.io)-用于创建CQRS应用程序的框架。
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker)-Dropwizard的断路器设计模式。(GPL-2.0-only)
- [Failsafe](https://github.com/jhalterman/failsafe)-简单的故障处理与重试和断路器。
- [Hazelcast](https://github.com/hazelcast/hazelcast)-具有免费开源版本的高度可扩展的内存datagrid。
- [JGroups](http://www.jgroups.org)-用于可靠消息传递和集群创建的工具包。
- [Quasar](http://docs.paralleluniverse.co/quasar/)-JVM的轻量级线程和actor。
- [resilience4j](https://github.com/resilience4j/resilience4j)功能容错库。
- [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG)-高性能反向代理服务器，具有专门的会话管理和凭据重放功能。
- [ScaleCube Services](https://github.com/scalecube/scalecube-services)-基于SWIM和gossip协议的嵌入式集群成员库。
- [Zuul](https://github.com/Netflix/zuul)-提供动态路由、监控、弹性、安全性等功能的网关服务。

### 分布式事务
_ 分布式事务提供了一种机制，用于在存在并发访问和部分故障的情况下确保数据更新的一致性。_ 

- [Atomikos](https://www.atomikos.com)-为REST，SOA和微服务提供事务，并支持JTA和XA。
- [Bitronix](https://github.com/bitronix/btm)-JTA 1.1 API的简单但完整的实现。
- [Narayana](https://narayana.io)-为传统的ACID和补偿交易提供支持，还符合JTA，JTS和其他标准。(LGPL-2.1-only)
- [Seata](https://github.com/seata/seata)-在微服务架构下提供高性能和易于使用的分布式事务服务。

### 分布
_ 处理以本机格式分发应用程序的工具。_ 

- [Artipie](https://github.com/artipie/artipie)-二进制工件管理工具包，将它们托管在文件系统或s3上。
- [Boxfuse ![c]](https://boxfuse.com)-使用不可变基础设施的原则将JVM应用程序部署到AWS。
- [Capsule](https://github.com/puniverse/capsule)-简单而强大的打包和部署。类固醇上的胖罐子，或者支持JVM优化容器的 “Java Docker”。
- [Central Repository](https://search.maven.org)-最大的二进制组件存储库可作为免费服务提供给开源社区。默认由Apache Maven使用，并在所有其他构建工具中可用。
- [Cloudsmith ![c]](https://cloudsmith.io)-完全托管的软件包管理SaaS，支持具有免费层的Maven/Gradle/SBT。
- [Getdown](https://github.com/threerings/getdown)-用于将Java应用程序部署到最终用户计算机并使其保持最新状态的系统。作为Java Web Start的替代方案而开发。
- [IzPack](http://izpack.org)-用于跨平台部署的设置创作工具。
- [JavaPackager](https://github.com/fvarrui/JavaPackager)-Maven和Gradle插件，它提供了一种简单的方法来在本机Windows，Mac OS X或GNU/Linux可执行文件中打包Java应用程序，并为它们生成安装程序。
- [jDeploy](https://www.jdeploy.com)-将桌面应用程序部署为本机Mac，Windows或Linux捆绑包。
- [jlink.online](https://github.com/AdoptOpenJDK/jlink.online)-通过HTTP构建优化的运行时。
- [Nexus ![c]](https://www.sonatype.com)-具有代理和缓存功能的二进制管理。
- [packr](https://github.com/libgdx/packr)-打包jar，资产和JVM，以便在Windows，Linux和macOS上进行本机分发。
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin)-用于制作自执行jar的Maven插件。

### 文档处理
_ 协助处理office文档格式的库。_ 

- [Apache POI](https://poi.apache.org)-支持OOXML (XLSX，DOCX，PPTX) 以及OLE2 (XLS，DOC或PPT)。
- [documents4j](https://documents4j.com/#/)-使用第三方转换器 (如MS Word) 进行文档格式转换的API。
- [docx4j](https://www.docx4java.org/trac/docx4j)-创建和操作Microsoft Open XML文件。
- [fastexcel](https://github.com/dhatim/fastexcel)-高性能库读取和写入大型Excel (XLSX) 工作表。
- [zerocell](https://github.com/creditdatamw/zerocell)-基于注释的API，用于将数据从Excel工作表读取到pojo中，重点是减少开销。

### 财务
_ 与金融领域相关的库。_ 

- [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot)-交易bot框架。
- [Parity](https://github.com/paritytrading/parity)-交易场所平台。
- [Philadelphia](https://github.com/paritytrading/philadelphia)-低延迟的金融信息交换。
- [Square](https://github.com/square/connect-java-sdk)-与Square API集成。
- [Stripe](https://github.com/stripe/stripe-java)-与Stripe API集成。
- [ta4j](https://github.com/ta4j/ta4j)-技术分析库。

### 形式验证
_ 形式方法工具: 证明助手、模型检查、符号执行等。_ 

- [CATG](https://github.com/ksen007/janala2)-Concoric单元测试引擎。使用正式方法自动生成单元测试。
- [Checker Framework](https://checkerframework.org)-可插拔类型的系统。包括无效类型、物理单位、不变性类型等。(与Classpath-exception-2.0 GPL-2.0-only)
- [Daikon](https://plse.cs.washington.edu/daikon/)-检测可能的程序不变量，并根据这些不变量生成JML规范。
- [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core)-包含模型检查器等的JVM形式验证工具。由NASA创建。
- [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok)-通过反馈导向的随机测试生成来检测代码和JML规范之间的不一致，并建议检测到的每个不一致的可能原因。(GPL-3.0-only)
- [KeY](https://www.key-project.org)-正式的软件开发工具，旨在尽可能无缝地集成面向对象软件的设计，实现，正式规范和形式验证。使用JML规范和符号执行验证。(GPL-2.0-or-later)
- [OpenJML](http://www.openjml.org)-将JML规范转换为smt-lib格式，并将程序暗示的证明问题传递给后端求解器。(GPL-2.0-only)

### 函数式编程
_ 便于函数式编程的库。_ 

- [Cyclops](https://github.com/aol/cyclops)-Monad和流实用程序，理解，模式匹配，所有JDK集合的功能扩展，未来流，蹦床等等。
- [derive4j](https://github.com/derive4j/derive4j)-Java 8注释处理器和框架，用于导出代数数据类型构造函数，模式匹配和态射。(GPL-3.0-only)
- [Fugue](https://bitbucket.org/atlassian/fugue)-对Guava的功能扩展。
- [Functional Java](http://www.functionaljava.org)-实现了许多基本和高级编程抽象，有助于面向组合的开发。
- [jOOλ](https://github.com/jOOQ/jOOL)-Java 8的扩展，旨在通过提供大量缺失的类型和一组丰富的顺序流API添加来修复lambda中的差距。
- [protonpack](https://github.com/poetix/protonpack)-流实用程序的集合。
- [StreamEx](https://github.com/amaembo/streamex)-增强Java 8流。
- [Vavr](https://www.vavr.io)-提供持久数据类型和功能控制结构的功能组件库。

### 游戏开发
_ 支持游戏开发的框架。_ 

- [FXGL](https://almasb.github.io/FXGL/)JavaFX游戏开发框架。
- [JBox2D](http://www.jbox2d.org/)-著名的C 2D物理引擎的端口。
- [jMonkeyEngine](https://jmonkeyengine.org)-现代3D开发的游戏引擎。
- [libGDX](https://libgdx.com)-全方位跨平台，高层次的框架。
- [Litiengine](https://litiengine.com/)-基于AWT的轻量级2D游戏引擎。
- [LWJGL](https://www.lwjgl.org)-抽象像OpenGL/CL/AL这样的库的健壮框架。
- [Mini2Dx](https://mini2dx.org)-初学者友好，掌握快速原型和构建2D游戏的框架。
- [Void2D](https://github.com/xzripper/Void2D)-基于Swing的内置物理的高级2D游戏引擎。

### 地理空间
_ 用于处理地理空间数据和算法的库。_ 

- [Apache SIS](https://sis.apache.org)-开发地理空间应用程序的库。
- [Geo](https://github.com/davidmoten/geo)-Java中的GeoHash实用程序。
- [GeoTools](https://geotools.org)-提供地理空间数据工具的库。(LGPL-2.1-only)
- [GraphHopper](https://github.com/graphhopper/graphhopper)-道路路由引擎。用作Java库或独立的web服务。
- [H2GIS](http://www.h2gis.org)-H2数据库的空间扩展。(LGPL-3.0-only)
- [Jgeohash](https://astrapi69.github.io/jgeohash/)-使用GeoHash算法的库。
- [Mapsforge](https://github.com/mapsforge/mapsforge)基于OpenStreetMap数据的地图渲染。(LGPL-3.0-only)
- [Spatial4j](https://github.com/locationtech/spatial4j)-通用空间/地理空间库。

### 图形用户界面
_ 库来创建现代图形用户界面。_ 

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main)-Swing的继任者.
- [Scene Builder](https://gluonhq.com/products/scene-builder/)-JavaFX应用程序的可视化布局工具。
- [SWT](https://www.eclipse.org/swt/)-图形小部件工具包。

### 高性能
_ 关于高性能计算的一切，从集合到特定的库。_ 

- [Agrona](https://github.com/real-logic/Agrona)-高性能应用程序中常见的数据结构和实用程序方法。
- [Disruptor](https://lmax-exchange.github.io/disruptor/)-线程间消息传递库
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections)-受Smalltalk启发的集合框架。
- [fastutil](http://fastutil.di.unimi.it)-快速和紧凑的特定类型的集合。
- [HPPC](https://labs.carrotsearch.com/hppc.html)-原始集合。
- [JCTools](https://github.com/JCTools/JCTools)-JDK中当前缺少的并发工具。
- [Koloboke](https://github.com/leventov/Koloboke)-精心设计的Java集合框架的扩展，具有原始的专业化和更多。

### HTTP客户端
_ 帮助创建HTTP请求和/或绑定响应的库。_ 

- [Apache HttpComponents](https://hc.apache.org/)-专注于HTTP和相关协议的低级Java组件的工具集。
- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)-异步HTTP和WebSocket客户端库。
- [Avaje Http Client](https://avaje.io/http-client)-JDK 11的HttpClient上的包装器，在其他增强功能中添加了类似Feign的接口。
- [Feign](https://github.com/OpenFeign/feign)-受改造，JAXRS-2.0和WebSocket启发的HTTP客户端绑定器。
- [Google HTTP Client](https://github.com/googleapis/google-http-java-client)-支持r java.net的可插拔HTTP传输抽象。HttpURLConnection，Apache HTTP客户端，Android，Google App Engine，XML，Gson，Jackson和Protobuf。
- [methanol](https://github.com/mizosoft/methanol)-HTTP客户端扩展库。
- [Retrofit](https://square.github.io/retrofit/)-Typesafe REST客户端。
- [Ribbon](https://github.com/Netflix/ribbon)-在云中经过战斗测试的客户端IPC库。
- [Riptide](https://github.com/zalando/riptide)-Spring的RestTemplate的客户端响应路由。
- [unirest-java](https://github.com/Kong/unirest-java)-简化，轻量级的HTTP客户端库。

### 超媒体类型
_ 处理超媒体类型序列化的库。_ 

- [hate](https://github.com/blackdoor/hate)-根据HAL规范构建超媒体友好的对象。
- [JSON-LD](https://github.com/jsonld-java/jsonld-java)-JSON-LD实现。
- [Siren4J](https://github.com/eserating-chwy/siren4j)-警报器规范库。

### IDE
_ 集成开发环境，试图简化开发的几个方面。_ 

- [Eclipse](https://www.eclipse.org)-建立了支持大量插件和语言的开源项目。
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/)-支持许多JVM语言，并为Android开发提供了很好的选择。商业版针对企业部门。
- [jGRASP](https://www.jgrasp.org)-创建以提供与调试器一起工作的软件可视化，例如控制结构图，UML类图和对象查看器。
- [NetBeans](https://netbeans.apache.org)-提供几个Java SE和EE功能的集成，从数据库访问到html5。
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java)-通过使用内部市场的扩展，为轻量级项目提供Java支持，并提供简单的现代工作流。

### 图像
_ 帮助创建、评估或处理图形图像的库。_ 

- [Imgscalr](https://github.com/rkalla/imgscalr)-在纯Java 2D中实现的简单，高效和硬件加速的图像缩放库。
- [Tess4J](https://github.com/nguyenq/tess4j)-Tesseract OCR API的JNA包装器。
- [Thumbnailator](https://github.com/coobird/thumbnailator)-高质量的缩略图生成库。
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)-扩展支持的图像文件格式数量的插件集合。
- [ZXing](https://github.com/zxing/zxing)-多格式1D/2D条码图像处理库。
- [image-comparison](https://github.com/romankh3/image-comparison)-比较具有相同大小的2个图像的库，并通过绘制矩形在视觉上显示差异。可以从比较中排除图像的一些部分。

### 内省
_ 有助于使Java自省和反射API更容易和更快地使用的库。_ 

- [ClassGraph](https://github.com/classgraph/classgraph)ClassGraph (以前称为FastClasspathScanner) 是用于Java，Scala，Kotlin和其他JVM语言的超快，超轻，并行化的类路径扫描仪和模块扫描仪。
- [jOOR](https://github.com/jOOQ/jOOR)jOOR代表jOOR面向对象的反射。它是java.lang.reflect包的简单包装。
- [Mirror](http://projetos.vidageek.net/mirror/mirror/)-Mirror的创建是为了解决一个简单的问题，通常将其命名为ReflectionUtil，该问题几乎适用于所有依靠反射来执行高级任务的项目。
- [Objenesis](http://objenesis.org)-允许没有默认构造函数的动态实例化，例如具有所需参数，副作用或抛出异常的构造函数。
- [ReflectASM](https://github.com/EsotericSoftware/reflectasm)-ReflectASM是一个非常小的Java库，通过使用代码生成提供高性能反射。
- [Reflections](https://github.com/ronmamo/reflections)-反射扫描您的类路径，索引元数据，允许您在运行时查询它，并可以保存和收集项目中许多模块的信息。

### 作业调度
_ 用于调度后台作业的库。_ 

- [JobRunr](https://github.com/jobrunr/jobrunr)-作业调度库，它利用lambdas进行fire-and-forget，延迟和重复的作业。使用乐观锁定保证由单个调度程序实例执行。具有持久性，最小依赖性和可嵌入的功能。
- [Quartz](https://github.com/quartz-scheduler/quartz)-功能丰富的开源作业调度库，可以集成在几乎任何Java应用程序中。
- [Sundial](https://github.com/knowm/Sundial)-轻量级框架，简单地定义作业，定义触发器和启动调度程序。
- [Wisp](https://github.com/Coreoz/Wisp)-具有最小的占用空间和简单的API的简单库。
- [db-scheduler](https://github.com/kagkarlsson/db-scheduler)-持久和群集友好的调度程序。
- [easy-batch](https://github.com/j-easy/easy-batch)-使用简单的处理管道设置批处理作业。记录从数据源按顺序读取，在管道中处理并批量写入数据接收器。
- [shedlock](https://github.com/lukas-krecan/ShedLock)-确保您的计划任务在同一时间最多执行一次。如果任务正在一个节点上执行，则它获取一个锁，该锁阻止从另一个节点或线程执行相同的任务。

### JSON
_ 用于将JSON与Java对象进行序列化和反序列化的库。_ 

- [Avaje Jsonb](https://avaje.io/jsonb/)-通过使用类似Jackson的注释生成源代码进行无反射的Json绑定。
- [DSL-JSON](https://github.com/ngs-doo/dsl-json)-具有高级编译时数据绑定的JSON库。
- [Genson](http://genson.io)-功能强大且易于使用的Java到JSON转换库。
- [Gson](https://github.com/google/gson)-将对象序列化为JSON，反之亦然。良好的性能与飞行使用。
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON)-高性能JSON解析器，比杰克逊快2倍。
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8)-用于Java 8数据类型和功能的Jackson模块集。
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money)-开源Jackson模块，支持JavaMoney数据类型的JSON序列化和反序列化。
- [Jackson](https://github.com/FasterXML/jackson)-与GSON类似，但如果您需要更频繁地实例化库，则可以提供性能提升。
- [JSON-io](https://github.com/jdereg/json-io)-将Java转换为JSON。将JSON转换为Java。漂亮的打印JSON。Java JSON序列化程序。
- [jsoniter](http://jsoniter.com)-快速和灵活的库与迭代器和惰性解析API。
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare)-基于Jackson的流API的JSON解析和序列化库。胜过GSON & Jackson的库。
- [Moshi](https://github.com/square/moshi)-现代JSON库，不太固执己见，并使用内置类型，如列表和地图。
- [Yasson](https://github.com/eclipse-ee4j/yasson)-类和JSON文档之间的绑定层，类似于JAXB。
- [fastjson](https://github.com/alibaba/fastjson)-非常快速的处理器，没有额外的依赖关系和完整的数据绑定。
- [Jolt](https://github.com/bazaarvoice/jolt)-JSON到JSON转换工具。
- [JsonPath](https://github.com/json-path/JsonPath)-使用类似XPATH的语法从JSON中提取数据。
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer)-流JsonPath处理器专用于处理大而复杂的JSON数据。

### JVM和JDK
_ JVM/JDK的当前实现。_ 

- [Adopt Open JDK](https://adoptopenjdk.net)-社区驱动的OpenJDK构建，包括HotSpot和openj9。
- [Avian](https://github.com/ReadyTalk/avian)-JVM与JIT，AOT模式和iOS端口。
- [Corretto](https://aws.amazon.com/corretto/)-亚马逊的OpenJDK的无成本，多平台，生产就绪分发。(与Classpath-exception-2.0 GPL-2.0-only)
- [Dragonwell8](https://github.com/alibaba/dragonwell8)-OpenJDK的下游版本，针对在线电子商务，金融，物流应用进行了优化。
- [Graal](https://github.com/oracle/graal)-多语言可嵌入JVM。(与Classpath-exception-2.0 GPL-2.0-only)
- [Liberica JDK](https://bell-sw.com)-从OpenJDK构建，经过全面测试并通过了JCK。(与Classpath-exception-2.0 GPL-2.0-only)
- [OpenJ9](https://github.com/eclipse/openj9)-高性能，企业级，灵活许可，开放管理的跨平台JVM，扩展和增强了Eclipse OMR和OpenJDK项目的运行时技术组件。
- [Open JDK](https://openjdk.java.net)-打开JDK社区主页。(与Classpath-exception-2.0 GPL-2.0-only)
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)-VM与非阻塞，并发GC的iOS。(与Classpath-exception-2.0 GPL-2.0-only)
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview)-RedHat的OpenJDK发行版。(与Classpath-exception-2.0 GPL-2.0-only)
- [SAP Machine](https://sap.github.io/SapMachine/)-SAP的无成本，经过严格测试和JCK验证的OpenJDK友好叉。(与Classpath-exception-2.0 GPL-2.0-only)
- [Zulu](https://www.azul.com/products/zulu-community/)-适用于Windows、Linux和macOS的OpenJDK版本。(与Classpath-exception-2.0 GPL-2.0-only)

### 日志记录
_ 记录应用程序行为的库。_ 

- [Apache Log4j 2](https://logging.apache.org/log4j/)-使用强大的插件和配置架构完成重写。
- [Echopraxia](https://github.com/tersesystems/echopraxia)-围绕结构化日志记录，丰富的上下文和条件日志记录设计的API。有Logback和Log4J2实现，但echoprawia的API是完全无依赖关系的，这意味着它可以用任何日志API实现。
- [Graylog](https://www.graylog.org)-适合扩展角色和权限管理的开源聚合器。(GPL-3.0-only)
- [Kibana](https://www.elastic.co/kibana)-分析和可视化日志文件。某些功能需要付款。
- [Logback](http://logback.qos.ch)-健壮的日志库，通过Groovy提供有趣的配置选项。
- [Logbook](https://github.com/zalando/logbook)-用于HTTP请求和响应日志记录的可扩展的开源库。
- [Logstash](https://www.elastic.co/logstash)-用于管理日志文件的工具。
- [p6spy](https://github.com/p6spy/p6spy)-启用所有JDBC事务的日志记录，而无需更改代码。
- [SLF4J](http://www.slf4j.org)-抽象层/简单日志记录立面。
- [tinylog](https://tinylog.org/v2/)-具有静态记录器类的轻量级日志记录框架。
- [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox)-建立在OpenTracing之上的库集合，并为现有仪器提供扩展和插件。

### 机器学习
_ 提供用于从数据中学习的特定统计算法的工具。_ 

- [Apache Flink](https://flink.apache.org)-快速，可靠，大规模数据处理引擎。
- [Apache Mahout](https://mahout.apache.org)-专注于协同过滤，聚类和分类的可扩展算法。
- [DatumBox](http://www.datumbox.com)-为自然语言处理提供几种算法和预训练模型。
- [Deeplearning4j](https://deeplearning4j.org)-分布式和多线程深度学习库。
- [DJL](https://djl.ai)-用于深度学习的高级和引擎无关的框架。
- [H2O ![c]](https://www.h2o.ai)-大数据统计分析引擎。
- [Intelligent java](https://github.com/Barqawiz/IntelliJava)-以编程方式与远程深度学习和语言模型无缝集成。
- [JSAT](https://github.com/EdwardRaff/JSAT)-用于预处理、分类、回归和聚类的算法，支持多线程执行。(GPL-3.0-only)
- [m2cgen](https://github.com/BayesWitnesses/m2cgen)-CLI工具将模型转换为本机代码。
- [oj! Algorithms](https://www.ojalgo.org/)-数据科学，机器学习和科学计算所需的高性能数学，线性代数和优化。
- [Oryx 2](https://github.com/OryxProject/oryx)-用于构建实时，大规模机器学习应用程序的框架。包括用于协同过滤、分类、回归和聚类的端到端应用程序。
- [Siddhi](https://github.com/siddhi-io/siddhi)-云原生流和复杂事件处理引擎。
- [Smile](https://github.com/haifengl/smile)-统计机器智能和学习引擎提供了一套机器学习算法和一个可视化库。
- [Tribuo](https://tribuo.org/)-提供用于分类，回归，聚类，模型开发的工具以及与其他库 (如scikit-learn，pytorch和TensorFlow) 的接口。
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/)-从预处理到可视化的数据挖掘任务的算法集合。(GPL-3.0-only)

### 消息传递
_ 帮助在客户端之间发送消息以确保协议独立性的工具。_ 

- [Aeron](https://github.com/real-logic/Aeron)-高效，可靠，单播和多播消息传输。
- [Apache ActiveMQ](https://activemq.apache.org)-实现JMS并将同步通信转换为异步通信的Message broker。
- [Apache Camel](https://camel.apache.org)-通过企业集成模式将不同的传输api粘合在一起。
- [Apache Kafka](https://kafka.apache.org)-高吞吐量分布式消息传递系统。
- [Apache Pulsar](https://pulsar.apache.org)-分布式pub/sub消息系统。
- [Apache RocketMQ](https://rocketmq.apache.org)-快速，可靠和可扩展的分布式消息传递平台。
- [Apache Qpid](https://qpid.apache.org)-Apache Qpid使消息工具讲AMQP并支持多种语言和平台。
- [Deezpatch](https://github.com/joel-jeremy/deezpatch)-用于解耦消息 (请求和事件) 和消息处理程序的简单，轻量级和高性能的调度库。
- [EventBus](https://github.com/greenrobot/EventBus)-简单的发布/订阅事件总线。
- [Hermes](http://hermes.allegro.tech)-建立在Kafka之上的快速可靠的消息代理。
- [JeroMQ](https://github.com/zeromq/jeromq)-实现ZeroMQ。
- [Nakadi](https://github.com/zalando/nakadi)-在Kafka之上提供一个RESTful API。
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client)-RabbitMQ客户端。
- [Smack](https://github.com/igniterealtime/Smack)跨平台XMPP客户端库。
- [NATS client](https://github.com/nats-io/nats.java)-NATS的客户.

### 微服务
_ 用于创建和管理微服务的工具。_ 

- [ActiveRPC](https://rpc.activej.io)-轻量级和快速的库，用于复杂的高负载分布式应用程序和类似Memcached的解决方案。
- [Apollo](https://spotify.github.io/apollo/)-用于编写可组合微服务的库。
- [Armeria](https://github.com/line/armeria)-基于Java 8，Netty，HTTP/2，Thrift和gRPC构建的异步RPC/REST客户端/服务器库。
- [consul-api](https://github.com/Ecwid/consul-api)-Consul API的客户端: 分布式、高可用性和数据中心感知的注册/发现服务。
- [Eureka](https://github.com/Netflix/eureka)-基于REST的服务注册表，用于弹性负载平衡和故障转移。
- [Helidon](https://helidon.io)-用于编写微服务的两种风格的方法: 功能反应式和作为MicroProfile的实现。
- [JDA](https://github.com/DV8FromTheWorld/JDA)-包装Discord REST API及其WebSocket事件。
- [KeenType](https://github.com/DaveJarvis/KeenType)-新排版系统的基于Java的实现的现代化版本，该版本在很大程度上基于Donald E. Knuth的原始TeX。
- [kubernetes-client](https://github.com/fabric8io/kubernetes-client)-客户端通过流畅的DSL提供对完整Kubernetes和OpenShift REST api的访问。
- [Micronaut](https://micronaut.io)-现代全栈框架，专注于模块化，最小的内存占用和启动时间。
- [Nacos](https://nacos.io)-用于构建云原生应用的动态服务发现、配置和服务管理平台。
- [OpenAI-Java](https://github.com/TheoKanning/openai-java)-用于使用OpenAI GPT-3 API的Java库。
- [Quarkus](https://quarkus.io)-为HotSpot和Graal VM量身定制的Kubernetes堆栈。
- [Sentinel](https://github.com/alibaba/Sentinel)-流量控制组件，实现微服务的可靠性、弹性和监控。

### 杂项
_ 其他一切。_ 

- [AWS SDK for Java 2.0](https://github.com/aws/aws-sdk-java-v2)-围绕aws的API进行包装。
- [CQEngine](https://github.com/npgall/cqengine)-Java集合上的超快速，类似SQL的查询。
- [Design Patterns](https://github.com/iluwatar/java-design-patterns)-最常见的设计模式的实现和解释。
- [FF4J](https://github.com/ff4j/ff4j)-Java的功能标志。
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)-认真的商人为严肃的商业目的而制造的FizzBuzz的废话。(无明确许可)
- [J2ObjC](https://github.com/google/j2objc)-用于将Android库移植到iOS的Java到objective-c转换器。
- [JBake](https://jbake.org)-静态网站生成器。
- [JBot](https://github.com/rampatra/jbot)-构建聊天机器人的框架。(GPL-3.0-only)
- [JCuda](http://jcuda.org)-JCuda为CUDA和与CUDA相关的库提供Java绑定。
- [Jimfs](https://github.com/google/jimfs)-内存文件系统。
- [JObfuscator![c]](https://www.pelock.com/products/jobfuscator)-源代码混淆器。
- [Joda-Money](https://www.joda.org/joda-money/)-JDK未提供的基本货币和货币类和算法。
- [jOOX](https://github.com/jooq/joox)-org.w3c.dom包的简单包装器，允许使用受jQuery启发的API进行流畅的XML文档创建和操作。
- [JPad](http://jpad.io)-片段赛跑者.
- [jsweet](https://github.com/cincheo/jsweet)-源转换器到TypeScript/JavaScript。
- [Maven Wrapper](https://github.com/takari/maven-wrapper)-Maven的Gradle包装器的模拟，允许在不安装maven的情况下构建项目。
- [Membrane Service Proxy](https://github.com/membrane/service-proxy)-开源，反向代理框架。
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP)-轻量级，小型和可定制的FTP服务器。
- [LittleProxy](https://github.com/adamfisk/LittleProxy)-在Netty的基于事件的网络库之上的高性能HTTP代理。
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial)-流行的Java 8指南。
- [Modernizer](https://github.com/gaul/modernizer-maven-plugin)-检测遗留Java api的使用。
- [OctoLinker](https://github.com/OctoLinker/OctoLinker)-浏览器扩展，允许更有效地浏览GitHub上的代码。
- [OpenRefine](http://openrefine.org)-用于处理凌乱数据的工具: 清理，转换，使用web服务扩展它并将其链接到数据库。
- [PipelinR](https://github.com/sizovs/pipelinr)-小型实用程序库，用于使用处理程序和带有管道的命令。
- [Polyglot for Maven](https://github.com/takari/polyglot-maven)-Maven 3.3.1的扩展，允许用XML以外的方言编写POM模型。
- [RR4J](https://github.com/Kartikvk1996/RR4J)-RR4J是一个记录java字节码执行的工具，后来允许开发人员在本地重放。
- [Simple Java Mail](https://github.com/bbottema/simple-java-mail)-邮寄一个干净和流畅的API。
- [Smooks](https://github.com/smooks/smooks)-基于片段的消息处理框架。(Apache-2.0或LGPL-3.0-or-later)
- [Svix](https://github.com/svix/svix-webhooks/tree/main/java)-用于Svix API的库，用于发送webhook并验证签名。
- [Togglz](https://www.togglz.org)-功能切换模式的实现。
- [TypeTools](https://github.com/jhalterman/typetools)-用于解析泛型类型的工具。
- [XMLBeam](https://github.com/SvenEwald/xmlbeam)-通过在代码中使用注释或XPath来处理XML。
- [yGuard](https://github.com/yWorks/yGuard)-通过重命名和收缩混淆。

### 移动开发
_ 用于创建或管理移动应用程序的工具。_ 

- [Codename One](https://www.codenameone.com)-用于编写本地移动应用程序的跨平台解决方案。(与Classpath-exception-2.0 GPL-2.0-only)
- [MobileUI](https://mobileui.dev)-跨平台框架，用于在Java和Kotlin中开发具有本机UI的移动应用程序。
- [Multi-OS Engine](https://multi-os-engine.org)-开源，跨平台引擎，用于开发本地移动 (iOS，Android等) 应用程序。

### 监测
_ 监视生产中的应用程序的工具。_ 

- [Automon](https://github.com/stevensouza/automon)-将AOP的功能与监视和/或日志记录工具相结合。
- [Failsafe Actuator](https://github.com/zalando/failsafe-actuator)-Spring-Boot环境中的故障安全断路器的开箱即用监控。
- [Glowroot](https://glowroot.org)-开源Java APM。
- [HertzBeat](https://github.com/dromara/hertzbeat)-具有自定义监视器和无代理功能的实时监视系统。
- [inspectIT](https://www.inspectit.rocks)-通过钩子捕获详细的运行时信息，可以在飞行中更改。它支持通过OpenTracing API跟踪多个系统，并可以将数据与最终用户监控相关联。
- [Instrumental ![c]](https://instrumentalapp.com)-实时Java应用程序性能监控。具有免费开发帐户的商业服务。
- [JavaMelody](https://github.com/javamelody/javamelody)-性能监控和分析。
- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java)-Jaeger客户.
- [jmxtrans](https://github.com/jmxtrans/jmxtrans)-连接到多个jvm并通过JMX查询它们的属性。它的查询语言基于JSON，允许非Java程序员访问JVM属性。支持不同的输出写入，包括Graphite、Ganglia和StatsD。
- [Jolokia](https://jolokia.org)-JMX over REST.
- [Metrics](https://github.com/dropwizard/metrics)-通过JMX或HTTP公开指标，并将其发送到数据库。
- [Datadog ![c]](https://github.com/DataDog/dd-trace-java)-现代监控和分析。
- [nudge4j](https://github.com/lorenzoongithub/nudge4j)-通过字节码注入从Java 8浏览器远程开发人员控制台。
- [Pinpoint](https://github.com/naver/pinpoint)-开源APM工具。
- [Prometheus](https://github.com/prometheus/client_java)-提供多维数据模型，DSL，自治服务器节点等等。
- [Sentry ![c]](https://github.com/getsentry/sentry-java)-与[Sentry](https://github.com/getsentry/sentry),一个应用程序错误跟踪和性能分析平台。
- [SPM ![c]](https://github.com/sematext/sematext-agent-java)-性能监视器，为JVM应用程序分发事务跟踪。
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor)-JVM应用程序的开源性能监控和事务跟踪。
- [Sysmon](https://github.com/palantir/Sysmon)-用于Java vm的轻量级平台监控工具。
- [zipkin](https://zipkin.io)-分布式跟踪系统，收集解决微服务架构中延迟问题所需的定时数据。
- [hippo4j](https://github.com/opengoofy/hippo4j/blob/develop/README-EN.md)-动态和可观察的线程池框架。

### 原生
_ 用于处理特定于平台的本机库。_ 

- [Aparapi](https://github.com/Syncleus/aparapi)-将字节码转换为允许在gpu上执行的OpenCL。
- [JavaCPP](https://github.com/bytedeco/javacpp)-提供高效和方便地访问本机C。
- [JNA](https://github.com/java-native-access/jna)-在不编写JNI的情况下使用本机库。还提供了通用系统库的接口。
- [JNR](https://github.com/jnr/jnr-ffi)-在不编写JNI的情况下使用本机库。还提供了通用系统库的接口。与JNA相同的目标，但速度更快，并作为即将到来的[Project Panama](http://openjdk.java.net/projects/panama)。

### 自然语言处理
_ 专门处理文本的库。_ 

- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)-为纯文本输入提供通用注释器。(研究和学术使用许可证)
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml)-为标记、命名实体识别和情感分析等任务提供了一组基本工具。(GPL-3.0-or-later)
- [DKPro](https://dkpro.github.io)-收集可重复使用的NLP工具，用于语言预处理，机器学习，词汇资源等。
- [LingPipe](http://alias-i.com/lingpipe/)-用于从POS标记到情感分析的任务的工具包。

### 联网
_ 用于构建网络服务器的库。_ 

- [Commons-networking](https://github.com/CiscoSE/commons-networking)-服务器发送事件 (SSE) 的客户端。
- [Comsat](https://github.com/puniverse/comsat)-将标准的Java web相关api与Quasar纤维和actor集成在一起。
- [Dubbo](https://github.com/apache/dubbo)-高性能RPC框架。
- [Grizzly](https://javaee.github.io/grizzly/)-NIO框架。在Glassfish中用作网络层。
- [gRPC](https://github.com/grpc/grpc-java)基于protobuf和HTTP/2的RPC框架。
- [KryoNet](https://github.com/EsotericSoftware/kryonet)-使用NIO和Kryo为高效的TCP和UDP客户端/服务器网络通信提供干净简单的API。
- [MINA](https://mina.apache.org)-抽象，事件驱动的异步I/O API，用于通过Java NIO通过tcp/IP和UDP/IP进行网络操作。
- [Netty](https://netty.io)-构建高性能网络应用程序的框架。
- [Drift](https://github.com/airlift/drift)-易于使用，基于注释的库，用于创建节俭客户端和可序列化类型。
- [ServiceTalk](https://github.com/apple/servicetalk)-基于Netty的框架，具有针对特定协议定制的api，并支持多种编程范例。
- [sshj](https://github.com/hierynomus/sshj)-以编程方式使用SSH，SCP或SFTP。
- [TLS Channel](https://github.com/marianobarrios/tls-channel)-在SSLEngine上实现ByteChannel接口，从而实现易于使用 (类似套接字) 的TLS。
- [Undertow](http://undertow.io)-基于NIO提供阻塞和非阻塞api的Web服务器。在WildFly中用作网络层。(LGPL-2.1-only)
- [urnlib](https://github.com/slub/urnlib)-表示，解析和编码urn，如RFC 2141。(GPL-3.0-only)
- [Fluency](https://github.com/komamitsu/fluency)-到Fluentd和Fluent Bit的高吞吐量数据摄取记录器。

### ORM
_ 处理对象持久性的api。_ 

- [Apache Cayenne](https://cayenne.apache.org)-为数据访问提供干净的静态API。还包括一个GUI建模器，用于处理数据库映射以及数据库逆向工程和生成。
- [Doma](https://github.com/domaframework/doma)-数据库访问框架，在编译时使用注释处理以及称为双向SQL的本机SQL模板来验证和生成源代码。
- [Ebean](https://ebean.io)-提供简单和快速的数据访问。
- [EclipseLink](https://www.eclipse.org/eclipselink/)-支持多种持久性标准: JPA、JAXB、JCA和SDO。
- [Hibernate](http://hibernate.org/orm/)-强大和广泛使用，与一个活跃的社区。(LGPL-2.1-only)
- [MyBatis](https://github.com/mybatis/mybatis-3)-将对象与存储过程或SQL语句耦合。
- [ObjectiveSql](https://github.com/braisdom/ObjectiveSql)-ActiveRecord ORM用于快速开发和convention over configuration。
- [Permazen](https://github.com/permazen/permazen)-语言-自然持久层。
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)-简单的数据库和CSV映射器。

### PaaS
_ Java平台即服务。_ 

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/)-基于AWS，支持Tomcat和Jetty。
- [AWS Lambda ![c]](https://aws.amazon.com/lambda/)-无服务器计算。
- [Google Cloud ![c]](https://cloud.google.com)-Google的云基础设施。
- [Heroku ![c]](https://www.heroku.com)-抽象计算环境。
- [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/)-微软的云基础设施。
- [OpenShift ![c]](https://www.openshift.com)-另外提供内部部署解决方案。

### PDF
_ 帮助处理pdf文件的工具。_ 

- [Apache FOP](https://xmlgraphics.apache.org/fop/)-从xsl-fo创建pdf。
- [Apache PDFBox](https://pdfbox.apache.org)-用于创建和操作pdf的工具箱。
- [Dynamic Jasper](http://dynamicjasper.com)-JasperReports的抽象层。(LGPL-3.0-only)
- [DynamicReports](https://github.com/dynamicreports/dynamicreports)-简化JasperReports。(LGPL-3.0-only)
- [Eclipse BIRT](https://www.eclipse.org/birt)-报告引擎，用于使用基于Eclipse的可视化编辑器创建PDF和其他格式 (DOCX，XLSX，HTML等)。
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)-XML/XHTML和CSS 2.1渲染器。(LGPL-2.1-or-later)
- [iText ![c]](https://itextpdf.com/en)-以编程方式创建pdf文件。
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library)-复杂的报告引擎。(LGPL-3.0-only)
- [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf)-正确支持基于flyingsaucer和Apache PDFBox的现代PDF标准。
- [OpenPDF](https://github.com/LibrePDF/OpenPDF)-开源iText fork。(LGPL-3.0-only和MPL-2.0)
- [Tabula](https://github.com/tabulapdf/tabula-java)-从pdf文件中提取表格。

### 性能分析
_ 用于性能分析、分析和基准测试的工具。_ 

- [fastThread ![c]](https://fastthread.io)-使用免费的基于云的上传界面分析和可视化线程转储。
- [GCeasy ![c]](https://gceasy.io)-分析和可视化GC日志的工具。它提供了一个免费的基于云的上传界面。
- [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler)-低开销，无偏差采样分析器。
- [jHiccup](https://github.com/giltene/jHiccup)-日志和记录平台JVM失速。
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)-分析HotSpot JVM所做的JIT编译器优化。
- [JMH](http://openjdk.java.net/projects/code-tools/jmh/)-用于构建，运行和分析以Java和其他语言编写的针对JVM的纳米/微/毫/宏基准的线束。(仅与Classpath-exception-2.0一起GPL-2.0)
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)-用于延迟测量和报告的实用程序。

### 站台
_ 框架是包含多个类别的多个库的套件。_ 

#### Apache Commons
- [BCEL](http://commons.apache.org/proper/commons-bcel/)-字节码工程库-分析，创建和操作Java类文件。
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils/)-围绕Java反射和内省api的易于使用的包装器。
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/)-重新设计Commons BeanUtils。
- [BSF](http://commons.apache.org/proper/commons-bsf/)-Bean脚本框架-脚本语言的接口，包括JSR-223。
- [Chain](http://commons.apache.org/proper/commons-chain/)-责任链模式的实施。
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan/)-在不加载的情况下查找类接口，方法，字段和注释。
- [CLI](http://commons.apache.org/proper/commons-cli/)-命令行参数解析器。
- [CLI2](http://commons.apache.org/sandbox/commons-cli2/)-重新设计Commons CLI。
- [Codec](http://commons.apache.org/proper/commons-codec/)-通用编码/解码算法，例如语音，base64或URL。
- [Collections](http://commons.apache.org/proper/commons-collections/)-扩展或增强Java集合框架。
- [Compress](http://commons.apache.org/proper/commons-compress/)-定义用于处理tar、zip和bzip2文件的API。
- [Configuration](http://commons.apache.org/proper/commons-configuration/)-读取各种格式的配置/首选项文件。
- [Convert](http://commons.apache.org/sandbox/commons-convert/)-Commons-Convert旨在提供一个单独的库，专门用于将一种类型的对象转换为另一种类型的任务。
- [CSV](http://commons.apache.org/proper/commons-csv/)-用于读取和写入逗号分隔值文件的组件。
- [Daemon](http://commons.apache.org/proper/commons-daemon/)-类似unix守护程序的java代码的替代调用机制。
- [DBCP](http://commons.apache.org/proper/commons-dbcp/)-数据库连接池服务。
- [DbUtils](http://commons.apache.org/proper/commons-dbutils/)-JDBC帮助程序库。
- [Digester](http://commons.apache.org/proper/commons-digester/)-XML-到-Java-对象映射实用程序
- [Email](http://commons.apache.org/proper/commons-email/)-从Java发送电子邮件的库。
- [Exec](http://commons.apache.org/proper/commons-exec/)-用于处理Java中的外部进程执行和环境管理的API。
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/)-您的servlet和web应用程序的文件上传功能。
- [Finder](http://commons.apache.org/sandbox/commons-finder/)-受UNIX find命令启发的Java库。
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/)-用于使用平面数据结构的Java库。
- [Functor](http://commons.apache.org/proper/commons-functor/)-可以作为对象或表示单个通用函数的对象进行操作的函数。
- [Graph](http://commons.apache.org/sandbox/commons-graph/)-通用图形api和算法。
- [I18n](http://commons.apache.org/sandbox/commons-i18n/)-添加本地化消息包的功能，该功能由一个或多个属于一起的本地化文本组成。
- [Id](http://commons.apache.org/sandbox/commons-id/)-Id是用于生成标识符的组件。
- [Imaging](http://commons.apache.org/proper/commons-imaging/)-图像库。
- [IO](http://commons.apache.org/proper/commons-io/)-I/O实用程序的集合。
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/)-继续实现以捕获应用程序的状态。
- [JCI](http://commons.apache.org/proper/commons-jci/)Java编译器接口。
- [JCS](http://commons.apache.org/proper/commons-jcs/)Java缓存系统。
- [Jelly](http://commons.apache.org/proper/commons-jelly/)-基于XML的脚本和处理引擎。
- [Jexl](http://commons.apache.org/proper/commons-jexl/)-表达式语言，它扩展了JSTL的表达式语言。
- [JNet](http://commons.apache.org/sandbox/commons-jnet/)-JNet允许通过e java.net API使用动态注册url流处理程序。
- [JXPath](http://commons.apache.org/proper/commons-jxpath/)-使用XPath语法操作Java bean的实用程序。
- [Lang](http://commons.apache.org/proper/commons-lang/)-为java.lang中的类提供额外的功能。
- [Logging](https://commons.apache.org/proper/commons-logging/)-围绕各种日志API实现的包装。
- [Math](http://commons.apache.org/proper/commons-math/)-轻量级，独立的数学和统计组件。
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/)-监控旨在为Java应用程序提供一个简单但可扩展的监控解决方案。
- [Nabla](http://commons.apache.org/sandbox/commons-nabla/)-Nabla提供自动微分类，可以生成Java语言中实现的任何函数的派生。
- [Net](http://commons.apache.org/proper/commons-net/)-网络实用程序和协议实现的集合。
- [OGNL](http://commons.apache.org/proper/commons-ognl/)-对象图导航语言。
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/)-使用OpenPGP对数据进行签名和验证的接口。
- [Performance](http://commons.apache.org/sandbox/commons-performance/)-用于微基准客户端的小型框架，实现了Commons DBCP和Pool。
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/)-提供一组围绕工作队列设计的管道实用程序，这些工作队列并行运行以按顺序处理数据对象。
- [Pool](http://commons.apache.org/proper/commons-pool/)-通用对象池组件。
- [Proxy](http://commons.apache.org/proper/commons-proxy/)-用于创建动态代理的库。
- [RDF](https://commons.apache.org/proper/commons-rdf/)-可以由JVM上的系统实现的RDF 1.1的常见实现。
- [RNG](https://commons.apache.org/proper/commons-rng/)-Commons Rng提供伪随机数生成器的实现。
- [SCXML](http://commons.apache.org/proper/commons-scxml/)-旨在创建和维护Java SCXML引擎的状态图XML规范的实现。
- [Validator](http://commons.apache.org/proper/commons-validator/)-在xml文件中定义验证器和验证规则的框架。
- [VFS](http://commons.apache.org/proper/commons-vfs/)-虚拟文件系统组件，用于将文件，FTP，SMB，ZIP等视为单个逻辑文件系统。
- [Weaver](http://commons.apache.org/proper/commons-weaver/)-提供一种简单的方法来增强 (编织) 编译的字节码。

#### 其他
- [CUBA Platform](https://www.cuba-platform.com/)-用于开发具有丰富web界面的企业应用程序的高级框架，基于Spring，EclipseLink和Vaadin。
- [Light-4J](https://github.com/networknt/light-4j/)-内置的快速，轻量级和高效的微服务框架[security](https://github.com/networknt/light-oauth2/)。
- [Orienteer](https://github.com/OrienteerBAP/Orienteer/)-用于快速配置/开发CRM，ERP，LMS和其他应用程序的开源业务应用程序平台。
- [Spring](https://spring.io/projects/)-提供了许多用于依赖注入，面向方面编程，安全性等的软件包。

### 流程
_ 帮助管理操作系统进程的库。_ 

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec)-围绕Apache Commons Exec的便捷API。
- [zt-exec](https://github.com/zeroturnaround/zt-exec)-为Apache Commons Exec和ProcessBuilder提供统一的API。
- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer)-通过PID停止从Java启动的进程或系统进程。

### 反应式库
_ 用于开发反应式应用程序的库。_ 

- [Akka](https://akka.io)-用于构建并发，分布式，容错和事件驱动应用程序的工具包和运行时。
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm)-提供具有非阻塞背压的异步流处理的标准。
- [Reactor](https://github.com/reactor/reactor-core)-用于构建响应式快速数据应用程序的库。
- [RxJava](https://github.com/ReactiveX/RxJava)-允许使用可观察序列组成异步和基于事件的程序。
- [vert.x](https://vertx.io)-多语言事件驱动的应用程序框架。

### REST框架
_ 专门用于创建RESTful服务的框架。_ 

- [Dropwizard](https://github.com/dropwizard/dropwizard)-自以为是的框架，用于使用Jetty，Jackson，Jersey和Metrics设置现代web应用程序。
- [Elide](https://elide.io)-基于JPA数据模型的JSON或GraphQL api的自以为是的框架。
- [Jersey](https://jersey.github.io)-JAX-RS参考实现。
- [Microserver](https://github.com/aol/micro-server)-用于Spring和Spring Boot的方便，可扩展的微服务插件系统。它拥有30多个插件，并且还在不断增长，它支持微单体和纯微服务风格。
- [Rapidoid](https://www.rapidoid.org)-简单，安全和非常快速的框架，包括嵌入式HTTP服务器，GUI组件和依赖注入。
- [rest.li](https://github.com/linkedin/rest.li)-用于使用类型安全绑定和异步，非阻塞IO构建强大，可扩展的RESTful架构的框架，具有端到端开发人员工作流程，可促进清洁实践，统一接口设计和一致的数据建模。
- [RESTEasy](https://resteasy.github.io)-JAX-RS规范的完全认证和可移植实现。
- [RestExpress](https://github.com/RestExpress/RestExpress)-JBoss Netty HTTP堆栈上的薄包装器，可提供缩放和性能。
- [Restlet Framework](https://github.com/restlet/restlet-framework-java)-具有强大路由和过滤功能以及统一的客户端和服务器API的开创性框架。
- [Spark](http://sparkjava.com)-Sinatra启发框架。
- [Crnk](http://www.crnk.io)-实现JSON API规范，以构建面向资源的REST端点，包括排序，过滤，分页，链接，对象图，类型安全，批量更新，集成等。
- [springdoc-openapi](https://github.com/springdoc/springdoc-openapi)-使用Spring Boot项目自动生成API文档。
- [Swagger](https://swagger.io)-REST api的标准语言无关接口。

### 科学
_ 用于科学计算、分析和可视化的库。_ 

- [BioJava](https://biojava.org/)-通过提供生物信息学中常用的算法，文件格式解析器，测序和3D可视化，促进处理生物数据。
- [Chart-FX](https://github.com/GSI-CS-CO/chart-fx)-科学图表库，重点是针对大型数据集以25 hz的更新速率进行性能优化的实时数据可视化。
- [DataMelt](https://datamelt.org/)-科学计算，数据分析和数据可视化的环境。(GPL-3.0-or-later)
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)-用于理论算法的模块化，轻便和简单的图形框架。
- [GraphStream](http://graphstream-project.org)-用于建模和分析动态图的库。
- [JFreeChart](http://www.jfree.org/jfreechart/)-用于Swing，JavaFX和服务器端应用程序的2D图表库。(LGPL-2.1-only)
- [JGraphT](https://github.com/jgrapht/jgrapht)-提供数学图论对象和算法的图库。
- [JGraphX](https://github.com/jgraph/jgraphx)-用于可视化 (主要是摆动) 和与节点边图交互的库。
- [LogicNG](https://github.com/logic-ng/LogicNG)-用于创建，操作和解决布尔和伪布尔公式的库。
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk)-用于地球物理科学计算，可视化和数字信号分析的库。
- [Morpheus](https://github.com/zavtech/morpheus-core)-提供了一种通用的二维内存高效表格数据结构，称为DataFrame，以实现高效的内存分析，用于JVM上的科学计算。
- [Orson-Charts](https://github.com/jfree/orson-charts)-生成各种各样的3D图表，这些图表可以与Swing和JavaFX一起显示，也可以导出为PDF，SVG，PNG和JPEG。(GPL-3.0-only)
- [Tablesaw](https://github.com/jtablesaw/tablesaw)-包括一个数据框、一个嵌入式列存储以及数百种用于转换、汇总或过滤数据的方法。
- [XChart](https://github.com/knowm/XChart)-用于绘制数据的轻量级库。有许多可自定义的图表类型。

### 搜索
_ 索引文档以进行搜索和分析的引擎。_ 

- [Apache Lucene](https://lucene.apache.org)-高性能，全功能，跨平台，文本搜索引擎库。
- [Apache Solr](https://lucene.apache.org/solr/)-针对高流量优化的企业搜索引擎。
- [Elasticsearch](https://www.elastic.co)-分布式，支持多租户的全文搜索引擎，具有RESTful web界面和无架构的JSON文档。
- [Indexer4j](https://github.com/haeungun/indexer4j)-简单而轻便的全文索引和搜索库。

### 安全
_ 处理安全性、身份验证、授权或会话管理的库。_ 

- [Apache Shiro](https://shiro.apache.org)-执行身份验证，授权，加密和会话管理。
- [Bouncy Castle](https://www.bouncycastle.org/java.html)-通用加密库和JCA提供程序提供广泛的功能，从基本的助手到PGP/SMIME操作。
- [DependencyCheck](https://github.com/jeremylong/DependencyCheck)-检测项目依赖项中包含的公开披露的漏洞。
- [Cryptomator](https://cryptomator.org)-云中文件的多平台，透明，客户端加密。(GPL-3.0-only)
- [Hdiv](https://github.com/hdiv/hdiv)-排除OWASP Top 10中包含的应用程序安全风险的运行时应用程序，包括SQL注入，跨站点脚本，跨站点请求伪造，数据篡改和蛮力攻击。
- [jjwt](https://github.com/jwtk/jjwt)-适用于Java和Android的JSON web令牌。
- [jwt-java](https://github.com/BastiaanJansen/jwt-java)-轻松创建和解析JSON Web令牌，并使用fluent API创建自定义JWT验证器。
- [Jwks RSA](https://github.com/auth0/jwks-rsa-java)-JSON Web密钥集解析器。
- [Kalium](https://github.com/abstractj/kalium)-网络和密码学 (NaCl) 库的绑定。
- [Keycloak](https://www.keycloak.org)-用于浏览器应用程序和RESTful web服务的集成SSO和IDM。
- [Keywhiz](https://github.com/square/keywhiz)-用于分发和管理秘密的系统。
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)-高级密码强度估计。
- [OACC](http://oaccframework.org)-提供基于权限的授权服务。
- [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)-访问管理解决方案，包括身份验证，SSO，授权，联合，权利和web服务安全性。
- [OTP-Java](https://github.com/BastiaanJansen/OTP-Java)-根据RFC 4226 (HOTP) 和RFC 6238 (TOTP) 的一次性密码生成器库。
- [pac4j](https://github.com/pac4j/pac4j)-安全引擎。
- [Passay](http://www.passay.org/)-通过根据可配置的规则集验证候选密码来实施密码策略。
- [Password4j](https://github.com/Password4j/password4j)-用户友好的加密库，支持Argon2，Bcrypt，Scrypt，PBKDF2和各种其他加密哈希函数。
- [SecurityBuilder](https://github.com/tersesystems/securitybuilder)-用于JCA和JSSE类，尤其是X.509证书的Fluent Builder API。
- [SSLContext-Kickstart](https://github.com/Hakky54/sslcontext-kickstart)-高级SSL上下文构建器，用于使用SSL/TLS配置HTTP客户端。
- [Themis](https://github.com/cossacklabs/themis)-多平台高级加密库为保护敏感数据提供易于使用的加密: 具有前向保密性的安全消息传递，安全数据存储 (AES256GCM); 适合构建端到端加密应用程序。
- [Tink](https://github.com/google/tink)-为常见的加密任务提供了一个简单且防误用的API。
- [Topaz](https://www.topaz.sh)-对支持RBAC、ABAC和ReBAC的应用程序进行细粒度授权。

### 序列化
_ 高效处理序列化的库。_ 

- [FlatBuffers](https://github.com/google/flatbuffers)-内存高效的序列化库，可以访问序列化数据，而无需解包和解析。
- [FST](https://github.com/RuedigerMoeller/fast-serialization)-JDK兼容，高性能对象图序列化。
- [Kryo](https://github.com/EsotericSoftware/kryo)-快速高效的对象图序列化框架。
- [MessagePack](https://github.com/msgpack/msgpack-java)-高效的二进制序列化格式。
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer)-以PHP序列化格式序列化对象。

### 服务器
_ 专门用于部署应用程序的服务器。_ 

- [Apache Tomcat](https://tomcat.apache.org)-用于Servlet和JSP的健壮、全面的服务器。
- [Apache TomEE](https://tomee.apache.org)-Tomcat加上Java EE。
- [Jetty](https://www.eclipse.org/jetty/)-提供Web服务器和javax.servlet容器，以及对HTTP/2，WebSocket，OSGi，JMX，JNDI，JAAS和许多其他集成的支持。
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd)-微小的，易于嵌入的HTTP服务器。
- [WildFly](https://www.wildfly.org)-以前称为JBoss，由Red Hat开发，具有广泛的Java EE支持。(LGPL-2.1-only)

### 模板引擎
_ 在模板中替换表达式的工具。_ 

- [Freemarker](https://freemarker.apache.org)-基于模板和更改数据生成文本输出 (HTML网页，电子邮件，配置文件，源代码等) 的库。
- [Handlebars.java](https://jknack.github.io/handlebars.java/)-无逻辑和语义胡子模板。
- [Jade4J](https://github.com/neuland/jade4j)-实施Pug (以前称为Jade)。
- [Jamal](https://github.com/verhas/jamal)-嵌入到Maven/JavaDoc中的可扩展模板引擎，支持多个扩展 (Groovy，Ruby，JavaScript，JShell，PlantUml)，并支持代码段处理。
- [jstachio](https://github.com/jstachio/jstachio)-Typesafe Mustache模板引擎。
- [jte](https://github.com/casid/jte)-编译为类，并使用简单的语法，几个功能，使开发更容易，并提供快速执行和占地面积小。
- [Jtwig](https://github.com/jtwig/jtwig)-模块化，可配置和完全测试的模板引擎。
- [Pebble](https://pebbletemplates.io)-受Twig的启发，并以其继承功能和易于阅读的语法将自己分开。它配备了内置的自动逃逸安全性，并包括对国际化的集成支持。
- [Rocker](https://github.com/fizzed/rocker)-优化，内存高效和快速的模板引擎产生静态类型，普通对象。
- [StringTemplate](https://github.com/antlr/stringtemplate4)-用于生成源代码，网页，电子邮件或任何其他格式化文本输出的模板引擎。
- [Thymeleaf](https://www.thymeleaf.org)-旨在替代JSP并适用于XML文件。

### 测试
_ 从模型到视图进行测试的工具。_ 

#### 异步
_ 简化测试异步服务的工具。_ 

- [Awaitility](https://github.com/awaitility/awaitility)-用于同步异步操作的DSL。
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit)-用于测试多线程和异步应用程序的工具包。
- [GreenMail](http://www.icegreen.com/greenmail/)-用于集成测试的内存电子邮件服务器。支持包含SSL的SMTP、POP3和IMAP。(GPL-2.0-only)
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java)-Hoverfly的本机绑定，它允许您模拟HTTP服务的代理。
- [Karate](https://github.com/intuit/karate)-DSL结合了API测试自动化，模拟和性能测试，使测试REST/HTTP服务变得容易。
- [REST Assured](https://github.com/rest-assured/rest-assured)-用于轻松测试REST/HTTP服务的DSL。
- [WebTau](https://github.com/testingisdocumenting/webtau)-使用一致的匹配程序和概念集，跨REST API，图形QL，浏览器，数据库，CLI和业务逻辑进行测试。

#### BDD
_ TDD产生的软件开发过程的测试，受到DDD和OOAD的严重影响。_ 

- [Cucumber](https://github.com/cucumber/cucumber-jvm)-提供了一种以客户可以理解的简单语言描述功能的方法。
- [Cukes-REST](https://github.com/ctco/cukes)-使用黄瓜进行REST服务测试的小黄瓜步骤集合。
- [J8Spec](https://github.com/j8spec/j8spec)-遵循类似茉莉花的语法。
- [JBehave](https://jbehave.org)-描述故事的广泛可配置的框架。
- [JGiven](http://jgiven.org)-提供了一个流畅的API，允许更简单的组合。
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave)-旨在提供一个流利的API来编写测试长而描述性的句子，读起来像普通英语。
- [Serenity BDD](https://github.com/serenity-bdd/serenity-core)-与Cucumber，jbeave和JUnit一起使用的自动验收测试和报告库，使编写高质量的可执行规范变得更加容易。

#### 固定装置
_ 与创建和处理随机数据有关的一切。_ 

- [Beanmother](https://github.com/keepcosmos/beanmother)-从YAML fixtures设置bean。
- [Fixture Factory](https://github.com/six2six/fixture-factory)-从模板生成假对象。
- [jFairy](https://github.com/Devskiller/jfairy)-假数据生成器。
- [Instancio](https://github.com/instancio/instancio)-通过生成完全填充的可再现对象来自动化单元测试中的数据设置。包括JUnit 5扩展。
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting)-JUnit测试运行器和插件，用于运行具有伪随机性的JUnit测试。
- [Java Faker](https://github.com/DiUS/java-faker)-Ruby的假数据生成器的端口。
- [Mockneat](https://github.com/nomemory/mockneat)-另一个假数据生成器。

#### 框架
_ 为特定用例提供运行测试的环境。_ 

- [ArchUnit](https://github.com/TNG/ArchUnit)-用于指定和断言架构规则的测试库。
- [Apache JMeter](http://jmeter.apache.org)-功能测试和性能测量。
- [Arquillian](http://arquillian.org)-Java EE容器的集成和功能测试平台。
- [Citrus](https://citrusframework.org)-专注于客户端和服务器端消息传递的集成测试框架。
- [Gatling](https://gatling.io)-负载测试工具专为易用性，可维护性和高性能而设计。
- [JUnit](https://junit.org/junit5/)-通用测试框架。
- [jqwik](https://jqwik.net)-基于JUnit 5构建的基于属性的测试引擎。
- [Pact JVM](https://github.com/DiUS/pact-jvm)-消费者驱动的合同测试。
- [PIT](http://pitest.org)-快速突变测试框架，用于评估现有JUnit或TestNG测试套件的故障检测能力。

#### 匹配程序
_ 提供自定义匹配程序的库。_ 

- [AssertJ](https://joel-costigliola.github.io/assertj/)-流利的断言，提高可读性。
- [Hamcrest](http://hamcrest.org/JavaHamcrest/)-可以组合以创建灵活的意图表达的匹配器。
- [JSONAssert](http://jsonassert.skyscreamer.org)-简化测试JSON字符串。
- [JsonUnit](https://github.com/lukas-krecan/JsonUnit)-简化测试中JSON比较的库。
- [Truth](https://truth.dev)-Google流利的断言和命题框架。
- [XMLUnit](https://github.com/xmlunit/xmlunit)-简化了XML输出的测试。

#### 杂项
_ 其他与测试有关的东西。_ 

- [ConsoleCaptor](https://github.com/Hakky54/console-captor)-捕获用于单元测试目的的控制台输出。
- [junit-dataprovider](https://github.com/TNG/junit-dataprovider)-用于JUnit的类似TestNG的数据提供程序/运行程序。
- [LogCaptor](https://github.com/Hakky54/log-captor)-捕获用于单元测试目的的日志条目。
- [log-capture](https://github.com/dm-drogeriemarkt/log-capture)-捕获日志条目并为单元和集成测试提供断言。
- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector)-报告给定类的实例是否不可变。
- [raml-tester](https://github.com/nidi3/raml-tester)-测试请求/响应是否与给定的RAML定义匹配。
- [TestContainers](https://github.com/testcontainers/testcontainers-java)-提供常见数据库、Selenium web浏览器或其他任何可以在Docker容器中运行的一次性实例。
- [pojo-tester](https://www.pojo.pl)-自动对基本POJO方法执行测试。(LGPL-3.0-only)

#### 嘲笑
_ 模拟协作者以帮助测试单个隔离单元的工具。_ 

- [JMockit](http://jmockit.github.io)-集成测试，API嘲笑和伪造以及代码覆盖。
- [Mockito](https://github.com/mockito/mockito)-Mocking框架，让您使用干净简单的API编写测试。
- [MockServer](https://www.mock-server.com)-允许嘲笑与HTTPS集成的系统。
- [Moco](https://github.com/dreamhead/moco)-用于存根和模拟的简洁web服务。
- [PowerMock](https://github.com/powermock/powermock)-模拟静态方法，构造函数，最终类和方法，私有方法以及删除静态初始值设定项。
- [WireMock](http://wiremock.org)-存根和模拟web服务。

### 效用
_ 提供通用实用功能的库。_ 

- [Arthas](https://github.com/alibaba/arthas)-允许对应用程序的生产问题进行故障排除，而无需修改代码或重新启动服务器。
- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j)基于令牌桶算法的限速库。
- [cactoos](https://github.com/yegor256/cactoos)-面向对象原语的集合。
- [Chocotea](https://github.com/cleopatra27/chocotea)-从java代码生成postman集合，环境和集成测试。
- [CRaSH](http://www.crashub.org)-为运行崩溃的JVM提供一个shell。由Spring Boot和其他人使用。(LGPL-2.1-or-later)
- [Dex](https://github.com/PatMartin/Dex)-Java/JavaFX工具能够强大的ETL和数据可视化。
- [Embulk](https://github.com/embulk/embulk)-批量数据加载器，可帮助各种数据库，存储，文件格式和云服务之间的数据传输。
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch)-微库监视目录文件系统更改，简化了java.nio.file.WatchService。
- [Gephi](https://github.com/gephi/gephi)-用于可视化和操纵大型图形网络的跨平台。(GPL-3.0-only)
- [Guava](https://github.com/google/guava)-集合，缓存，原语支持，并发库，通用注释，字符串处理，I/O等。
- [JADE](http://jade.tilab.com)-用于构建和调试多代理系统的框架和环境。(LGPL-2.0-only)
- [Java Diff Utils](https://java-diff-utils.github.io/java-diff-utils/)-用于文本或数据比较和修补的实用程序。
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)-帮助构建困难的正则表达式的库。
- [JGit](https://www.eclipse.org/jgit/)-实现Git版本控制系统的轻量级纯Java库。
- [minio-java](https://github.com/minio/minio-java)-提供简单的api来访问任何Amazon S3-compatible对象存储服务器。
- [Protégé](https://protege.stanford.edu)-提供了一个本体编辑器和一个框架来构建基于知识的系统。
- [Underscore-java](https://github.com/javadev/underscore-java)-Underscore.js函数的端口。

### 版本管理器
_ 帮助创建开发shell环境并在不同Java版本之间切换的实用程序。_ 

- [jabba](https://github.com/shyiko/jabba)-受nvm启发的Java版本管理器。支持macOS，Linux和Windows。
- [jenv](https://github.com/jenv/jenv)-受rbenv启发的Java版本管理器。可以全局配置或按项目配置。在Debian和macOS上测试。
- [SDKMan](https://github.com/sdkman/sdkman-cli)-受RVM和rbenv启发的Java版本管理器。支持基于UNIX的平台和Windows。

### Web爬行
_ 分析网站内容的库。_ 

- [Apache Nutch](https://nutch.apache.org)-用于生产环境的高度可扩展，高度可扩展的web爬虫。
- [Crawler4j](https://github.com/yasserg/crawler4j)-简单和轻量级的网络爬虫。
- [jsoup](https://jsoup.org)-刮擦，解析，操纵和清理HTML。
- [StormCrawler](http://stormcrawler.net)-用于构建低延迟和可扩展的web爬虫的SDK。
- [webmagic](https://github.com/code4craft/webmagic)-具有下载，url管理，内容提取和持久性的可扩展爬虫。

### Web框架
_ 处理web应用程序各层之间通信的框架。_ 

- [ActiveJ](https://activej.io)-为开发高性能web应用程序而从头开始构建的轻量级异步框架。
- [Apache Tapestry](https://tapestry.apache.org)-面向组件的框架，用于创建动态，健壮，高度可扩展的web应用程序。
- [Apache Wicket](https://wicket.apache.org)-基于组件的web应用程序框架，类似于Tapestry，具有有状态的GUI。
- [Blade](https://github.com/lets-blade/blade)-轻量级的模块化框架，旨在优雅和简单。
- [Bootique](https://bootique.io)-可运行应用程序的最小自以为是的框架。
- [Firefly](http://www.fireflysource.com)异步框架快速开发高性能的web应用程序。
- [Javalin](https://javalin.io/)-用于web应用程序的微框架
- [Jooby](http://www.jooby.org)-可扩展，快速和模块化的微框架，提供多种编程模型。
- [Ninja](http://www.ninjaframework.org)-全栈web框架。
- [Pippo](http://www.pippo.ro)-小型、高度模块化、类似Sinatra的框架。
- [Play](https://www.playframework.com)-基于Akka构建，它为Java和Scala中的高度可扩展应用程序提供了可预测且最小的资源消耗 (CPU，内存，线程)。
- [PrimeFaces](https://www.primefaces.org)-具有免费和商业/支持版本以及前端组件的JSF框架。
- [Ratpack](https://ratpack.io)-一组库，可促进快速，高效，可发展且经过良好测试的HTTP应用程序。
- [Takes](https://github.com/yegor256/takes)-固执己见的web框架，围绕真正的面向对象编程和不变性的概念构建。
- [Vaadin](https://vaadin.com)-使用标准web组件的事件驱动框架。在客户端使用Ajax的服务器端架构。

### 工作流编排引擎
- [Cadence](https://cadenceworkflow.io)-来自Uber的有状态代码平台。
- [flowable](https://github.com/flowable/flowable-engine)-紧凑高效的工作流和业务流程管理平台。
- [Temporal](https://temporal.io)-微服务编排平台，从Cadence分叉，但基于gRPC。

## 资源
### 相关的Awesome 列表
_ 与Java和JVM生态系统相关的很棒的列表。_ 

- [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing)
- [Awesome Graal](https://github.com/neomatrix369/awesome-graal)
- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle)
- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX)
- [Awesome JVM](https://github.com/deephacks/awesome-jvm)
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices)
- [Awesome REST](https://github.com/marmelab/awesome-rest)
- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium)
- [ciandcd](https://github.com/ciandcd/awesome-ciandcd)
- [Useful Java Links](https://github.com/Vedenin/useful-java-links)
- [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency)
- [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap)

### 社区
_ 积极的讨论。_ 

- [r/java](https://www.reddit.com/r/java/)-Subreddit的Java社区。
- [Stack Overflow](https://stackoverflow.com/questions/tagged/java)-问答平台。
- [VirtualJUG](https://virtualjug.com)-虚拟Java用户组。

### 前端
_ 为此列表提供前端的网站。请注意，不会有官方网站。我们不与特定网站相关联，每个人都可以创建一个。_ 

- [java.libhunt.com](https://java.libhunt.com)

### 有影响力的书籍
_ 这些书产生了很大的影响，仍然值得一读。_ 

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)
- [Head First Java (3rd Edition)](https://www.oreilly.com/library/view/head-first-java/9781492091646/)

### 播客和截屏
_ 编程时要看或听的东西。_ 

- [140 Second Ducklings](https://twitter.com/debugagent/status/1491075324805001219)-在Twitter上的短视频深入解释Java调试。
- [A Bootiful Podcast](https://bootifulpodcast.fm)
- [Foojay Podcast](https://foojay.io/today/category/podcast/)
- [Inside Java](https://inside.java/podcast)(官方)
- [Java Off Heap](http://www.javaoffheap.com)
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com)-自02/2015年起停产。

### 人
#### Twitter
_ 要关注的活跃账户。推特上的描述。_ 

- [Adam Bien](https://twitter.com/AdamBien)-自由作家，JavaOne Rockstar演讲者，顾问，Java冠军。
- [Aleksey Shipilëv](https://twitter.com/shipilev)-性能极客，基准沙皇，并发bug猎人。
- [Antonio Goncalves](https://twitter.com/agoncal)-Java冠军，JUG领导者，Devoxx法国，Java EE 6/7，JCP，作者。
- [Arun Gupta](https://twitter.com/arungupta)-Java冠军，JavaOne Rockstar，JUG领导者，Devoxx4Kids-er，Couchbase开发人员倡导副总裁。
- [Brian Goetz](https://twitter.com/BrianGoetz)-Oracle的Java语言架构师。
- [Bruno Borges](https://twitter.com/brunoborges)-Oracle的产品经理/Java Jock。
- [Chris Engelbert](https://twitter.com/noctarius2k)-开源爱好者，演讲者，开发人员，TimescaleDB的开发人员倡导。
- [Chris Richardson](https://twitter.com/crichardson)-软件架构师，顾问和连续企业家，Java冠军，JavaOne摇滚明星，* POJOs in Action-作者。
- [Ed Burns](https://twitter.com/edburns)-Oracle技术人员的咨询成员。
- [Eugen Paraschiv](https://twitter.com/baeldung)-春季安全课程的作者。
- [Heinz Kabutz](https://twitter.com/heinzkabutz)-Java冠军，演讲者，Java专家通讯的作者，并发性能专家。
- [Holly Cummins](https://twitter.com/holly_cummins)-IBM伦敦Bluemix车库技术负责人，Java冠军，JavaOne rockstar开发人员，作者。
- [James Weaver](https://twitter.com/JavaFXpert)-Java/JavaFX/IoT开发人员，作者和演讲者。
- [Java EE](https://twitter.com/Java_EE)-官方Java EE Twitter帐户。
- [Java Magazine](https://twitter.com/Oraclejavamag)-官方Java杂志帐户。
- [Java](https://twitter.com/java)-官方Java Twitter帐户。
- [Javin Paul](https://twitter.com/javinpaul)-著名的Java博客。
- [Josh Long](https://twitter.com/starbuxman)-Pivotal的Spring倡导者，O'Reilly's Cloud Native Java的作者-以及使用JavaOne摇滚明星Spring Boot构建微服务。
- [Lukas Eder](https://twitter.com/lukaseder)-Java冠军，演讲者，创始人兼首席执行官Data Geekery (jOOQ)。
- [Mani Sarkar](https://twitter.com/theNeomatrix369)-Java冠军，多语言，涉及 @ graalvm，AI/ML/DL，数据科学，开发人员社区，演讲者和博客的软件工匠。像这样的几个令人敬畏的列表的创建者。
- [Mario Fusco](https://twitter.com/mariofusco)-RedHatter，JUG协调员，经常演讲和作者。
- [Mark Heckler](https://twitter.com/MkHeck)-Pivotal首席技术专家和开发人员倡导者，会议发言人，出版作者和Java冠军，专注于物联网和云。
- [Mark Reinhold](https://twitter.com/mreinhold)-Oracle Java平台组首席架构师。
- [Markus Eisele](https://twitter.com/myfear)-Java EE布道者，Red Hat。
- [Martijn Verburg](https://twitter.com/karianna)-伦敦JUG联合负责人，演讲者，作者，Java冠军等等。
- [Martin Thompson](https://twitter.com/mjpt777)-面对表演黑帮。
- [Monica Beckwith](https://twitter.com/mon_beck)-性能顾问，JavaOne摇滚明星。
- [OpenJDK](https://twitter.com/OpenJDK)-官方OpenJDK帐户。
- [Peter Lawrey](https://twitter.com/PeterLawrey)-Peter Lawrey，Java性能专家。
- [Randy Shoup](https://twitter.com/randyshoup)-Stitch Fix工程副总裁，扬声器，JavaOne摇滚明星。
- [Reza Rahman](https://twitter.com/reza_rahman)-Java EE/GlassFish/WebLogic布道者，作者，演讲者，开源黑客。
- [Sander Mak](https://twitter.com/Sander_Mak)-Java冠军，作者。
- [Simon Maple](https://twitter.com/sjmaple)-Java冠军，VirtualJUG创始人，LJC领导者，RebelLabs作者。
- [Spencer Gibb](https://twitter.com/spencerbgibb)-软件工程师，爸爸，极客，Spring Cloud Core @ pivotal的联合创始人兼负责人。
- [Stephen Colebourne](https://twitter.com/jodastephen)-Java冠军，演讲者.
- [Trisha Gee](https://twitter.com/trisha_gee)-Java冠军和演讲者。
- [Venkat Subramaniam](https://twitter.com/venkat_s)-作者，休斯顿大学教授，微软MVP奖获得者，JavaOne摇滚明星，Java冠军。
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea)-Java冠军致力于Hypersistence优化器，数据库爱好者，高性能Java持久性书籍的作者。

#### 其他
- [Groundbreakers](https://apexapps.oracle.com/pls/apex/f?p=119297:3::::::)-甲骨文王牌，开创性大使和Java冠军。

### 网站
_ 要阅读的网站。_ 

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
- [foojay.io](https://foojay.io)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [OverOps Blog](https://blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)
- [Java Weekly](https://discu.eu/weekly/java/)

## 贡献
捐款是非常受欢迎的!

请看看[CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/%5Bthis%5D(CONTRIBUTING.md))指导方针和[the validation tools](https://github.com/akullpp/awesome-java-lint)。


