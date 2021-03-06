---
title: "실습 환경 셋업"
weight: 20
pre: "<b>2. </b>"
---

{{% notice note %}}
다음 장에서 생성한 CloudFormation의 스택은 이 실습환경을 전부 포함하고 있습니다. 
{{% /notice%}}
 

#### 실습환경
![AWS-Code-Cycle](/images/war/awswellarchitected.svg)

#### 사용 서비스
![AWS-Code-Cycle](/images/war/awsservice.svg)


| 이름 | 설명|
|:---|:---|
| **Amazon EC2** | Amazon Elastic Compute Cloud(EC2)는 안전하고 크기 조정이 가능한 컴퓨팅 파워를 클라우드에서 제공하는 웹 서비스입니다. 개발자가 더 쉽게 웹 규모의 클라우드 컴퓨팅 작업을 할 수 있도록 설계되었습니다. Amazon EC2의 간단한 웹 서비스 인터페이스를 통해 간편하게 필요한 용량을 얻고 구성할 수 있습니다. 컴퓨팅 리소스에 대한 포괄적인 제어권을 제공하며, Amazon의 검증된 컴퓨팅 환경에서 실행할 수 있습니다. |
| **Application Load Balancer** | 로드 밸런서는 클라이언트에 대한 단일 접점 역할을 수행합니다. 로드 밸런서는 여러 가용 영역에서 EC2 인스턴스 같은 여러 대상에 수신 애플리케이션 트래픽을 분산합니다. 이렇게 하면 애플리케이션의 가용성이 향상됩니다. 로드 밸런서에 하나 이상의 리스너를 추가할 수 있습니다. |
| **Amazon RDS** | Amazon Relational Database Service(RDS)를 사용하면 클라우드에서 관계형 데이터베이스를 간편하게 설정, 운영 및 확장할 수 있습니다. 하드웨어 프로비저닝, 데이터베이스 설정, 패치 및 백업과 같은 시간 소모적인 관리 작업을 자동화하면서 비용 효율적이고 크기 조정 가능한 용량을 제공합니다. 사용자가 애플리케이션에 집중하여 애플리케이션에 필요한 빠른 성능, 고가용성, 보안 및 호환성을 제공할 수 있도록 지원합니다. | 
| **AWS Auto Scaling** | AWS Auto Scaling은 애플리케이션을 모니터링하고 용량을 자동으로 조정하여, 최대한 저렴한 비용으로 안정적이고 예측 가능한 성능을 유지합니다. AWS Auto Scaling을 사용하면 몇 분 만에 손쉽게 여러 서비스 전체에서 여러 리소스에 대해 애플리케이션 규모 조정을 설정할 수 있습니다. | 

-[CloudFomration을 이용하여 실습환경을 셋팅해보겠습니다.](/setup/lab-setup-master) 
