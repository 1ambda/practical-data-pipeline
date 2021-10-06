# 2.1 데이터 처리

데이터를 처리하기 위한 프레임워크는 다양합니다. 이 글에서는 데이터를 분산처리하기 위해 자주 쓰이는 두 가지 프레임워크에 대해 이야기 할 예정입니다.

* [Apache Spark ](https://spark.apache.org/)
* [Apache Flink](https://flink.apache.org/) 

Apache Spark 는 배치 처리를 위해 많이 활용됩니다. 경우에 따라 스트림 처리를 위해 사용되는 경우도 있습니다. 메타스토어로부터 데이터를 테이블 형태로 쉽게 읽어오고 가공하는 것이 가능하며, 사용자의 편의에 따라 다양한 API 수준을 지원합니다.

* [Spark SQL](https://spark.apache.org/docs/latest/sql-programming-guide.html#sql)
* [Spark Dataframe / DataSet API](https://spark.apache.org/docs/latest/sql-programming-guide.html#datasets-and-dataframes) 

Spark 를 활용하면, 도메인 로직을 모듈로 만들고 배치 및 스트림에서 애플리케이션 \(이하 Application\) 에서 동일한 로직을 사용할 수 있습니다. 예를 들어

* Kafka 에서 데이터를 읽어 처리하는 스트림 Application 있을 때
* 장애 등의 이유로 동일한 데이터를 Kafka 가 아닌 S3 등 스토리지에서 읽어 배치처리를 할 경우
* 동일한 모듈을 이용해 가공할 수 있습니다

Flink 또한 배치 및 스트림 처리를 위한 API 를 지원합니다. 다만 이 글에서는 스트림을 위한 내용을 위주로 설명합니다.

