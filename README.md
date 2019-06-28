# demo
学习

监测服务jvm情况

1、启动项目的 .sh 方法内，启动配置下 添加配置信息：\n
-Dcom.sun.management.jmxremote 【开启 jmx，jdk 1.5 前需要手动开启，后面jdk版本可省略】\n
-Dcom.sun.management.jmxremote.ssl=false 【不开启 ssl 通道】\n
-Dcom.sun.management.jmxremote.authenticate=false 【不开启验证】\n
-Dcom.sun.management.jmxremote.port=22221 【jmx的端口】\n
-Dcom.sun.management.jmxremote.rmi.port=22222\n
2、打开java安装目录下bin里面的jvisualvm 创建jmx链接\n


