# SparkStreamingDemo
准实时分布式流处理框架，单位以分钟来算<br/>
<br/>
Spark入门学习 <br/>
http://www.cnblogs.com/shishanyuan/p/4699644.html<br/>
https://www.cnblogs.com/shishanyuan/p/4747735.html<br/>
英文官网：<br/>
http://spark.apache.org/docs/latest/streaming-programming-guide.html<br/>
<br/>
SSH的 The authenticity of host xxx.xxx.xxx.xxx can't be established. 问题,authorized_keys的权限为600，不是400:<br/>
http://blog.csdn.net/lina791211/article/details/11818825<br/>
<br/>
Hadoop出现namenode running as process 18472. Stop it first.解决方法:<br/>
http://www.linuxidc.com/Linux/2014-07/104315.htm<br/>
<br/>
linux 如何把文件夹里面文件权限修改:<br/>
https://zhidao.baidu.com/question/139006065.html<br/>
<br/>
Initial job has not accepted any resources; check your cluster UI to ensure that workers are registered and have sufficient resources<br/>
http://blog.csdn.net/qyl445/article/details/50684691<br/>
<br/>
增加spark worker的内存和datanode的内存方法:<br/>
http://blog.csdn.net/wonder4/article/details/52476008<br/>
<br/>
scala.MatchError异常以及StructType Schema设置:<br/>
http://blog.csdn.net/gangchengzhong/article/details/70153932<br/>
spark streaming向oracle插入日期的问题：<br/>
http://www.aboutyun.com/thread-18282-1-1.html<br/>
<br/>
spark 各类算子：<br/>
https://www.cnblogs.com/zlslch/p/5723857.html<br/>
<br/>
foreachPartitions遍历插入数据,用java编写的连接池，scala编写的有问题：<br/>
java编写的连接池可以使用，SparkStreaming程序有问题，可以参见第三个连接:<br/>
http://blog.csdn.net/erfucun/article/details/52312682<br/>
scala编写的连接池有问题，SparkStreaming程序正常:<br/>
http://blog.csdn.net/legotime/article/details/51836039<br/>
oracle ORA-01000: maximum open cursors exceeded问题的解决方法:<br/>
https://www.cnblogs.com/qinjunli/p/4588089.html<br/> 
<br/>
oracle批量插入数据操作:<br/>
http://blog.csdn.net/yuanzexi/article/details/50912630<br/>
<br/>
spark 连接池c3p0使用:<br/>
http://www.jianshu.com/p/65c1b319b70a<br/>
<br/>
 scala中 object 和 class的区别:<br/>
http://blog.csdn.net/wangxiaotongfan/article/details/48242029<br/>
<br/>
scala基础语法学习：<br/>
http://www.yiibai.com/scala/scala_overview.html<br/>
<br/>
spark读取配置文件中的配置<br/>
http://blog.csdn.net/u012307002/article/details/53308937<br/>
<br/>
Spark Streaming使用Kafka保证数据零丢失：<br/>
https://www.cnblogs.com/jacksu-tencent/p/5135869.html<br/>
https://www.jianshu.com/p/8603ba4be007<br/>
http://blog.csdn.net/lsshlsw/article/details/51133217<br/>
https://www.iteblog.com/archives/1591.html<br/>
<br/>
Spark Streaming消费Kafka Direct方式数据零丢失实现：<br/>
https://www.cnblogs.com/hd-zg/p/6841249.html<br/>:
Spark streaming接收Kafka数据, 偏移量记录的方式有checkpoint、数据库或文件记录或者回写到zookeeper中进行记录:<br/>
https://www.cnblogs.com/xlturing/p/6246538.html<br/>
<br/>
spark Direct 偏移量保存在zookeeper上
https://github.com/xlturing/spark-journey/blob/master/SparkStreamingKafka/src/main/scala/com/sparkstreaming/main/KafkaManager.scala<br/>
http://blog.csdn.net/lw_ghy/article/details/50926855<br/>
<br/>
Spark Streaming -2. Kafka集成指南（Kafka版本0.10.0或更高版本）<br/>
http://blog.csdn.net/zhongguozhichuang/article/details/53282858<br/>
 Spark2.x学习笔记：1、Spark2.2快速入门（本地模式）<br/>
http://blog.csdn.net/chengyuqiang/article/details/77671748?locationNum=4&fps=1<br/>
Spark2.11 两种流操作 + Kafka<br/>
http://blog.csdn.net/zeroder/article/details/73650731<br/>
<br/>
foreachPartition和mapPartition的区别，一个Transformation运算，一个action运算：<br/>
http://blog.csdn.net/u010454030/article/details/78897150<br/>

spark心跳与集群机器时间有关，如果集群每台机器时间不一致，会导致spark心跳失衡，故而报错
