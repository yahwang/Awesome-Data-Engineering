# Prefect

[Why Not Airflow? - An overview of the Prefect engine for Airflow users](https://medium.com/the-prefect-blog/why-not-airflow-4cfa423299c4)  
  -  Airflow와 비교하여 Prefect의 장점을 설명 

[Prefect Server 101: Deploying to Google Cloud Platform](https://medium.com/the-prefect-blog/prefect-server-101-deploying-to-google-cloud-platform-47354b16afe2)

## Prefect 개요

1. Risk Management에 초점을 둔 Tool \(Negative Data Engineering\)
2. Functional API 제공 - Task를 함수처럼 활용 \(Pythonic\) [  Functional API - Prefect Docs](https://docs.prefect.io/core/concepts/flows.html#apis)
3. Realtime UI 제
4. Dask를 default executor로 사용  - Dask의 Low latency를 활용하여 task 간 delay 최소화
5. Central scheduler를 없애고 flow\(&lt;-&gt;DAG\) 각각이 자체적으로 수행된다. - Scheduling Overhead 최소화
6. ad-hoc run 및 irregular 스케줄 설정이 가능하다.
7. result handler가 task output을 관리한다. - Airflow의 XCOM 문제\(META DB I/O, expiration, push 오류\) 해결



