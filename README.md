# Kafka With Go

A Kafka implementation using [Go], the [kafka-go] package, and the example provided in the kafka-go package. 

## Preparation
- Install [Docker desktop](https://docs.docker.com/docker-for-mac/install/)
- Install [Apache Kafka](https://medium.com/@Ankitthakur/apache-kafka-installation-on-mac-using-homebrew-a367cdefd273)

## To start/stop

    % docker-compose up/down

Then use docker-desktop to inspect or use terminal log to see a uuid is produced and consumed see the log.  

## Go
The [Get started with Go] explains how to bootstrap a simple project and dependency tracking.

## Docker-compose
Configuring Kafka networking is explained in detail here [Kafka connectivity] when using [kafka-go].

## References
- [Go]
- [kafka-go]
- [Get started with Go]
- [Kafka connectivity]
- [kafka-docker]

[Go]: https://golang.org
[kafka-go]: https://github.com/segmentio/kafka-go
[Get started with Go]: https://golang.org/doc/tutorial/getting-started
[Kafka connectivity]: https://github.com/wurstmeister/kafka-docker/wiki/Connectivity
[kafka-docker]: https://hub.docker.com/r/wurstmeister/kafka/
