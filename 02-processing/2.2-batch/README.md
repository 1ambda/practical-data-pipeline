# 2.2 배치 \(Batch\) 처리

배치 \(Batch\) 처리는 비교적 긴 주기로, 데이터를 처리하는 것을 말합니다. 

개념을 설명하는 특정 문서에서는 배치 처리는 데이터를 특정 기간동안 모아서 처리하는 것을 말하고, 스트림 처리는 매 건마다 개별로 처리한다고 구별하는 경우도 있습니다. \[1\] 그러나 프레임워크에 따라 스트림 처리라 하더라도 Native Processing / Micro Batch 등 구현 방법이 다른 경우도 있어

이 글에서는 프레임워크가 어떻게 구현되었는지 보다는 Application 이 실행되는 패턴에 따라 분류하여 파이프라인 관점에서 그 용도에 따라 구분합니다. 예를 들어

* Application 이 실행되고 데이터를 처리한 후 종료되며 비교적 긴 주기 \(1시간, 1일 등\) 마다 실행될 경우를 배치 처리로 설명합니다
* 반면 Application 이 실행되어 있는 상태로 계속 유지되며, 비교적 짧은 주기 \(수백 milils, 수초 등\) 마다 데이터를 반복적으로 읽어 처리하는 경우를 스트림 처리로 설명합니다.

배치 처리를 위해 사용되는 Framework 는 다양하나, 이 글에서는 Spark 를 위주로 설명합니다. 



\[1\] [https://www.precisely.com/blog/big-data/big-data-101-batch-stream-processing](https://www.precisely.com/blog/big-data/big-data-101-batch-stream-processing)

