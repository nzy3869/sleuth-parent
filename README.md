# sleuth-parent
spring cloud 链路追踪

ps:
  实例教程来自https://blog.csdn.net/forezp/article/details/70148833
  
spring cloud 版本
  Finchley.RELEASE
  
spring boot 版本
  2.0.3.RELEASE
  
在spring Cloud为F版本的时候，已经不需要自己构建Zipkin Server了，只需要下载jar即可，下载地址：

  https://dl.bintray.com/openzipkin/maven/io/zipkin/java/zipkin-server/

也可以在这里下载：

  链接: https://pan.baidu.com/s/1w614Z8gJXHtqLUB6dKWOpQ 密码: 26pf

下载完成jar 包之后，需要运行jar，如下：

  java -jar zipkin-server-2.10.1-exec.jar

访问浏览器localhost:9411
