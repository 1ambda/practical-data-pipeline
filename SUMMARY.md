# Table of contents

* [Practical Data Pipeline](README.md)
* [시작 전에 드리는 당부의 말](undefined.md)

## 01 - 데이터 인프라 <a href="01-data-infra" id="01-data-infra"></a>

* [1.X 데이터 파이프라인](01-data-infra/1.1.md)
* [1.X 데이터 입수 (Ingestion)](01-data-infra/1.2.md)
* [1.X 데이터 가공 (Processing)](01-data-infra/1.x-processing.md)
* [1.X 데이터 저장 (Storage)](01-data-infra/1.x-storage.md)
* [1.X 데이터 분석 (Analysis)](01-data-infra/1.3.md)

## 02 - 데이터 처리 <a href="02-processing" id="02-processing"></a>

* [2.1 데이터 처리](02-processing/2.1.md)
* [2.2 배치 (Batch) 처리](02-processing/2.2-batch/README.md)
  * [2.1.1 Spark Intro](02-processing/2.2-batch/untitled.md)
  * [2.1.2 Spark Tutorial](02-processing/2.2-batch/2.1.2-spark-architecture.md)
  * [2.1.3 Spark Concept](02-processing/2.2-batch/2.1.3-spark-concept.md)
  * [2.1.4 Spark Architecture](02-processing/2.2-batch/2.1.4-spark-architecture.md)
  * [2.1.X Spark DataFrame](02-processing/2.2-batch/2.1.x-spark-dataframe.md)
  * [2.1.X Spark Persistence](02-processing/2.2-batch/2.1.x-spark-persistence.md)
  * [2.1.X Spark Cache](02-processing/2.2-batch/2.1.x-spark-cache.md)
  * [2.1.X Spark SQL & Table](02-processing/2.2-batch/2.1.x-spark-sql-and-table.md)
  * [2.1.X Spark Join](02-processing/2.2-batch/2.1.x-spark-join.md)
  * [2.1.X Spark Memory](02-processing/2.2-batch/2.1.5-spark-memory-management.md)
  * [2.1.X Spark Environment](02-processing/2.2-batch/2.1.3-spark-mode.md)
  * [2.1.X Spark Metastore](02-processing/2.2-batch/2.1.x-spark-metastore.md)
  * [2.1.6 PySpark](02-processing/2.2-batch/2.1.6-pyspark.md)
* [2.3 워크플로우 (Workflow) 관리](02-processing/2.3-workflow.md)
* [2.4 스트림 (Stream) 처리](02-processing/2.4-stream.md)

## 04 - 데이터 스토리지 <a href="04-data-storage" id="04-data-storage"></a>

* [4.1 Kafka](04-data-storage/untitled.md)
* [4.2 Redis](04-data-storage/4.2.md)
* [4.3 RDB (MySQL)](04-data-storage/4.3-rdb-mysql.md)
* [4.4 ElasticSearch](04-data-storage/4.4.md)
* [4.5 KV Storage (DynamoDB)](04-data-storage/4.5-kv-storage-dynamodb.md)
* [4.6 Druid](04-data-storage/4.6-druid.md)

## 05 - 데이터 애플리케이션 <a href="05-data-application" id="05-data-application"></a>

* [5.1 데이터 서비스](05-data-application/untitled.md)
* [5.2 통계 서비스](05-data-application/5.2.md)
* [5.3 추천 서비스](05-data-application/5.3.md)
* [5.4 A/B 테스팅](05-data-application/5.4.md)

## 08 - Case Study

* [Week 1 - Data Pipeline](08-case-study/week-1-data-pipeline.md)
* [Week 2 - EMR & Kubernetes](08-case-study/week-2-emr-and-kubernetes.md)
* [Week 3 - Metastore](08-case-study/week-3-metastore.md)
* [Week 4 - KV & Delta Storage](08-case-study/week-4-kv-and-delta-storage.md)
* [Week 5 - Kafka Rebalancing](08-case-study/week-5-kafka-rebalancing.md)
* [Week 6 - ML Pipeline](08-case-study/week-6-ml-pipeline.md)

## 09 - 설치 및 환경 구성 <a href="09-installation" id="09-installation"></a>

* [Spark 설치 및 환경 구성](09-installation/spark/README.md)
  * [Spark - Local Shell 환경](09-installation/spark/spark-local-shell.md)
  * [Spark - Local Jupyter 환경](09-installation/spark/spark-local-jupyter.md)
  * [Spark - Kubernetes 환경](09-installation/spark/spark-kubernetes.md)
  * [Spark - EMR 환경](09-installation/spark/spark-emr.md)
  * [Spark - Databricks 환경 (SaaS)](09-installation/spark/spark-databricks-saas.md)
* [Flink 설치 및 환경 구성](09-installation/flink.md)
* [Kafka 설치 및 환경 구성](09-installation/kafka.md)
* [MySQL 설치 및 환경 구성](09-installation/mysql.md)
* [DynamoDB 사용을 위한 환경 구성](09-installation/dynamodb.md)
* [ElasticSearch 설치 및 환경 구성](09-installation/elasticsearch.md)
* [Presto 설치 및 환경 구성](09-installation/presto.md)
* [Druid 설치 및 환경 구성](09-installation/druid.md)
