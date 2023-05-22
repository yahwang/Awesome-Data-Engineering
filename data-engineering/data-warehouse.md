# Data Warehouse

[How to architect the perfect Data Warehouse](https://medium.com/@lewisdgavin/how-to-architect-the-perfect-data-warehouse-b3af2e01342e)\
&#x20; _-  Key warehousing technique - Staging, Master and Reporting layer_

[Data Warehousing: Basics of Relational Vs Star Schema Data Modeling](https://medium.com/@daryl.ung/data-warehousing-basics-of-relational-vs-star-schema-data-modeling-75a68eeaf0e3)\
&#x20; _-  일반적인 DB모델링과 Star schema 비교_

[Snowflake Schemas vs. Star Schemas: What Are They and How Are They Different?](https://www.xplenty.com/blog/snowflake-schemas-vs-star-schemas-what-are-they-and-how-are-they-different/) - by Xplenty\
&#x20; _-  Snowflake는 Star schema의 dimension table을 정규화_

### Dimension Table - Star Schema

[Surrogate Key vs Natural Key Differences](https://www.mssqltips.com/sqlservertip/5431/surrogate-key-vs-natural-key-differences-and-when-to-use-in-sql-server/)\
&#x20; \-  _DW에서 Primary Key를 대체키(e.g. sequence ID)와 자연키 중 선정할 경우 장/단점_

[Slowly Changing Dimension ? What’s That ?](https://medium.com/@atriadplt/slowly-changing-dimension-whats-that-8ebf7cfef113)\
&#x20; \-  _SCD(Slowly Changing Dimension)에 대한 이해 ( historical data를 어떻게 다룰 것인가 )_

* 📺 [Slowly Changing Dimensions For Data Engineers](https://www.youtube.com/watch?v=1FZ7et0pN4c) - by Ben R

[Managing Dimensions - Slowly and Rapidly Changing Dimension](https://towardsdatascience.com/building-a-modern-batch-data-warehouse-without-updates-7819bfa3c1ee#beba)\
&#x20; \-  _dimension 테이블을 snapshot으로 관리하는 방법 (e.g. user 테이블)_

### Fact Table - Star Schema

[Managing Facts](https://towardsdatascience.com/building-a-modern-batch-data-warehouse-without-updates-7819bfa3c1ee#8d09)
