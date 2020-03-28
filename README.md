# java-rabbitmq

## rabbitmq 启动
    1、docker pull rabbitmq
    2、docker pull rabbitmq:management
    3、docker run -d --hostname my-rabbit --name rabbitmq --restart always -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=admin -v /data/rabbitmq/data:/var/lib/rabbitmq -p 15672:15672 -p 5672:5672 -p 25672:25672 -p 61613:61613 -p 1883:1883 rabbitmq:management
    