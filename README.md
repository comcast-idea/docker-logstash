# Logstash server in Docker

## Components

* Logstash server 1.4.2
* ElasticSearch server 1.1.1
* Oracle Java 7
* Ubuntu 14.04 Trusty

## Resources

* ElasticSearch volume `/data/elasticsearch` containing `data` and `log` directories
* ElasticSearch ports
** 9300/tcp (transport)
** 9200/tcp (HTTP)
* Logstash ports implemented syslog input
** 5000/tcp
** 5000/udp
