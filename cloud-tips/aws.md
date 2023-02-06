# AWS

### General

[https://kr.developers.io/](https://kr.developers.io/) - by Classmethod\
&#x20; \- AWS서비스 사용 관련 팁들이 많음

[GS네오텍(WiseN) 블로그](https://blog.wisen.co.kr/?cat=3)

### Network

[AWS IAM Hands On Lab](https://whchoi98.gitbook.io/aws-iam/) - by AWS

[Your Comprehensive Guide to Understanding AWS Data Transfer Costs](https://medium.com/@mulupuru/your-comprehensive-guide-to-understanding-aws-data-transfer-costs-f5c8241d65ed)

📺 [AWS의 눈 - Cloud Watch](https://www.youtube.com/watch?v=jGryI-hBA38) - by 생활코딩

&#x20;[AWS SSM로 VPN없이 Private 자원 접근하기](https://beomi.github.io/2020/02/13/AWS-SSM-with-Bastion/) - by Beomi's Tech Blog\
&#x20; \-  _AWS SSM + Bastion EC2 + SSH 터널링_

[AWS SSM 배스천호스트 터널링으로 RDS(PGDB) 에 연결하기](http://blog.haandol.com/2020/05/01/bastion-host-tunnel-rds.html)

### EC2

[Which is better, gp2 or gp3 EBS volume types?](https://ahmedahamid.com/which-is-better/?fbclid=IwAR3TSSM436Dn1RmQfTCVRSyeXgt\_Sfjw6TgmPsN7KEwVKTeZNcuuMhnnIFc)\
&#x20; _- 비용 효율적인 EBS Volume 설정 방법_

[Extend a Linux file system after resizing a volume](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/recognize-expanded-volume-linux.html?icmpid=docs\_ec2\_console) _- by AWS_\
&#x20; _- EBS 먼저 볼륨 증가후EC2에서 볼륨설정하는 법_

### S3

upload\_file & download\_file : multipart 기능\
put\_object & get\_object : 기본 업로드 기능 (파일 통째로)

[boto3 - File transfer configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/s3.html#uploads) - in AWS

[AWS S3 Multipart Upload/Download using Boto3 (Python SDK)](https://medium.com/analytics-vidhya/aws-s3-multipart-upload-download-using-boto3-python-sdk-2dedb0945f11)\
&#x20; \-  파일이 100MB 이상일 경우, multipart 사용을 권장 ( CLI는 자동 기능 존재 )&#x20;

[Querying data without servers or databases using Amazon S3 Select](https://aws.amazon.com/ko/blogs/storage/querying-data-without-servers-or-databases-using-amazon-s3-select/) - by AWS\
&#x20; \- 미리 필터링 연산 및 비용 절감 가능&#x20;
