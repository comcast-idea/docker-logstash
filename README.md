# Logstash server in Docker

## Components

* Logstash server 1.4.2
* ElasticSearch server 1.3.4
* Oracle Java 7

## Resources

* ElasticSearch volume `/elasticsearch` containing `data`, `logs` and `plugins` directories
* ElasticSearch ports
** 9300/tcp (transport)
** 9200/tcp (HTTP)
* Logstash ports implemented syslog input
** 5000/tcp
** 5000/udp
