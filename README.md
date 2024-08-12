В пулл реквестах репозитария содержится код с отработкой использования брокеров сообщений для передачи сущности между микросервисами. 

1. Add kafka template - передача POJO от продюсера получателю с помощью Apache Kafka с сохранением объекта в PostgreSQL.

2. Add replying kafka template - передача POJO от продюсера получателю с помощью ReplyingKafkaTemplate с сохранением объекта в PostgreSQL и возвратом продюсеру с данными о присвоенном при сохранении значении идентификатора.

3. Add RabbitMQ - передача POJO от продюсера получателю с помощью RabbitMQ с сохранением объекта в PostgreSQL.
