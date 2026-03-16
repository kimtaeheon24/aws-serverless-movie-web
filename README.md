# 🎬 TAEHEON MOVIE WORLD
AWS 기반의 서버리스 영화 정보 플랫폼입니다.

## 🛠 Tech Stack
- **Frontend:** S3, Route 53
- **Backend:** API Gateway, AWS Lambda (Python)
- **Database:** DynamoDB

## 🚀 Key Features & Troubleshooting
- **서버리스 아키텍처:** EC2 없이 S3와 Lambda를 활용하여 비용 최적화 및 관리 효율성 달성
- **Decimal 처리:** DynamoDB의 특수 데이터 타입을 JSON으로 변환하기 위해 Custom Encoder 구현
- **이중 트리거:** API Gateway와 Application Load Balancer(ALB)를 모두 트리거로 구성하여 테스트 완료
