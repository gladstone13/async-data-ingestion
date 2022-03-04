# async-data-ingestion
This project is a sample of Rabbit MQ Producer and Consumer on .Net 6.
The RabbitMQ producer is a REST API that creates file data in Minio (it emulates a file storage in cloud like AWS S3 or Azure Blob) and send an event message to the broker.
The RabbitMQ consumer is a Worker that listen the event queue and persists the file data into MongoDB.
