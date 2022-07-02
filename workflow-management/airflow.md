# Airflow

📺 [Airflow를 활용하여 아름다운 데이터 파이프라인 구성하기](https://if.kakao.com/2019/program?sessionId=de3ff829-ac4c-4090-9ea1-046df55429a0) - in ifkakao 2019

📺 [Apache Airflow for beginners](https://www.youtube.com/watch?v=YWtfU0MQZ\_4) - in PyConDE 2019\
&#x20; \-  _Data -> Postgres -> S3(Filtered) -> HTML template -> EMAIL(SMTP) 파이프라인_

[Why Apache Airflow Is a Great Choice for Managing Data Pipelines](https://towardsdatascience.com/why-apache-airflow-is-a-great-choice-for-managing-data-pipelines-48effcce3e41)

[Getting started with Apache Airflow](https://towardsdatascience.com/getting-started-with-apache-airflow-df1aa77d7b1b)\
&#x20; \-  _전반적인 기초 설명_

[airflow tutorial(1 \~ 7) - Apply Data Science](https://www.applydatascience.com/page2/) (자막 X )\
&#x20; \-  자체 docker image 활용 / 기초 설명과 bash 파이프라인 예제 ( + Google Composer, Bigquery 예제 )

[Get Started with Airflow + Google Cloud Platform + Docker](https://medium.com/@junjiejiang94/get-started-with-airflow-google-cloud-platform-docker-a21c46e0f797)

[Airflow Schedule Interval 101](https://towardsdatascience.com/airflow-schedule-interval-101-bbdda31cc463)\
&#x20; \-  Airflow Scheduling에 대한 이해\
&#x20; \-  UI에 표시되 execution\_date와 start\_date 차이

[Is Apache Airflow good enough for current data engineering needs?](https://towardsdatascience.com/is-apache-airflow-good-enough-for-current-data-engineering-needs-c7019b96277d)\
&#x20; \-  Airflow의 단점에 대한 설명&#x20;

## Setting

[A Gentle Introduction To Understand Airflow Executor](https://towardsdatascience.com/a-gentle-introduction-to-understand-airflow-executor-b4f2fee211b1)

[https://crontab.guru/](https://crontab.guru/)\
&#x20; \- cron schedule 표현을  시간으로 알려주는 사이트&#x20;

[Apache Airflow: Dask Executor](https://medium.com/@bpleines5qa/apache-airflow-dask-executor-17eea5d26a8b)

[How to deploy Apache Airflow with Celery on AWS](https://towardsdatascience.com/how-to-deploy-apache-airflow-with-celery-on-aws-ce2518dbf631)\
&#x20; \-  _ECS(fargate)를 활용하여 구축_

## Workflow (DAG)

[ETL-Pipelines-With-Airflow](http://michael-harmon.com/blog/AirflowETL.html#ETL-Pipelines-With-Airflow)\
&#x20; \-  _API를 통해 크롤링한 데이터를 MySQL에 업로드하는 예제_

[Implementing the functional data engineering paradigm in data load processes by using Airflow](https://towardsdatascience.com/implementing-the-functional-data-engineering-paradigm-in-data-load-processes-by-using-airflow-61d3bae486b0)\
&#x20; \-  _Functional Data Engineering 개념 기반 Pyspark로 MySQL => S3 데이터 업로드_

[Generalizing data load processes with Airflow](https://towardsdatascience.com/generalizing-data-load-processes-with-airflow-a4931788a61f)\
&#x20; \-  _Config와 Factory 패턴을 활용한 DAG 생성_

[Build your first data warehouse with Airflow on GCP](https://towardsdatascience.com/build-your-first-data-warehouse-with-airflow-on-gcp-fdd0c0ad91bb)

## Airflow Tips

[jgohman/Awesome Apache Airflow](https://github.com/jghoman/awesome-apache-airflow)

[Automated Maintenance for Apache Airflow](https://blog.clairvoyantsoft.com/automated-maintenance-for-apache-airflow-8d844f32737d)\
&#x20; \-  _airflow를 오래 운영하면서 생기는 문제(메타DB, 로그 등) 해결에 관한 내용_

[AIRFLOW PLUGINS example](https://adataguru.net/airflow-plugins/)\
&#x20; \-  _Custom Plugin(custom hook ,operator, ...)을 만들어서 활용하는 예제_

* [Airflow: Lesser Known Tips, Tricks, and Best Practises](https://medium.com/datareply/airflow-lesser-known-tips-tricks-and-best-practises-cf4d4a90f8f)&#x20;
* [We’re All Using Airflow Wrong and How to Fix It](https://medium.com/bluecore-engineering/were-all-using-airflow-wrong-and-how-to-fix-it-a56f14cb0753)&#x20;
* [Handling API Errors with Airflow](https://medium.com/stashaway-engineering/handling-api-errors-with-airflow-79738868d663)&#x20;
