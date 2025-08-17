---
description: OLAP 분석 도구에 대한 간단한 정리
---

# Summary

[Top 10 Real-Time OLAP Databases in 2025](https://estuary.dev/blog/real-time-olap-databases/) - by Estuary

## 고려할 요소

* reatime + batch ingestion
* 표준 SQL  / 복잡한 쿼리 / UPSERT
* 중복 제거 / exactly once
* open table format 연동 ( external table )

## ClickHouse

{% hint style="info" %}
Toss
{% endhint %}

장점

* 커뮤니티가 가장 큼 ( 가장 일반적인 용도로 적합 )

단점

* 복잡한 JOIN 제한적
* open table format 지원 제한적

## StarRocks

{% hint style="info" %}
Naver, Toss
{% endhint %}

[https://www.starrocks.io/](https://www.starrocks.io/)

장점

* Doris의 fork로 시작되어, 업데이트가 빠르고 성능이 가장 좋음을 강조함
* Cross Catalog Query

단점

*

2025 [StarRocks의 도입 배경과 성능 최적화](https://d2.naver.com/helloworld/1168674) - in naver D2

2025 [Real-Time Analytics at Scale: Why iQIYI, a Leading Streaming Platform, Chose StarRocks](https://medium.com/starrocks-engineering/real-time-analytics-at-scale-why-we-use-starrocks-0aa3c859cbeb) - in Medium

## Apache Doris

[https://doris.apache.org/](https://doris.apache.org/)

장점

* Full Text Serach, Log Analytics
  * ElasticSearch의 대체제를 강조
* Cross Catalog Query ( Federated Analytics **)**

단점

*

2025 [Elasticsearch와 ClickHouse를 넘어서는 옵저버빌리티 엔진은? Apache Doris의 압도적 선택지](https://digitalbourgeois.tistory.com/1465)

## Apache Pinot

{% hint style="info" %}
Kakaopay
{% endhint %}

[https://pinot.apache.org/](https://pinot.apache.org/)

장점

* 내장 Kafka Streaming Ingestion 지원

단점

* open table format 지원이 아직 없어보임
* github star가 비교적 적음

2025 [실시간 OLAP을 위한 Apache Pinot 운영 노하우](https://tech.kakaopay.com/post/realtime-olap-with-apache-pinot/) - in kakaopay tech\


## Apache Druid

{% hint style="info" %}
Kakao, Toss
{% endhint %}

[https://druid.apache.org/](https://druid.apache.org/)

&#x20;장점

* 내장 Kafka Streaming Ingestion 지원 및 Low latency 강점
* Clickstream analysis와 같은 time series 분석이 강점
* RTB(Real Time Bidding)에 활용하는 경우가 있음

단점

* Druid SQL을 사용, 복잡한 쿼리 불가능
* JOIN이 어려움 ( Ingestion 전에 JOIN 전략이 필요 )
* open table format 지원 X

2024 ![](<../.gitbook/assets/image (8).png>) [AI 기반 광고 추천 파이프라인에서 스파크 스트리밍의 배포 및 모니터링 전략](https://www.youtube.com/watch?v=knvmbxqaMQk\&t=100s) - in kakao tech\
&#x20; 광고추천팀 실시간 지표를 Druid에 적재
