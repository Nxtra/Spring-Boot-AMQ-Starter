# Spring Boot Application accessing Standalone ActiveMQ starter project

## ActiveMQ
brew install apache-activemq  
amq home (when brew install): /usr/local/Cellar/activemq/5.15.6/libexec

activemq start  
activemq stop


Dashboard: [http://localhost:8161/admin](http://localhost:8161/admin)

## Hawtio dashboard
http://bennet-schulz.com/2016/07/apache-activemq-and-hawtio.html

## Application
Put messages on the queue:
http://localhost:8081/rest/publish/yourMessage  

If you want to see some messages on the queue, comment out the Consumer

## Source
[https://www.youtube.com/watch?v=zaCXYkzLgJc](https://www.youtube.com/watch?v=zaCXYkzLgJc)  
[https://github.com/TechPrimers/standalone-spring-boot-activemq-example.git](https://github.com/TechPrimers/standalone-spring-boot-activemq-example.git)

