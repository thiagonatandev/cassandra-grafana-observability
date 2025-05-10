# As you need:
- [Docker](https://www.docker.com/)
- [Cassandra Easy Stress](https://github.com/rustyrazorblade/cassandra-easy-stress)
- [Grafana](https://grafana.com/)
- [Prometheus](https://prometheus.io/)
- [Java 11](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html)

```
./gradlew shadowJar
./prometheus --config.file=prometheus.yml
``` 