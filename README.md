## ** - AWS 활용 계획 - **

이번 프로젝트의 계획은 정돈된 인터페이스, 구조화된 정보, 안전한 배포를 목표로 하고 있습니다. 
아직 무슨 웹 사이트를 만들지 정하지는 않았지만 AWS로 업로드하는 것이 목적인 만큼 간단한 웹 사이트를 만들고
그것을 AWS에 올리는 것이 주 목적이라고 할 수 있겠습니다.

---

##  - 프로젝트 간단 요약 -

AWs 6조는 **HTML + CSS + JavaScript** 로 간단한 웹사이트를 개발하고, 이를 Aws 위에 배포하여  
실제 서비스 환경에서 운영이나, 보안, 데이터 관리를 직접 경험하고 지식을 쌓을 수 있도록 하겠습니다.

---

## - 단계별 작업 흐름 - 

| 단계 | 내용 | 사용 서비스·도구 |
| --- | --- | --- |
| 1. 디자인·기능 구현 | Visual Studio Code 등으로 프론트엔드 개발 | html, css, 자바스크립트 |
| 2️. 코드 버전 관리 | 팀원이 동시에 작업하고 기록 추적 | git, gitHub |
| 3️. 정적 파일 호스팅 | 완성된 파일을 S3 버킷에 업로드 | amazon S3 |
| 4️. 배포 가속 | 빠른 응답, HTTPS 적용 | cloudfront |
| 5️. 사용자 도메인 연결 | Route 53 에 도메인 레코드 설정 | route 53 |
| 6️. 권한 분리,보안 | IAM User Group Policy로 팀별 권한 분리 | IAM (필수 x 추가 공부 사항)|
| 7️. 모니터링,로깅 | 성능·오류 확인, 비용 최적화 | cloudwatch (필수 x 추가 공부 사항)|

---

## - 목표 -

- 팀워크 강화 : GitHub Flow로 협업 절차 숙달
- 클라우드 이해도 향상 : AWS 핵심 서비스를 실습  
- 보안 및 성능 최적화 : HTTPS,캐싱,정적 웹 배포 패턴을 체득  
- 데이터베이스 기초 경험 : 필요 시 RDS 또는 dynamo데이터베이스 연동 

---

## - 혹시 모를 참고 링크 (AWS 사이트) -

- [AWS S3 정적 웹 호스팅 문서](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/WebsiteHosting.html)
- [CloudFront 배포 시작하기](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/GettingStarted.html)
- [GitHub Pages 가이드](https://aws.amazon.com/ko/blogs/)
