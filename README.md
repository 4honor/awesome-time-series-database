<!-- NOTE: this md file is generated, please don't modify the file directly -->
# awesome-time-series-database
A curated list of awesome time series databases, benchmark tools, blog and published papers

## Contents

- [Databases](#databases)
- [Backends](#backends)
  - [HBase](#hbase)
  - [Cassandra](#cassandra)
  - [Elasticsearch](#elasticsearch)
  - [Bigtable](#bigtable)
  - [Memoery](#memoery)
- [Monitoring solutions](#monitoring-solutions)

## Databases

### OpenTSDB

[OpenTSDB](http://opentsdb.net/) is a Classical time series database on top of HBase. Now support Cassandra and Bigtable.

- Language: java

### KairosDB

[KairosDB](https://kairosdb.github.io/) is a Fast Time Series Database on Cassandra

- Language: java

### Heroic

[Heroic](https://spotify.github.io/heroic/) is a Scalable time series database based on Bigtable, Cassandra, and Elasticsearch

- Language: java

## Backends

<!-- NOTE: some databases have multiple backends, they are grouped by their default backend. -->

### HBase

Databases: [OpenTSDB](#opentsdb)

#### Design

- [HBase in Action (Manning Publications) - Chapter 7: HBase by Example: OpenTSDB](http://www.manning.com/dimidukkhurana/)

### Cassandra

Databases: [KairosDB](#kairosdb), [Heroic](#heroic)

#### Design

- [Basic Time Series with Cassandra](http://www.rubyscale.com/post/143067470585/basic-time-series-with-cassandra)
- [Advanced Time Series with Cassandra](http://www.datastax.com/dev/blog/advanced-time-series-with-cassandra)

### Elasticsearch

Databases: 

#### Design

- [Timelion: The time series composer for Kibana](https://www.elastic.co/blog/timelion-timeline)

### Bigtable

Databases: 

#### Design

- [Cloud Bigtable Schema Design for Time Series Data](https://cloud.google.com/bigtable/docs/schema-design-time-series)

### Memoery

Databases: 

#### Design

- [Gorilla: A Fast, Scalable, In-Memory Time Series Database](http://www.vldb.org/pvldb/vol8/p1816-teller.pdf)

## Monitoring solutions

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Pinglei Guo](https://github.com/at15) has waived all copyright and related or neighboring rights to this work.
