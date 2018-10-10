## 모임이 추구하는 가치
 * 개인의 전문성 확보. 전문성 확보 과정에서의 즐거움.

## 가치 추가에 따른 기대 결과
위 가치를 이루기 위한 과정에서 얻을 수 있을 것으로 기대하는 결과들
 * 개인의 전문성을 사회에 발현시킨다. 안정적이고 빠르고, 적절한 서비스를 개발. 이런 서비스를 개발 할 수 있는 인프라 혹은 플랫폼을 설계하고 그 결과를 회사에 제안하고 그 위에서 개발을 할 수 있다.
 * 전문성을 확보한 공동체(네트워크) 구성 
 * 사회 & 서비스 & 기술 변화에 공동체로 적응. 정보 공유, 커리어 설계, 기술적인 도움, 직업 및 사업 기회 발굴.
 * AWS 커뮤니티에서 공식적으로 전문성을 인정 받음.

## AWS 자격증 자체의 가치
  * 높은 가용성, 확장성, 안정성, 보안성을 가지는 애플리케이션과 서비스 설계/배포/운영을 위한 전문성을 보유하고 있음을 입증.
  * AWS 관련 기술 숙련도에 대한 가시적인 증명
  * 고용주와 동료간 신뢰조성

## 모임 운영 방식
아직 결정된 건 없습니다. 논의해서 바뀔 수 있습니다.
  * 기수 방식으로 닫힌 커뮤니티
  * 5명 정도로 시작 주 1회 매주 금요일 모임 : 첫 번째 모임은 10월 5일로 계획
  * 어떤 이유로 모임에 참여하지 못했을 경우, 해당 모임에서의 정보들은 git 문서 (문서 작성이 늦어지거나 충분한 내용을 담지 못할 수 있으므로)혹은 개인적으로 습득한다.
  * 현업 실무자 중심
  * 초기에는 범용적인 정보를 습득할 수 있다고 생각되는 솔류션 아키텍트 영역을 집중하고, 이후 DevOps, 개발, 스페셜 영역으로 세분화. 
  * 기수는 목표로하는 자격증이 있다. 
  * 새로만들어지는 기수의 경우, 이전 기수에서 그룹을 리딩하는 역할을 수행 한다. 

## 모임 준비 사항
AWS 자격증 로드맵을 만들어서 자격증을 취득하는게 목표입니다. 모든 내용은 AWS 웹 콘솔 혹은 AWS CLI를 이용해서, 직접 개발&테스트를 하면서 진행 자신의 것으로 만들려고 합니다. 따라서 아래의 것들을 미리 준비하고 테스트해야 합니다.
  * AWS 계정 생성 - 필수 
  * AWS 계정 생성 후 VM 생성을 하고 접속을 한다. - 필수
  * IAM을 발급 받아서 CLI를 이용 VM 목록을 확인하고 VM을 생성한다. - 옵션

## 학습 방향
AWS&클라우드 기술을 체화해야겠지만 "목표는 자격 취득"입니다.
  * 각 로드맵 단계에서의 FAQ 문서
  * 각 로드맵 단계에서의 AWS 기술 백서
  * 각 로드맵을 위해서 AWS 공식 사이트에서 제공하는 문서들
을 중점적으로 다룹니다.

단 실제 업무 환경에서의 적용 & 경험을 통한 체화도 목표 중 하나이므로, 각 단계에서의 리더는 서비스 시나리오를 만들어서 공유 할 수 있도록 길잡이 역할을 하게 됩니다. 예를 들어 Solution Architect 라면
  * 로컬에서의 이미지 처리 고가용성 서비스에 대한 레퍼런스 아키텍처를 만들고, 세부 컴포넌트들을 어떻게 구성해야 할지를 "자격 취득 학습을 통해서 얻은 지식을 기반으로" 토론한다.
  * 토론을 기반으로 간단한 서비스 구성을 과제로 하고 토론한다.
등의 심화학습을 계획 합니다.

## 자격증 로드맵
![이미지](src/cert-roadmap-update-horz.db90b31e06fa36d126fb6caed07119b1a71181db.png)

## 기본 준비 사항 
클라우드 개념, AWS 서비스, 보안, 아키텍처, 요금 및 지원에 대한 개요를 제공한다. AWS에 대한 기초로 전반적인 내용을 다룬다. Associate와 Professional을 위한 기본단계다. 이 자격은 "옵션"이다. 
  * AWS의 실무 적용만이 목표라면 굳이 들을 필요는 없겠으나, 목표가 "자격증 취득"이므로 읽어야 한다.
  * [AWS Cloud Practitioner essentials](https://aws.amazon.com/ko/training/course-descriptions/cloud-practitioner-essentials/)를 각자 학습 후 1회 토론으로 끝낸다. 
  * [Cloud Concepts](cloud-practitioner-essentials/CloudConcepts.md)
  * [AWS Key Service](cloud-practitioner-essentials/KeyService.md)

## 시험 범위에 해당되는 AWS공식문서들
### 전체
- [AWS 한국어 설명서 목록](https://aws.amazon.com/ko/blogs/korea/ko-documentation/)
- [AWS 백서](https://aws.amazon.com/ko/whitepapers/)
  - [Amazon Web Services 개요](https://d1.awsstatic.com/International/ko_KR/whitepapers/aws-overview.pdf)
  - [Architecting for the Cloud](https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [AWS 보안 모범 사례](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
  - [AWS 스토리지 서비스 개요](https://d1.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf)
  - [AWS Well-Architected Framework](https://d1.awsstatic.com/International/ko_KR/whitepapers/Well-Architected%20Framework%20Whitepaper.pdf)
  - [클라우드를 위한 아키텍처 설계: AWS 모범 사례](https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [AWS Lambda를 사용한 서버리스 아키텍처](https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf)
- [AWS 아키텍처 센터](https://aws.amazon.com/ko/architecture/)


### 영역 1: 복원력을 갖춘 아키텍처 설계
- AWS 글로벌 인프라의 이해
  - [AWS 글로벌 인프라](https://aws.amazon.com/ko/about-aws/global-infrastructure/)
  - [EC2의 지역 및 가용영역 선택](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
  - [Amazon CloudFront 글로벌 엣지 네트워크](https://aws.amazon.com/ko/cloudfront/details/)
- 클라우드 서비스를 설계하는 방법
  - [AWS 고급 아키텍처 방법론](http://www.slideshare.net/awskorea/aws-cloud-track-2-advanced)
  - [AWS 기반의 마이크로 서비스 아키텍쳐 구현 방안](http://www.slideshare.net/awskorea/micro-service-oriented-architecture-on-aws-piljoong-kim)
- 느슨한 결합을 구현하기 위한 서비스들
  - [ELB FAQ](https://aws.amazon.com/ko/elasticloadbalancing/faqs/)
  - [SQS FAQ](https://aws.amazon.com/ko/sqs/faqs/)
- 계획 및 설계
  - [클라우드를 위한 아키텍처 설계 - 모범 사례](https://amz.kr/pdf/Architecture_Best_Practices_draft-KR.pdf)
  - [AWS 고객 사례 모음](https://www.awsseoul.kr/images/content/aws-korea-customer-cases-2016.pdf) 
- 안정적이고 복원력을 갖춘 스토리지 선택하기
  - [EC2 스토리지](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/Storage.html)
  - [EC2 인스턴스 스토어](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [EBS FAQ](https://aws.amazon.com/ko/ebs/faqs/)
  - [EFS FAQ](https://aws.amazon.com/ko/efs/faq/)
  - [S3 FAQ](https://aws.amazon.com/ko/s3/faqs/)
  - [Galcier FAQ](https://aws.amazon.com/ko/glacier/faqs/)
  - [Storage Gateway FAQ](https://aws.amazon.com/ko/storagegateway/faqs/)

- 모범 사례
  - [EC2 모범사례](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-best-practices.html)
  - [RDS 모범사례](http://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/CHAP_BestPractices.html)
- 가격/비용을 비롯한 클라이언트 사양 개발(예: 온디맨드 vs. 예약 vs. 스폿, RT  - 및 RP  - DR디자인)
  - [Amazon EC2 요금](https://aws.amazon.com/ko/ec2/pricing/)
- 아키텍처적 트레이드오프(고가용성과 비용 간 트레이드오프, Amazon Relational Database Service(RDS)를 사용하는 것과 Amazon Elastic Compute Cloud(EC2)에 자체 데이터베이스를 설치하는 것 간의 트레이드오프)
  - [Amazon Relational Database Service(Amazon RDS)는 무엇인가?](http://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Welcome.html)
- 기존 개발 환경과의 통합 및 확장형 아키텍처 구축
  - [AWS Enterprise Summit: 하이브리드 클라우드 인프라를 통한 데이터센터 확장과 마이그레이션 방안](http://www.slideshare.net/awskorea/aws-enterprise-summit-67243885)
- 탄력성 및 확장성
  - [AWS 클라우드에서의 웹 애플리케이션 호스팅](http://d0.awsstatic.com/whitepapers/International/ko/AWS_Web_Hosting_Best_Practices_05252010.pdf)
  - [RDS의 고가용성(다중 AZ)](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)
  - [Amazon CloudWatch를 사용하여 Auto Scaling 인스턴스 및 그룹 모니터링](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/as-instance-monitoring.html)
  - [Auto Scaling 그룹에 로드 밸런서 사용](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/autoscaling-load-balancer.html)

### 영역 2: 성능이 뛰어난 아키텍처 정의
- 캐시 사용하기
  - [ElastCache FAQ](https://aws.amazon.com/ko/elasticache/faqs/)
  - [Amazon CloudFront – 제품 세부 정보](https://aws.amazon.com/ko/cloudfront/details/)
- [Amazon Machine Image:AMI](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/AMIs.html)
- 탄력성과 확장성
  - [자동화된 탄력성](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-automating-elasticity/introduction.html)
  - [적절한 크기 조정: 워크로드에 맞춰 인스턴스를 프로비저닝](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-right-sizing/introduction.html)
  - [천만 사용자를 위한 AWS 클라우드 아키텍처 진화하기 - 이창수 솔루션즈 아키텍트](https://www.youtube.com/watch?v=HI0fPiZpniY)

### 영역 3: 안전한 애플리케이션 및 아키텍처
- [클라우드 보안 모범 사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Best_Practices_11052013.pdf)
- [AWS 한글 보안 기술 백서](https://aws.amazon.com/ko/blogs/korea/aws-security-whitepapers/)
- [보안 프로세스의 개요](http://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Whitepaper_Overview.pdf)
- [AWS Security by Design](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/Intro_to_Security_by_Design.pdf)
- [AWS IAM 모범사례](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/best-practices.html)
  - 책임 분담 보안 모델 ([클라우드 보안 모범 사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/AWS_Security_Best_Practices_11052013.pdf) 안에 포함되어 있음)
  - AWS 플랫폼 규정 준수
    - [AWS 클라우드 규정 준수](https://aws.amazon.com/ko/compliance/)
  - AWS 보안 속성(고객 워크로드부터 물리적 계층까지)
    - [규모별 보안: AWS 기반 거버넌스](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Security_at_Scale_Governance_in_AWS_Whitepaper.pdf)
    - [규모별 보안: AWS에서 로깅하기](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Security_at_Scale_Logging_in_AWS_Whitepaper.pdf)
  - 보안 서비스
    - [AWS Identity and Access Management(IAM)](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/introduction.html)
    - [Amazon Virtual Private Cloud(VPC)](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_Introduction.html)
  - CIA 및 AAA 모델, 인바운드 및 아웃바운드 필터링 그리고 이에 맞는 AWS 서비스 및 기능
  - ‘핵심’ Amazon EC2 및 S3 보안 기능 집합
    - [Amazon S3 리소스에 대한 액세스 권한 관리](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/s3-access-control.html)
  - 공통적인 일반 보안 제품 통합(방화벽, IDS:HIDS/NIDS, SIEM, VPN)
  - 디자인 패턴
    - [AWS Cloud Design Patterns](http://en.clouddesignpattern.org/index.php/Main_Page)
    - [Monitoring Integration Pattern](http://en.clouddesignpattern.org/index.php/CDP:Monitoring_Integration_Pattern)
  - DDos 완화
    - [DDoS 대응을 위한 AWS 모범사례](https://d0.awsstatic.com/International/ko_KR/whitepapers/DDoS_White_Paper.pdf)
  - [암호화 솔루션](http://d0.awsstatic.com/International/ko_KR/whitepapers/Compliance/AWS_Securing_Data_at_Rest_with_Encryption.pdf)
  - 정교한 액세스 제어(세밀한 보안 그룹, ACL 등 구축)
    - [VPC의 보안그룹](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_SecurityGroups.html)
    - [네트워크 ACL](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_ACLs.html)
  - [보안 아키텍트를 위한 Amazon CloudWatch](https://aws.amazon.com/ko/cloudwatch/details/)
- [AWS를 사용하는 백업 및 복구 접근 방식](https://d0.awsstatic.com/whitepapers/Storage/LocalizedBR/Backup_and_Recovery_Approaches_Using_AWS_whitepaper_KR.pdf)

- [Amazon S3에서 CloudFront 사용](http://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/MigrateS3ToCloudFront.html)

### 영역4. 비용에 최적화된 아키텍처 설계
- [비용 최적화](https://aws.amazon.com/ko/pricing/cost-optimization/)
- AWS 클라우드 비용 최적화를 위한 모범 사례-AWS Summit Seoul 2017
  - [장표](https://www.slideshare.net/awskorea/2-good-cases-of-aws-cloud-cost-optimization)
  - [세션영상](https://www.youtube.com/watch?v=Ks0hJ2CTFsA)
- [AWS 총 소유 비용(TCO) 계산기](https://aws.amazon.com/ko/tco-calculator/)
- [AWS 월 비용 계산기](https://calculator.s3.amazonaws.com/index.html)
- [적절한 크기 조정: 워크로드에 맞춰 인스턴스를 프로비저닝](https://docs.aws.amazon.com/ko_kr/aws-technical-content/latest/cost-optimization-right-sizing/introduction.html)

### 영역5. 운영에 탁월한 아키텍처 정의
- 운영 관련 서비스들
  - [AWS Config](https://aws.amazon.com/ko/config/faq/)
  - [AWS CloudFormation](https://aws.amazon.com/ko/cloudformation/faqs/)
  - [AWS Trusted Advisor](https://aws.amazon.com/ko/premiumsupport/ta-faqs/)
  - [Amazon Inspector](https://aws.amazon.com/ko/inspector/faqs/)
  - [VPC Flow Logs](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/flow-logs.html)
  - [Amazon Cloudwatch](https://aws.amazon.com/ko/cloudwatch/faqs/)
    - [Amazon CloudWatch Logs](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
  - [AWS CloudTrail](https://aws.amazon.com/ko/cloudtrail/faqs/)
  - [AWS Trusted Advisor](https://aws.amazon.com/ko/premiumsupport/trustedadvisor/)
- [모니터링 모범사례](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/monitoring_best_practices.html)
- [AWS 운영을 위한 체크리스트](https://d1.awsstatic.com/whitepapers/aws-operational-checklists.pdf)
- 일반적인 문제 해결 정보 및 질문
  - [인스턴스 연결 중 오류 발생: 연결시간 초과](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/TroubleshootingInstancesConnecting.html#TroubleshootingInstancesConnectionTimeout)
  - [인스턴스 문제 해결](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instance-troubleshoot.html)
  - [IAM 문제 해결](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/troubleshoot.html)
- [AWS Service Limits](http://docs.aws.amazon.com/ko_kr/general/latest/gr/aws_service_limits.html): AWS에는 요청으로 변경 가능한 제한(Soft Limits)과 변경이 불가능한 제한(Hard Limits)이 있습니다.
  - [Amazon EC2 서비스 제한](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-resource-limits.html) 
- [Amazon EC2 인스턴스 FAQ](https://aws.amazon.com/ko/instance-help/)

## 부록
### 부록1. AWS 공인 솔루션스 아키텍트 – 어소시에이트 : 시험준비 워크샵에서 소개된 링크들
- [EBS FAQ](https://aws.amazon.com/ebs/faqs/)
- [백서 – AWS 스토리지 서비스 개요](https://d0.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf)
- [실습 – Amazon Elastic Block Store 소개](https://amazon.qwiklabs.com/focuses/3458?locale=en)
- [Amazon EC2 인스턴스 스토어](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)

- [ELB FAQ](https://aws.amazon.com/ko/elasticloadbalancing/faqs/)
- [CloudWatch FAQ](https://aws.amazon.com/ko/cloudwatch/faqs/)
- [Auto Scaling FAQ](https://aws.amazon.com/ko/ec2/autoscaling/faqs/)

- [SQS FAQ](https://aws.amazon.com/sqs/faqs/)
- [ELB FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)
- [ELB 설명서](https://aws.amazon.com/documentation/elastic-load-balancing/)
- [EIP FAQ](https://aws.amazon.com/ec2/faqs/)
- [Route 53 설명서](https://aws.amazon.com/documentation/route53/)

- [AWS Well Architected 프레임워크](https://aws.amazon.com/architecture/well-architected/)

- [Amazon Web Services: 보안 프로세스의 개요](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Whitepaper.pdf)
- [AWS 보안 모범 사례 백서](https://d0.awsstatic.com/whitepapers/aws-security-best-practices.pdf)
- [IAM 모범 사례](http://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [AWS 액세스 키를 관리하기 위한 모범 사례](http://docs.aws.amazon.com/general/latest/gr/aws-access-keys-best-practices.html)

- [AWS 리인벤트 2015: VPC 기본 사항 및 연결 옵션](https://www.youtube.com/watch?v=5_bQ6Dgk6k8)
- [AWS 클라우드의 Linux 배스천 호스트](https://s3.amazonaws.com/quickstart-reference/linux/bastion/latest/doc/linux-bastion-hosts-on-the-aws-cloud.pdf)
- [Amazon VPC는 무엇입니까?](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html)

- [AWS에서 데이터 보호 동영상](https://www.youtube.com/watch?v=Tb_W1w_TwLk)

- [저장 데이터 보호 백서](https://d0.awsstatic.com/whitepapers/AWS_Securing_Data_at_Rest_with_Encryption.pdf)

- [Amazon S3 개발자 안내서의 “암호화를 사용한 데이터 보호”](http://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)

- [Amazon Web Services: 보안 프로세스 개요 백서](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Whitepaper.pdf)

- [IAM Policies and Bucket Policies and ACLs! Oh, My! (Controlling Access to S3 Resources) - Amazon 보안 블로그](http://blogs.aws.amazon.com/security/post/TxPOJBY6FE360K/IAM-policies-and-Bucket-Policies-and-ACLs-Oh-My-Controlling-Access-to-S3-Resourc)

### 부록2. 시험에 자주 나오는 서비스들
- [EC2](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/concepts.html) : AWS의 핵심서비스인 만큼 EC2에 대한 내용은 무척 비중있게 다루어집니다.
  - [인스턴스 및 AMI](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instances-and-amis.html)
  - [인스턴스 유형](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/instance-types.html)
  - [인스턴스 구입 옵션](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/instance-purchasing-options.html)
  - [리전 및 가용 영역](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
  - [Amazon EC2 루트 디바이스 볼륨](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/RootDeviceStorage.html)
  - [Amazon EC2 모니터링](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/monitoring_ec2.html)
  - [네트워크 및 보안](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EC2_Network_and_Security.html)
  - [스토리지](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/Storage.html)
  - [Amazon EC2 인스턴스 스토어](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [Auto Scaling 설명서](http://docs.aws.amazon.com/ko_kr/autoscaling/latest/userguide/WhatIsAutoScaling.html)
  - [탄력적 네트워크 인터페이스(ENI:Elastic Network Interface)](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/using-eni.html)
  - [EIP](https://aws.amazon.com/ec2/faqs/)
  - [인스턴스 메타데이터 및 사용자 데이터](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instance-metadata.html)
- [VPC](https://aws.amazon.com/ko/vpc/faqs/)
  - [VPC 사용자 가이드](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/VPC_Introduction.html)
  - [VPC 피어링이란?](http://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/PeeringGuide/Welcome.html)
  - [Amazon Virtual Private Cloud 를 이용한 IT 인프라의 확장](http://d0.awsstatic.com/International/ko_KR/whitepapers/Extend%20your%20IT%20infrastructure%20with%20Amaon%20VPC.pdf)
- [Elastic Beanstalk](https://aws.amazon.com/ko/elasticbeanstalk/faqs/)
  - [Elastic Beanstalk를 이용한 웹 앱 배포](http://docs.aws.amazon.com/ko_kr/gettingstarted/latest/deploy/overview.html)
- [EBS](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSVolumes.html)
  - [EBS FAQ](https://aws.amazon.com/ko/ebs/faqs/)
  - [EBS 볼륨 유형](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSVolumeTypes.html)
  - [EBS 스냅샷](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSSnapshots.html)
  - [EBS 암호화](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSEncryption.html)
  - [Linux 인스턴스의 Amazon EBS 볼륨 성능](http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSPerformance.html)
- [EFS](https://aws.amazon.com/ko/efs/faq/)
- S3
  - [Amazon S3 FAQ](https://aws.amazon.com/ko/s3/faqs/)
  - [Amazon S3 리소스에 대한 액세스 권한 관리](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/s3-access-control.html)
  - [S3 스토리지 클래스](https://aws.amazon.com/ko/s3/storage-classes/)
  - [S3 Reduced Redundancy Storage](https://aws.amazon.com/ko/s3/reduced-redundancy/)
- [CloudFormation](https://aws.amazon.com/ko/cloudformation/faqs/)
- [OpsWorks](https://aws.amazon.com/ko/opsworks/faqs/)
- [Amazon SNS](https://aws.amazon.com/ko/sns/faqs/)
- [Amazon SQS](https://aws.amazon.com/ko/sqs/faqs/)
- [AWS Storage Gateway](https://aws.amazon.com/ko/storagegateway/faqs/)
- [Amazon Kinesis](https://aws.amazon.com/ko/kinesis/streams/faqs/)
- [Amazon EMR](https://aws.amazon.com/ko/emr/faqs/)
- [AWS Direct Connect](https://aws.amazon.com/ko/directconnect/)
- [AWS Import/Export](https://aws.amazon.com/ko/documentation/importexport/?nc1=h_ls)
- [AWS Directory Service](https://aws.amazon.com/ko/directoryservice/faqs/)
- [Amazon Route53](https://aws.amazon.com/ko/route53/details/)
- [Amazon CloudFront](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [AWS ECS](https://aws.amazon.com/ko/ecs/faqs/)
  - [AWS ECR](https://aws.amazon.com/ko/ecr/faqs/)
- [AWS KMS](https://aws.amazon.com/ko/kms/faqs/)
- [Amazon DynamoDB](https://aws.amazon.com/ko/dynamodb/faqs/)
  - [SQL에서 NoSQL로](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/SQLtoNoSQL.html)
  - [프로비저닝된 처리량](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/HowItWorks.ProvisionedThroughput.html)
  - [DynamoDB의 쿼리 및 스캔 작업](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/QueryAndScan.html)
  - [파티션 및 데이터 배포](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/HowItWorks.Partitions.html)
- [Amazon MQ](https://aws.amazon.com/ko/amazon-mq/faqs/)

## Professional 등급

## AWS Certified Developer 
## AWS Certified DevOps Engineer 
## AWS Specialty Certifications 
### AWS Certified Advanced Networking
### AWS Certified Big Data 
### AWS Certified Security 
