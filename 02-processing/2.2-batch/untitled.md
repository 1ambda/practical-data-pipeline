# 2.1.1 Apache Spark

[Apache Spark](https://spark.apache.org) 는 데이터 처리를 위한 범용 프레임워크 입니다. 데이터 파이프라인을 위해 많이 사용되며, 산업 표준에 가깝습니다. 

* Spark SQL / Dataframe / Dataset API 등 다양한 형태의 API 를 제공해 사용자 편의 및 개발 환경에 따라 자유롭게 선택할 수 있습니다. 
* 다양한 Storage 와 연동되는 Connector 가 존재합니다. 
  * [Kafka Connector](https://spark.apache.org/docs/latest/structured-streaming-kafka-integration.html), [ElasticSearch Connector](https://www.elastic.co/guide/en/elasticsearch/hadoop/current/spark.html), [MongoDB Connector](https://docs.mongodb.com/spark-connector/current/), [Redis Connector](https://github.com/RedisLabs/spark-redis), [Cassandra Connector](https://github.com/datastax/spark-cassandra-connector)
* Scala 이외에도 Python, R 등 다양한 언어를 지원하며 데이터 처리를 위한 라이브러리가 많이 존재합니다.  ([Spark 관련 Third Party 프로젝트 목록](https://spark.apache.org/third-party-projects.html))
  * [PySpark](http://spark.apache.org/docs/latest/api/python/)
  * [SparkR (R on Spark)](https://spark.apache.org/docs/latest/sparkr.html)
  * [Spark MLLib (머신러닝 라이브러리)](https://spark.apache.org/docs/latest/ml-guide.html)
  * [GraphX (그래프 데이터 처리 라이브러리)](https://spark.apache.org/docs/latest/graphx-programming-guide.html)
* 다양한 실행 모드 및 환경을 지원해 어느 환경에서나 사용할 수 있습니다.
  * Spark Shell 
  * Local Mode
  * Client Mode
  * Cluster Mode
  * Standalone / Yarn / Kubernetes

따라서 원하는 환경에서 다양한 커넥터를 이용해 데이터를 추출하고, 원하는 언어와 API 그리고 라이브러리를 이용해 분산처리를 수행할 수 있는 **범용** 데이터 처리 도구입니다.
