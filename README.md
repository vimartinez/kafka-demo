# kafka-demo

Kafka demo with Docker

Demo de kafka con Spring Boot y Docker.


Se levanta Kafka junto con Zookeeper en un Docker compose.

Se realiza una API en Spring que se conecta a kafka y deja mensajes en un tópico (productor)

Se realiza otra API que lee los mensajes de kafka para el tópico seleccionado (consumidor)

Se visualiza kafka, los tópicos y mensajes con offset explorer
https://www.kafkatool.com/download.html

Artículo utilizado para levantar kafka y offset explorer 
https://medium.com/@diego.coder/acceso-a-kafka-utilizando-offset-explorer-2-c6d5e0278d62

Basado en este ejemplo
https://github.com/yoandypv/spring-boot-kafka-basics
