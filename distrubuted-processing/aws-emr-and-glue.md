# ▹ AWS EMR & Glue

[AWS Glue Vs. EMR: Which One is Better?](https://www.knowledgenile.com/blogs/aws-glue-vs-emr/)

[AWS EMR vs GLUE evaluation for ETL workflow](https://www.linkedin.com/pulse/aws-emr-vs-glue-evaluation-etl-workflow-data-rajat-kumar)  
  - engineer 입장에서 평가한 비교 

## Glue

📺 [효율적인 빅데이터 분석 및 처리를 위한 Glue, EMR 활용](https://www.youtube.com/watch?v=aavblrrk4Fo) - by AWS

[Implementing ETL job using AWS Glue](https://techmagie.wordpress.com/2019/07/29/implementing-etl-job-using-aws-glue/)  
  -  _AWS console로 Glue를 활용하는 예시 설명_

[Best practices to scale Apache Spark jobs and partition data with AWS Glue](https://aws.amazon.com/ko/blogs/big-data/best-practices-to-scale-apache-spark-jobs-and-partition-data-with-aws-glue/) - by AWS

[Optimize memory management in AWS Glue](https://aws.amazon.com/blogs/big-data/optimize-memory-management-in-aws-glue/) - by AWS  
  -  데이터 로딩\(s3, jdbc\)에 대한 최적화가 많음 

[AWS Glue: Lesson learned…](https://medium.com/@techatcore/aws-glue-lesson-learned-437d73f3e988)

📊 [우리는 왜 glue를 버렸나?](https://www.slideshare.net/Thomas_Hyun_Park/20200206-glue) - by 메쉬 코리아

#### TEST

[Local Debugging of AWS Glue Jobs](https://support.wharton.upenn.edu/help/glue-debugging) - by Wharton  
  - Local에 aws glue lib와 glue용 spark를 설치하는 방법

[Developing AWS Glue ETL jobs locally using a container](https://aws.amazon.com/blogs/big-data/developing-aws-glue-etl-jobs-locally-using-a-container/) - by AWS  
  - AWS 공식 지원 docker 기반으로 TEST \(jupyter, zeppelin도 포함\) 

## EMR \(Spark\)

[How Drop used the Amazon EMR runtime for Apache Spark to halve costs and get results 5.4 times faster](https://aws.amazon.com/blogs/big-data/how-drop-used-the-amazon-emr-runtime-for-apache-spark-to-halve-costs-and-get-results-5-4-times-faster/) - by AWS

[Running Apache Spark on AWS](https://medium.com/acast-tech/running-apache-spark-on-aws-81a5f766d3a6)

[AWS Elastic MapReduce \(EMR\) — 6 Caveats You Shouldn’t Ignore](https://towardsdatascience.com/aws-elastic-mapreduce-emr-6-caveats-you-shouldnt-ignore-7a3e260e19c1)

[Reducing AWS EMR data processing costs](https://medium.com/teads-engineering/reducing-aws-emr-data-processing-costs-7c12a8df6f2a)

[How to Set-up a cost-effective AWS EMR cluster and Jupyter Notebooks for SparkSQL](https://medium.com/@andcy7/how-to-set-up-a-cost-effective-aws-emr-cluster-and-jupyter-notebooks-for-sparksql-552360ffd4bc)

[PEX — The secret sauce for the perfect PySpark deployment of AWS EMR workloads](https://towardsdatascience.com/pex-the-secret-sauce-for-the-perfect-pyspark-deployment-of-aws-emr-workloads-9aef0d8fa3a5)  
  -  _Spot Instance로 EMR을 사용할 때 빠르게 application을 구성하는 방법 설명_

[Zipping and Submitting PySpark Jobs in EMR Through Lambda Functions](https://towardsdatascience.com/zipping-and-submitting-pyspark-jobs-in-emr-through-lambda-functions-46a58a496d9e)  
  _-  Lambda로 Pyspark job 실행하는 방법\( project 형식 + gitlab CI\)_

[AWS -EMR Monitoring and Alerting Bot](https://medium.com/swlh/aws-emr-monitoring-and-alerting-bot-20db4b9662)  
  -  _Airflow와 boto3를 활용해서 slack or email로 메세지 전송_

\_\_



