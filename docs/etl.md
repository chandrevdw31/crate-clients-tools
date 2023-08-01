(etl)=
# ETL with CrateDB

Use ETL applications and frameworks for transferring data in and out of CrateDB.

```{note}
This section is a work in progress.
```


## General

- [Automating recurrent CrateDB queries]


## Apache Airflow

[Apache Airflow] is a software platform to programmatically author, schedule, and
monitor workflows, written in Python.

```{div}
:style: "float: right"
[![](https://19927462.fs1.hubspotusercontent-na1.net/hub/19927462/hubfs/Partner%20Logos/392x140/Apache-Airflow-Logo-392x140.png?width=784&height=280&name=Apache-Airflow-Logo-392x140.png){w=180px}](https://airflow.apache.org/)
```

A set of starter tutorials.

- [Automating the import of Parquet files with Apache Airflow]
- [Updating stock market data automatically with CrateDB and Apache Airflow]
- [Automating stock data collection and storage with CrateDB and Apache Airflow]

A set of elaborated tutorials, including blueprint implementations.

- [Automating export of CrateDB data to S3 using Apache Airflow]
- [Implementing a data retention policy in CrateDB using Apache Airflow]
- [CrateDB and Apache Airflow: Building a data ingestion pipeline]
- [Building a hot and cold storage data retention policy in CrateDB with Apache Airflow]

```{seealso}
[CrateDB and Apache Airflow]
```


## Apache Flink

```{div}
:style: "float: right"
[![](https://flink.apache.org/flink-header-logo.svg){w=180px}](https://flink.apache.org/)
```

[Apache Flink] is a framework and distributed processing engine for stateful
computations over unbounded and bounded data streams. Flink has been designed
to run in all common cluster environments, perform computations at in-memory
speed and at any scale.

- [Build a data ingestion pipeline using Kafka, Flink, and CrateDB]
- [Community Day: Stream processing with Apache Flink and CrateDB]
- [Executable stack: Apache Kafka, Apache Flink, and CrateDB]

![](https://flink.apache.org/img/flink-home-graphic.png){h=200px}


## Apache Kafka

```{div}
:style: "float: right"
[![](https://kafka.apache.org/logos/kafka_logo--simple.png){w=180px}](https://kafka.apache.org/)
```

[Apache Kafka] is an open-source distributed event streaming platform used by
thousands of companies for high-performance data pipelines, streaming analytics,
data integration, and mission-critical applications. 

- [Data Ingestion using Kafka and Kafka Connect]

```{seealso}
[CrateDB and Apache Kafka]
```


## Debezium

```{div}
:style: "float: right"
[![](https://debezium.io/assets/images/color_white_debezium_type_600px.svg){w=180px}](https://debezium.io/)
```

[Debezium] is an open source distributed platform for change data capture. After
pointing it at your databases, you are able to subscribe to the event stream of
all database update operations.

- [Tutorial: Replicating data to CrateDB with Debezium and Kafka]
- [Webinar: How to replicate data from other databases to CrateDB with Debezium and Kafka]



## Node-RED

```{div}
:style: "float: right"
[![](https://global.discourse-cdn.com/business6/uploads/nodered/original/1X/778549404735e222c89ce5449482a189ace8cdae.png){w=180px}](https://nodered.org/)
```

[Node-RED] is a programming tool for wiring together hardware devices, APIs
and online services within a low-code programming environment for event-driven
applications. It allows orchestrating message flows and transformations through
an intuitive web interface.

It provides a browser-based editor that makes it easy to wire together flows
using the wide range of elements called "nodes" from the palette that can be
deployed to its runtime in a single-click.

- [Ingesting MQTT messages into CrateDB using Node-RED]

```{seealso}
[CrateDB and Node-RED]
```


## pandas

[pandas] is a fast, powerful, flexible and easy to use open source data analysis
and manipulation tool, built on top of the Python programming language. 

```{div}
:style: "float: right"
[![](https://pandas.pydata.org/static/img/pandas.svg){w=180px}](https://pandas.pydata.org/)
```

- [Importing Parquet files into CrateDB using Apache Arrow and SQLAlchemy]
- [Guide to efficient data ingestion to CrateDB with pandas]
- [Guide to efficient data ingestion to CrateDB with pandas and Dask]


## Telegraf

```{div}
:style: "float: right"
[![](https://raw.githubusercontent.com/influxdata/branding/master/docs/img/logo-usage/logo-symbol-black.svg){w=180px}](https://www.influxdata.com/time-series-platform/telegraf/)
```

[Telegraf] is a leading open source server agent to help you collect metrics
from your stacks, sensors, and systems. More than 200 adapters to connect
to other systems leaves nothing to be desired.

- [Use CrateDB With Telegraf, an Agent for Collecting & Reporting Metrics]

![](https://www.influxdata.com/wp-content/uploads/Main-Diagram_06.01.2022v1.png){h=200px}

```{seealso}
[CrateDB and Telegraf]
```


[Apache Airflow]: https://airflow.apache.org/
[Apache Flink]: https://flink.apache.org/
[Apache Kafka]: https://kafka.apache.org/
[Automating recurrent CrateDB queries]: https://community.crate.io/t/automating-recurrent-cratedb-queries/788
[Automating export of CrateDB data to S3 using Apache Airflow]: https://community.crate.io/t/cratedb-and-apache-airflow-automating-data-export-to-s3/901
[Automating stock data collection and storage with CrateDB and Apache Airflow]: https://community.crate.io/t/automating-stock-data-collection-and-storage-with-cratedb-and-apache-airflow/990
[Automating the import of Parquet files with Apache Airflow]: https://community.crate.io/t/automating-the-import-of-parquet-files-with-apache-airflow/1247
[Build a data ingestion pipeline using Kafka, Flink, and CrateDB]: https://dev.to/crate/build-a-data-ingestion-pipeline-using-kafka-flink-and-cratedb-1h5o
[Building a hot and cold storage data retention policy in CrateDB with Apache Airflow]: https://community.crate.io/t/cratedb-and-apache-airflow-building-a-hot-cold-storage-data-retention-policy/934
[Community Day: Stream processing with Apache Flink and CrateDB]: https://crate.io/blog/cratedb-community-day-2nd-edition-summary-and-highlights
[CrateDB and Apache Airflow]: https://crate.io/integrations/cratedb-and-apache-airflow
[CrateDB and Apache Airflow: Building a data ingestion pipeline]: https://community.crate.io/t/cratedb-and-apache-airflow-building-a-data-ingestion-pipeline/926 
[CrateDB and Apache Kafka]: https://crate.io/integrations/cratedb-and-kafka
[CrateDB and Node-RED]: https://crate.io/integrations/cratedb-and-node-red
[CrateDB and Telegraf]: https://crate.io/integrations/cratedb-and-telegraf
[Data Ingestion using Kafka and Kafka Connect]: https://crate.io/docs/crate/howtos/en/latest/integrations/kafka-connect.html
[Debezium]: https://debezium.io/
[Executable stack: Apache Kafka, Apache Flink, and CrateDB]: https://github.com/crate/cratedb-examples/tree/main/stacks/kafka-flink
[Guide to efficient data ingestion to CrateDB with pandas]: https://community.crate.io/t/guide-to-efficient-data-ingestion-to-cratedb-with-pandas/1541
[Guide to efficient data ingestion to CrateDB with pandas and Dask]: https://community.crate.io/t/guide-to-efficient-data-ingestion-to-cratedb-with-pandas-and-dask/1482
[Implementing a data retention policy in CrateDB using Apache Airflow]: https://community.crate.io/t/implementing-a-data-retention-policy-in-cratedb-using-apache-airflow/913 
[Importing Parquet files into CrateDB using Apache Arrow and SQLAlchemy]: https://community.crate.io/t/importing-parquet-files-into-cratedb-using-apache-arrow-and-sqlalchemy/1161
[Ingesting MQTT messages into CrateDB using Node-RED]: https://community.crate.io/t/ingesting-mqtt-messages-into-cratedb-using-node-red/803
[Node-RED]: https://nodered.org/
[pandas]: https://pandas.pydata.org/
[Telegraf]: https://www.influxdata.com/time-series-platform/telegraf/
[Tutorial: Replicating data to CrateDB with Debezium and Kafka]: https://community.crate.io/t/replicating-data-to-cratedb-with-debezium-and-kafka/1388
[Updating stock market data automatically with CrateDB and Apache Airflow]: https://community.crate.io/t/updating-stock-market-data-automatically-with-cratedb-and-apache-airflow/1304
[Use CrateDB With Telegraf, an Agent for Collecting & Reporting Metrics]: https://crate.io/blog/use-cratedb-with-telegraf-an-agent-for-collecting-reporting-metrics
[Webinar: How to replicate data from other databases to CrateDB with Debezium and Kafka]: https://crate.io/resources/webinars/lp-wb-debezium-kafka