---
description: Pandas를 보완 혹은 대체하는 역할
---

# Beyond Pandas

## Duckdb

> 기본적으로 로딩 및 데이터 처리 속도가 빠름 ( 코드 최적화에 대한 고민이 줄어듬 )
>
> SQL 분석으로 사용성이 높음

[https://duckdb.org/](https://duckdb.org/)

[Pandas 대신 SQL로 분석해보자 with DuckDB](https://yahwang.github.io/posts/100)

[데이터 분석계의 신성, DuckDB를 알아보자](https://www.youtube.com/watch?v=LUHvc2cMvwA\&t=66s) - by 데이터홀릭

## Dask

> Dask is built on top of pandas\
> data = chunk size(blocks) \* partitions / memory 동시 사용량 = chunk size \* cores\
> Multi-Processing(Parallel) 연산 / Cluster 구성 가능 / RAPIDS - GPU 연산 가능 \
> Numpy, Pandas, Scikit-learn과 호환하여 활용도가 높음

> Pandas에서 느린 연산은 Dask에서도 느림\
> Parallel 처리가 어려운 함수들은 미지원  e.g. 정렬

**recommended only for datasets that don’t fit in the main memory ( 1차 전처리 용도 )**

[Are you still using Pandas for big data?](https://towardsdatascience.com/are-you-still-using-pandas-for-big-data-12788018ba1a)\
&#x20; \-  pandas로 다루기 힘든 큰 데이터에는 Dask를 함께 활용

[A Data Scientist’s Intro to Parallel Computing With _Dask_](https://towardsdatascience.com/a-data-scientists-intro-to-parallel-computing-with-dask-4c1b4a464579)

[Comparison to Spark _- Dask Docs_](https://docs.dask.org/en/latest/spark.html)\
&#x20; _- Dask와 Spark 비교 (Dask는 complex and flexible parallelism 처리에 장점 )_

[DASK Scheduler Dashboard: Understanding resource and task allocation in Local Machines](https://medium.com/@kartikbhanot/dask-scheduler-dashboard-understanding-resource-and-task-allocation-in-local-machines-bc5aa60eca6e)

## Vaex

> 문자열 처리에 특히 뛰어남 \
> HDF5 파일 포맷이어야 하는 불편함이 있음

[7 reasons why I love Vaex for data science](https://towardsdatascience.com/7-reasons-why-i-love-vaex-for-data-science-99008bc8044b)

[Flying high with Vaex: analysis of over 30 years of flight data in Python](https://towardsdatascience.com/https-medium-com-jovan-veljanoski-flying-high-with-vaex-analysis-of-over-30-years-of-flight-data-in-python-b224825a6d56)

[How to analyse 100 GB of data on your laptop with Python](https://towardsdatascience.com/how-to-analyse-100s-of-gbs-of-data-on-your-laptop-with-python-f83363dda94)

[Vaex: A DataFrame with super strings](https://towardsdatascience.com/vaex-a-dataframe-with-super-strings-789b92e8d861)

## Swifter

> 함수를 정의한 후 .apply를 통해 함수를 실행할 때 활용하는 라이브러리 ( 병렬 처리 )\
> Vectorized function 형태(numpy)로 사용해야 빠름. 그렇지 않으면 더 느릴 수 있음 \
> Non-vectorized function의 경우, dask 병렬 처리 또는 pandas apply 중 선택 수행&#x20;

[Speed up your Pandas Processing with Swifter](https://towardsdatascience.com/speed-up-your-pandas-processing-with-swifter-6aa314600a13)\
&#x20; \- Vectorized function 사용에 대한 예시

## ETC

[Faster Pandas with parallel processing: cuDF vs. Modin](https://towardsdatascience.com/faster-pandas-with-parallel-processing-cudf-vs-modin-f2318c594084)\
&#x20; \-  _Pandas보다 항상 빠른 것은 아니다. (각자 장단점이 있음)_

참고 : [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/)\
&#x20; \-  _single machine에서 다양한 라이브러리로 groupby, join 연산 수행 시 성능 비교_
