# AWS

[Your Comprehensive Guide to Understanding AWS Data Transfer Costs](https://medium.com/@mulupuru/your-comprehensive-guide-to-understanding-aws-data-transfer-costs-f5c8241d65ed)

 [AWS SSM로 VPN없이 Private 자원 접근하기](https://beomi.github.io/2020/02/13/AWS-SSM-with-Bastion/) - by Beomi's Tech Blog  
  -  _AWS SSM + Bastion EC2 + SSH 터널링_

[AWS SSM 배스천호스트 터널링으로 RDS\(PGDB\) 에 연결하기](http://blog.haandol.com/2020/05/01/bastion-host-tunnel-rds.html)

[AWS Data Streaming Data Solution for Amazon Kinesis 소개](https://aws.amazon.com/ko/about-aws/whats-new/2020/09/introducing-aws-data-streaming-data-solution-for-amazon-kinesis/?sc_channel=em&sc_campaign=GLOBAL_CT_NL_global-snapshot-newsletter_20200910_&sc_medium=em_294590&sc_content=PA_nl_la&sc_geo=mult&sc_country=global&sc_outcome=pa&trk=em_294590&mkt_tok=eyJpIjoiTkdZeU1XRmlOREZqWmpRNSIsInQiOiJLbTBYRnVWc3FVV2EzdlpWVTBjczVjc0xWRDN2Z3AyRzZ5c2dQdjZIYVJ2NmZ5VnpVRjNxUnF0WjJPUXFmMzhVZVd3Y2Q2SHlvczFxSmpZXC9aNTdCdThLdnVBbHdONXhjQXBaWFQ1TTgxUWpVTmoycGNoOHlaTHhHNmR3NXhudmxLV2N5MDhUV2x2eWQyU3I0K2EzamdRPT0ifQ%3D%3D) - by AWS

### S3

upload\_file & download\_file : multipart 기능  
put\_object & get\_object : 기본 업로드 기능 \(파일 통째로\)

[boto3 - File transfer configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/s3.html#uploads) - in AWS

[AWS S3 Multipart Upload/Download using Boto3 \(Python SDK\)](https://medium.com/analytics-vidhya/aws-s3-multipart-upload-download-using-boto3-python-sdk-2dedb0945f11)  
  -  파일이 100MB 이상일 경우, multipart 사용을 권장 \( CLI는 자동 기능 존재 \) 

### Lambda - FaaS

[Why You Should Never, Ever print\(\) in a Lambda Function](https://towardsdatascience.com/why-you-should-never-ever-print-in-a-lambda-function-f997d684a705#--responses)  
  -  Lamda Error를 처리하는 효율적인 방법 \(+ cloudwatch logs\) 

[Processing Large S3 Files With AWS Lambda](https://medium.com/swlh/processing-large-s3-files-with-aws-lambda-2c5840ae5c91)  
  -  S3의 대용량 데이터를 chunk 단위로 나누어 처리하는 방법  
  -  시간 제한에 맞춰 새로운 Lambda 작업을 트리거하여 작업을 이어서 처리함

[  
](https://medium.com/@hang.c?source=post_page-----2c5840ae5c91----------------------)



